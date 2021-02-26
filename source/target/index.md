---
title: 前端知识体系整理
date: 2019-12-22
toc: true
thumbnail: https://gitee.com/heptaluan/backups/raw/master/cdn/cover/23.webp
---

> 最后更新于 `2020-10-04`

虽然工作时间不短了，但是却从来没有静下心来好好梳理一下自己所掌握的东西，博客当中的许多内容都是在工作当中遇到，然后查阅资料解决后随手记录的一些知识点，亦或是无意间看到个新东西觉得好玩学一下，明天又看到那个有意思学一下，但是却没有真正的整理构建过属于自己的知识体系，所以在这里打算对照当下比较流行的一些方向，从新的整理一份个人的前端知识体系，主要目的是

* 梳理已经熟练掌握的知识
* 复习之前已经掌握但并不算熟练的知识
* 补习自身没有掌握，但是知道是必须要掌握的知识

希望通过梳理可以让自己的知识面达到一定的深度和广度，其实最主要的目的还是明确未来的方向，并有一个比较好的规划，这样才能让自己的职业生涯走的更远，另外博客当中的一些在初学时期整理的文章全部移动到了 [这里](https://github.com/heptaluan/web-warehouse/tree/master/interview)，本文中所涉及到的内容均可在这两个地方找到

这里推荐一篇文章 [《一个程序员的成长之路》](https://github.com/fouber/blog/issues/41)，虽然文章是很早之前的了，但是依然给了我比较多关于未来的思考，也明确了未来短期内的一个方向，路漫漫其修远兮，与君共勉

<!--more-->





<!-- 


✅

❌


『』




深入函数底层的相关文章

深浅拷贝





React 核心原理，源码分析

Egg + React 实战日记本（总结收夜）



webpack && babel && loader && plugins




正则表达式
https://fe.rualc.com/note/regexp.html

RxJS（从新整理，复习）
https://fe.rualc.com/note/rxjs.html#rxjs-jian-jie

redux-observable
https://fe.rualc.com/note/redux-observable.html#redux-observable-jian-jie



------------

01 月  Docker/自动化测试/rxjs/PWA/微前端

02 月  刷算法，刷面试题

------------


Service Workers

Deno

动态表单

二建



-->




## HTML/CSS

* `HTML`
  * `Web` 标准
  * 文档类型（`DOCTYPE`）
  * `HTML5` 标签新特性
  * 渐进增强与优雅降级
* `CSS`
  * 盒子模型
  * 样式来源与层叠规则（层叠权重值）
  * 伪类与伪元素
  * 经典布局（文档流/浮动/定位/圣杯/双飞翼/`flex`/`grid`）
  * `BFC/IFC/haslayout`
  * `float/display/position/z-index/line-height/vertical-align`


## JavaScript

* `ECMAScript`
  * `ES5`
    * 基本数据类型（类型转换/值和引用的传递/类型判断）
    * 运算符（优先级/隐式类型转换）
    * 对象（定义方式/原型链）
    * 函数（事件流/作用域/执行上下文栈/继承）
    * `this`（调用方式/如何确定 `this` 的值）
    * 闭包（闭包模型/柯里化/反柯里化/偏函数）
    * 深浅拷贝
    * 跨域
  * `ES6+`
    * 块级作用域/模板字符串/迭代器/生成器
    * `Class/Reflect/Symbol/Set/Map/Generator/Iterator/Arrow Function`
* `BOM` 和 `DOM`
  * `DOM`（节点类型/节点关系/节点操作）
  * `BOM`（`Window/Navigator/Screen/History/Location`）
* 手写函数
  * 工具（`once/debounce/thorttle/slowcopy/deepcopy`）
  * 原生（`call/apply/bind/new/Promise/Object.create/instanceof/getOwnPropertyNames`）
  * 数组（`push/unshift/shift/pop/forEach/map/filter/reduce/find/indexOf`）
* 执行过程
  * 同步（调用栈/执行上下文栈/作用域链/`VO`/`AO`）
  * 异步（`Callback/Promise/Generator/Async/Await`）
  * 事件轮询机制（渲染进程/`EventLoop`/任务队列/`requestAnimationFrame`）
* `V8` 引擎
  * 解析器与 `AST`（基线编译器/优化编译器）
  * 内存管理（分配/使用/回收/内存泄漏）
  * 垃圾回收机制
    * 标记清除/引用计数
    * `V8` 垃圾回收策略（内存限制/新生代/晋升/老生代）
* 设计模式
  * 工厂模式/工厂方法模式/观察者模式/发布订阅模式/单例模式/装饰者模式/中介者模式/代理模式
  * 原型模式/外观模式/适配器模式/桥接模式/模版方法模式/状态模式/策略模式/访问模式
* `TypeScript`
  * 基础类型/内置对象/对象类型/数组类型/函数类型
  * 元组/枚举/类与接口（`readonly`/抽象类/私有字段）
  * 泛型（接口/类/约束/参数默认类型/条件类型/工具类型）
* 正则表达式（待整理）




## 主流框架

* `Angular`
  * `Angular-CLI`
  * 生命周期流程/变化检测机制
  * 依赖注入/装饰器/管道
  * 动态加载
  * `rxjs`
  * `ngrx` 与 `@effect`
* `React`
  * 生命周期流程
  * `Virtual DOM` 与 `Diff` 算法
  * `Redux/Flux/React-Redux/Middleware`
  * `Mixin/Render Props/HOC/Hook`
  * `React Fiber`（节点与架构）
* `Vue`
  * 生命周期流程
  * 双向绑定原理
  * `Router` 原理
  * `Vuex`



## 工程实践

* 模块化/组件化
* `Webpack`（待完善）
  * `AST/Babel/Babylon/Loader/Library`
  * 构建方式/配置/优化
* 性能优化（字体优化/精灵图/懒加载/预加载/静态资源的渲染阻塞/选择器优化/表达式优化）
* 微前端


## 计算机网络

* `HTTP/HTTPS`
  * `HTTP` 概述/协议/报文/首部字段/报文实体/状态码
  * 结构组件（代理、网关、隧道、缓存）
  * 用户认证（`Session/Cookie/Token/JWT`）
  * `HTTPS`
  * 追加协议
    * `HTTP/2`
    * `HTTP/3`
  * 安全
* `TCP/IP`
  * `OSI` 参考模型
  * `TCP/IP` 基础与分层模型
  * 数据包与数据处理流程
  * `IP` 协议（地址/组成/分类/广播地址/多播/子网掩码）
  * 路由控制（地址/报文的分片与重组/路径 `MTU` 发现）
  * `IPv4` 与 `IPv6`
  * `IP` 协议相关技术（`DNS/ARP/ICMP/DHCP/NAT`）
  * `TCP` 和 `UDP`
  * 应用层协议
  * 其他应用层协议（多媒体通信实现技术/`H.323/SIP/RTP/P2P/LDAP`）
  * 网络安全（构成要素/防火墙/入侵检测系统/安全协议）





## 浏览器

* `HTTP` 请求流程
* 域名发散与收敛
* 渲染机制
  * `DOM/CSSOM/渲染树`
  * 重绘/回流
* 浏览器缓存
* 前端安全（`XSS/CSRF`）



## 服务端

* `Node.js`
  * 模块机制
  * 原生模块（`HTTP/Buffer/EventEmitter/Stream`）
  * 中间件
  * 多进程与事件轮询机制
  * `Koa.js/Egg.js`
* 数据库（待完善）
  * `MySQL`
  * `SQLite`




## 数据结构与算法

* 线性表（顺序存储结构/链式存储结构/循环链表/双向循环链表）
* 栈和队列
* 递归（尾调用/分治思想/汉诺塔/八皇后问题）
* 树和二叉树
  * 树的定义/二叉树的定义/二叉树的遍历/线索二叉树
  * 树、森林与二叉树之间的转换/赫夫曼树
* 图结构
  * 存储结构与遍历
  * 最小生成树（普里姆算法/克鲁斯卡尔算法）
  * 最短路径（迪杰斯特拉算法/弗洛伊德算法）
  * 关键路径（拓扑序列/拓扑排序/`AOV` 网/`AOE` 网）
* 查找算法
  * 顺序查找/二分查找/插值查找/斐波那契查找/线性索引查找（有序）
  * 散列表查找（无序）
  * 二叉排序树/平衡二叉排序树/散列表查找
* 排序算法
  * 比较排序（冒泡排序/选择排序/插入排序/希尔排序/归并排序/快速排序/堆排序）
  * 非比较排序（计数排序/基数排序/桶排序）




## 数学

* 向量
* 线性代数
  * 矩阵
  * 矩阵的秩
* 高等数学
  * 链式求导
  * 梯度 && 导数 && 偏导





## 待整理

想捣鼓但暂时没时间深入折腾，记录一下

* 正则表达式
* `PWA`
* `RxJS`
* `Docker`
* `Deno`
* `Golang`
* `WebAssembly`
* `Flutter`
* `Microservices`
* `ServerLess/GraphSQL`
* `D3/WebGL`
* `WebRTC`
* `Svelte`


