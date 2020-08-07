---
title: 前端知识体系整理
date: 2019-12-22
toc: true
thumbnail: https://gitee.com/heptaluan/backups/raw/master/cdn/cover/12.jpg
---

> 最后更新于 `2020-07-26`

虽然工作时间不短了，但是却从来没有静下心来好好梳理一下自己所掌握的东西，博客当中的许多内容都是在工作当中遇到，然后查阅资料解决后随手记录的一些知识点，亦或是无意间看到个新东西觉得好玩学一下，明天又看到那个有意思学一下，但是却没有真正的整理构建过属于自己的知识体系，所以在这里打算对照当下的前端知识体系，从新的整理一份个人的前端知识体系，主要包括以下几部分

* 梳理已经熟练掌握的知识
* 复习之前已经掌握但并不算熟练的知识
* 补习自身没有掌握，但是知道是必须要掌握的知识

目的是希望能让自己达到一定的深度和广度，其实说那么多，最主要的目的还是明确未来的方向，并有一个比较好的规划，这样才能让自己的职业生涯走的更远不是，这里推荐一篇文章 [《一个程序员的成长之路》](https://github.com/fouber/blog/issues/41)，虽然文章是很早之前的了，但是依然给了我比较多关于未来的思考，也明确了我未来短期内的一个方向

本文当中所涉及到的知识点绝大部分都可以在 [博客](https://heptaluan.github.io/) 和 [随笔](https://github.com/heptaluan/web-warehouse/tree/master/interview) 当中找到，路漫漫其修远兮，与君共勉

<!--more-->







<!-- 

IndexDB

Service Workers

-->




## HTML

* `WEB` 标准与 `W3C`
* 文档类型（`DOCTYPE`）
* `HTML` 基本结构
* `HTML5` 标签
* 渐进增强与优雅降级


## CSS

* 盒模型
* 样式来源与层叠规则（层叠权重值）
* 伪类与伪元素
* 经典布局（文档流布局，浮动布局，定位布局，圣杯布局，双飞翼布局，`flex` 布局，`grid` 布局）
* `BFC/IFC/hasLayout`


## JavaScript

* `ECMAScript`
  * `ES5`
    * 基本数据类型（类型判断与类型转换）
    * 运算符/位运算符（优先级，`==/===/||/&&/^/~` 等）
    * 函数（值和引用/冒泡与捕获）
    * 调用堆栈
      * 变量提升，作用域，执行上下文栈，变量对象和活动对象
      * 内存空间与机制，常见内存泄漏及如何避免
    * 对象（创建/遍历/原型和原型对象/原型继承和类式继承）
    * `this`（常见的调用方式，如何确定 `this` 的值）
    * 闭包（柯里化与偏函数）
    * 深浅拷贝
    * 高阶函数
    * 防抖和节流
    * 模块加载
  * `ES6+`
    * 块级作用域/模板字符串
    * `Class/Reflect/Symbol/Set/Map/Generator/Iterator/Arrow Function`
* `BOM` 和 `DOM`
  * `DOM`（节点类型/节点类型/节点操作）
  * `BOM`（`Window/Navigator/Screen/History/Location`）
* 相关 `API`
  * `XHR API`
    * 跨域（同源策略/解决方式）
    * `XHR Level 2`
  * 原生 API
    * `call/apply/bind`
    * `parseInt/parseFloat/JSON.parse/JSON.stringify`
    * `IntersectionObserver`
    * `requestAnimationFrame`
* 异步（`Callback/Promise/Generator/Async/Await`）
* `V8` 引擎工作原理
  * 垃圾回收机制
  * 并发模型（`EventLoop/MacroTask/MicroTask`）
* 设计模式
  * 单例模式，工厂模式，代理模式，观察者模式，发布订阅模式
* `TypeScript`
  * 常用语法（基础类型/枚举/元祖等）
  * 类型断言/变量声明
  * 接口/泛型/类型判断/高级类型
* 正则表达式








## 主流框架

* `Angular`
  * 生命周期流程
  * 变化检测机制
  * 依赖注入
  * 装饰器
  * 动态加载
  * `rxjs`
  * `ngrx` 与 `@effect`
* `Vue`
  * 生命周期流程
  * 双向绑定原理
  * `Router` 原理
  * `Vuex`
* `React`
  * 生命周期流程
  * `Virtual DOM` 与 `Diff` 算法
  * `Redux/Flux/React-Redux`
  * `Middleware`
  * `Hook`




## 工程实践

* 模块化/组件化
* `Webpack`
  * `AST/Babel/Babylon/Loader/Library`
  * 构建方式/配置/优化
* 性能优化（字体优化/精灵图/懒加载/预加载/静态资源的渲染阻塞/选择器优化/表达式优化）
* 微前端


## 计算机网络

* 网络基础知识
* 七层 `OSI` 模型
* `HTTP/HTTPS`
  * 状态码
  * 缓存机制
  * 报文头
* `TCP/IP`
  * 三次握手/四次挥手
  * 滑动窗口（慢启动/拥塞控制）
  * 可靠通信（`TCP` 状态机）
* `UDP`
* `WebSocket`
* 网络安全








## 浏览器

* `HTTP` 请求流程
* 浏览器缓存
* 渲染机制
  * `DOM/CSSOM/Render-Tree`
  * 重绘/回流
* 用户认证（`Session`，`Cookie`，`Token`，`JWT`）
* 安全
  * `TLS`（非对称加密原理）
  * 网络攻击（`XSS`，`CSRF`，数据库注入）



## 服务端

* `Node.js`
  * `CommonJS/AMD/CMD`
  * `module.exports` 与 `exports`
  * 原生模块（`Http/Buffer/EventEmitter/Stream`）
  * 多进程与事件轮询机制
  * `Koa/Egg`
* 数据库
  * `MySQL`
  * `SQLite`




## 数据结构与算法

* 线性表（顺序存储结构/链式存储结构/双向链表/双向循环链表）
* 栈和队列
* 递归
* 数组/字符串（`BF/KMP`）
* 树和二叉树
  * 二叉树的遍历/二叉排序树/平衡二叉排序树
  * 最小生成树（普里姆算法和克鲁斯卡尔算法）
* 图结构
  * 存储结构与遍历
  * 最短路径（迪杰斯特拉算法和弗洛伊德算法）
  * 关键路径（拓扑排序，`AOV` 网与 `AOE` 网）
* 查找算法
  * 顺序查找/二分查找/插值查找/斐波那契查找/线性索引查找（有序）
  * 散列表查找（无序）
* 排序算法
  * 比较排序（冒泡排序/选择排序/插入排序/希尔排序/归并排序/快速排序/堆排序）
  * 非比较排序（计数排序/基数排序/桶排序）




## 数学

* 线性代数
  * 矩阵
  * 矩阵的秩
* 高等数学
  * 链式求导
  * 梯度 && 导数 && 偏导




## 编译原理

* 待补充

## 趋势

想捣鼓但没时间折腾，记录一下

* `PWA`
* `WebAssembly`
* `Flutter`
* `Microservices`
* `ServerLess/GraphSQL`
* `D3/WebGL`
* `WebRTC`/静态生成/人工智能前端化




