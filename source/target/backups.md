


## 泛型

https://www.typescriptlang.org/docs/handbook/utility-types.html

https://jkchao.github.io/typescript-book-chinese/faqs/generics.html

https://jkchao.github.io/typescript-book-chinese/tips/infer.html


对于泛型的大致理解：泛型是用于处理类型的“函数”。

* 函数，对于不同的输入，运算出得不同的结果。
* 泛型，对于不同类型，运算出得相应的另一种类型。

一个简单的代码片段，通过泛型和推断，以下代码拥有正确的类型识别

```ts
type MapEveryToPromise<T extends object> = {
  [K in keyof T]: T[K] extends infer P ? Promise<P> : never;
};

const obj1 = {
  key1: 1,
  key2: 'hello',
};

const obj2: MapEveryToPromise<typeof obj1> = {
  key1: Promise.resolve(1),
  key2: Promise.resolve('hello'),
};
```

泛型常见于各种工具库的源码中（如 Redux、Ramda），
部分工具函数支持用户传入任意类型，得到的结果需要有正确的类型，
那么工具函数对应的类型声明就需要使用泛型完成。


## 重载

https://zhongsp.gitbooks.io/typescript-handbook/content/doc/handbook/Functions.html

TypeScript 中的重载（Overload），是函数声明的重载，和面向对象中的重载有所差异，TS 中的重载是指多个同名的类型声明，具体判断还是要手动实现，手动在唯一的函数本体中进行传参的判断，TS 中的重载：

```js
function simpleAdd(a: number): (b: number) => number;
function simpleAdd(a: number, b: number): number;
function simpleAdd(a, b?) {
  if (b === undefined) return (b) => a + b;
  return a + b;
}
```

而如 Java、C# 中的重载，是直接写多个同名函数本体。Java 中的重载：

```js
class Dog {
  public void bark() {
    System.out.println('woof')
  }
  public void bark(int num) {
    for (int i = 0; i < num; i++)
      System.out.println('woof')
  }
}
```

TS 重载的作用主要用于类型识别上。比如在各种工具库的源码中（如 Redux、Ramda），对于不同的传参情况，会得到不同的对应类型提示，这就需要借助重载。