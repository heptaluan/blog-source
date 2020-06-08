---
title: 前端知识体系整理
date: 2020-05-30
toc: true
thumbnail: https://gitee.com/heptaluan/backups/raw/master/cdn/cover/12.jpg
---

> 最后更新于 2020-06-06

虽然工作时间不短了，但是却从来没有静下心来好好梳理一下自己所掌握的东西，博客当中的许多内容都是在工作当中遇到，然后查阅资料解决后随手记录的一些知识点

亦或是无意间看到个新东西觉得好玩学一下，明天又看到那个有意思学一下，但是却没有真正的整理构建过属于自己的知识体系

所以在这里打算对照当下的前端知识体系，从新的整理一份个人的前端知识体系，主要目的是

* 梳理已经熟练掌握的知识
* 复习之前已经掌握但并不算熟练的知识
* 补习自身没有掌握，但是知道是必须要掌握的知识

梳理下来差不多就是左侧目录的样子，不过接下来会慢慢进行完善和补充，争取能让自己达到一定的深度和广度

路漫漫其修远兮，与君共勉



<!--more-->



<!-- 

IndexDB

Service Workers

BOM

promise 怎么实现

http/2


----


TypeScript

深入 rxjs

Webpack

node + koa + egg

react/redux


----



WebAssembly 让更多语言可以运行在浏览器上

PWA 进入稳定期，尤其是 PWA 桌面版，可以让我们更好的看清楚 PC 桌面版开发的全貌

Flutter 发展较快，最大硬伤是Dart语言，RN原有的开发方式会退出历史舞台

Microservices

ServerLess\GraphSQL发展迅猛

D3、webgl、SVG

webpack不再是唯一的打包工具选项（Rollup、parcel零配置）

WebRTC、静态生成、人工智能前端化


-->




## HTML

* WEB 标准与 W3C
* 文档类型（DOCTYPE）
* 基本的表单标签
* HTML5
  * 语义化标签
  * [ALT 与 TITLE](http://localhost:4000/2016/10/10/JavaScript/02/)
  * Canvas && Svg
  * 响应式 meta
* 渐进增强与优雅降级






## CSS

* 盒模型
* 样式来源与层叠规则
  * 样式表继承与样式优先级策略（I-C-E）
* link 和 @import
* 伪类与伪元素
* 经典布局
  * 文档流布局，浮动布局，定位布局，圣杯布局，双飞翼布局，flex 布局，grid 布局
* CSS3
  * filter
  * 媒体查询
  * Transform && Animation
  * px，em，rem，vw 和 vh
  * 文本溢出隐藏
* BFC
  * [高度塌陷与清除浮动](http://localhost:4000/2016/11/17/CSS/01/)
  * Margin 塌陷
  * position 嵌套 && 覆盖
* IFC
* haslayout



## JavaScript

* ECMAScript
  * ES5
    * 基本数据类型（类型判断与类型转换）
    * 运算符（优先级，[== 和 ===](http://localhost:4000/2017/03/17/JavaScript/08/)，|| 和 &&）
    * 函数
      * length 和 callee
      * [事件流，冒泡与捕获](http://localhost:4000/2016/12/12/JavaScript/01/)
      * [值和引用](http://localhost:4000/2017/02/22/JavaScript/06/)
    * 调用堆栈
      * [变量提升，作用域，执行上下文栈，变量对象和活动对象](http://localhost:4000/2017/01/18/JavaScript/03/)
      * 内存空间与机制，常见内存泄漏及如何避免
    * 对象
      * 对象的创建
      * [遍历和枚举](http://localhost:4000/2017/04/22/JavaScript/11/)
      * [Object.defineProperty](http://localhost:4000/2017/05/02/JavaScript/12/)
      * [原型和原型对象](http://localhost:4000/2017/04/08/JavaScript/09/)
      * [Object.create()](http://localhost:4000/2017/03/03/JavaScript/07/)
      * 原型继承和类式继承
    * this（常见的调用方式，如何确定 this 的值）
    * [闭包（柯里化与偏函数）](http://localhost:4000/2017/05/12/JavaScript/14/)
    * 深浅拷贝
    * 高阶函数
    * 防抖和节流
    * 模块加载
  * ES6+
    * 块级作用域，模板字符串，Class，Reflect，Symbol，Set 和 Map
    * 迭代器与生成器
    * 箭头函数
* BOM 和 DOM
  * DOM
    * 节点类型
    * 节点关系
    * 节点操作
  * BOM
    * Window 对象
      * Navigator 对象
      * Screen 对象
      * History 对象
      * Location 对象
* 相关 API
  * XHR API
    * 跨域
      * 同源策略
      * JSONP，CORS，form，document.domain，window.name，location.hash，postMessage
      * Nginx，webpack proxy，WebSocket
    * XHR Level 2
  * 原生 API
    * [parseInt() 与 parseFloat()](http://localhost:4000/2017/04/15/JavaScript/10/)
    * IntersectionObserver
    * call，apply，[bind](http://localhost:4000/2017/05/07/JavaScript/13/)
    * JSON.parse() 与 JSON.stringify()
    * Map 与 forEach
    * Object.keys
    * requestAnimationFrame
* 异步
  * 回调函数
  * Promise
  * Generator 
  * Async/Await
* V8 引擎工作原理
  * 垃圾回收机制
    * 标记清除
    * 引用计数
  * 并发模型
    * 单线程执行机制
    * 栈和堆
    * Event Loop
    * MacroTask && MicroTask
* 设计模式
  * 单例模式，工厂模式，代理模式，观察者模式，发布订阅模式
* 第三方库
  * jQuery
    * jQuery.fn.init()
    * 辅助方法
  * Zepto
* WebAssembly
* TypeScript
* 正则表达式






## 主流框架

* Angular
  * Angular-CLI
  * 生命周期
  * 变化检测机制
  * :host 和 ::ng-deep
  * &#91;&#91;&#93;&#93; 和 &#123;&#123;&#125;&#125; 的区别
  * Angular Component
  * 依赖注入
    * 为什么要使用依赖注入
    * Angular 中的依赖注入
  * 装饰器
  * 表单
  * 管道
  * 动态加载
  * rxjs
    * 高阶操作符
  * ngrx 与 @effect
* Vue
  * 生命周期流程
  * 双向绑定原理
  * HTML 模板
  * 组件通信机制
  * 高阶组件
  * Router 原理
  * Mixin
  * Vuex
    * 初始化装载
    * Store
* React
  * Virtual DOM 与 Diff 算法
    * 什么是 Virtual DOM？
    * 渲染器
    * 渲染器的核心 Diff 算法
  * 生命周期
  * jsx
  * 路由
  * Flux 与 Redux
    * Redux、Flux 和 React-Redux
    * Redux（compose()，bindActionCreators()，createStore()，applyMiddleware()）
  * Middleware
  * 组件状态管理
  * Hook






## 工程实践

* 模块化 && 组件化
* 依赖构建
  * Webpack
    * 构建方式，配置与优化
    * babel，loader，plugin，library
  * Gulp
  * Rollup
* 包管理
* 性能优化
  * 前端字体优化
  * base64 编码 && 精灵图
  * 懒加载 && 预加载
  * 静态资源的渲染阻塞
  * CSS 选择器优化 && 表达式优化
  * CDN






## 计算机网络

* 网络基础知识
* 七层 OSI 模型
* HTTP
  * 1.0 与 2.0
    * 二进制协议，多工，数据流（连接共享），头信息压缩，服务端推送
  * 状态码
  * HTTP 缓存机制（强缓存和协商缓存，Pragma，Cache-Control，Expires，Last-Modified && If-Modified-Since，ETag && If-None-Match）
  * HTTP 报文头
* HTTPS
* TCP/IP
  * 三次握手 && 四次挥手
  * 滑动窗口（慢启动 && 拥塞控制）
  * 可靠通信（TCP 状态机）
* UDP
* WebSocket
* 网络安全








## 浏览器

* 输入网址到页面显示经历的过程
* 渲染机制
  * FOUC
  * DOM，CSSOM，Render Tree
  * 重绘 && 回流
* 浏览器缓存（Cookie，localStorage 与 sessionStorage，IndexDB，Service Workers）
* 用户认证（Session，Cookie，Token，JWT）
* 域名发散与收敛
* 字符编码（ASCII，UTF-8，GBK && GB2312）
* SEO优化（meta 标签等）
* 安全
  * TLS
    * 非对称加密原理
  * 网络攻击（XSS，CSRF，数据库注入）
* 体系结构与操作系统
  * 二进制，字节序，字节对齐
  * 多任务（进程与线程）
  * 内存管理
  * 磁盘调度










## 服务端

* Node.js
  * [CommonJS、AMD 和 CMD](http://localhost:4000/2017/02/03/JavaScript/05/)
  * module.exports 和 exports
  * 原生模块
    * Http，Buffer，EventEmitter
    * 模块机制
    * Stream
      * Readable && Writable
      * Duplex && transform
      * 流式数据处理
      * 背压（back pressure）
      * Browserify && Gulp 设计机制
  * 第三方模块
    * co
  * 多进程与事件轮询机制
  * koa
    * 实现原理（包括常用中间件）
    * 中间件
    * koa.js 源码解析
  * egg
* 数据库
  * MySQL
    * 时间函数
    * 数据类型
      * char && varchar
    * 命令调用
      * drop，delete，truncate
    * 事务和锁
    * 缓存穿透和缓存雪崩
* ELK



## 数据结构与算法

* 线性表
  * 顺序存储结构和链式存储结构
  * 静态链表与循环链表
  * 双向链表与双向循环链表
* 栈和队列
* 递归
* 数组 && 字符串（BF 和 KMP）
* 树和二叉树
  * 二叉树的遍历
  * 线索二叉树
  * 树、森林与二叉树之间的转换
  * 最小生成树（普里姆算法和克鲁斯卡尔算法）
  * 二叉排序树和平衡二叉排序树
* 图结构
  * 图的存储结构与遍历
  * 最短路径（迪杰斯特拉算法和弗洛伊德算法）
  * 关键路径（拓扑排序，AOV 网与 AOE 网）
* 查找算法
  * 顺序查找，二分查找，插值查找，斐波那契查找，线性索引查找（有序）
  * 散列表查找（无序）
* 排序算法
  * 比较排序（冒泡排序，选择排序，插入排序，希尔排序，归并排序，快速排序，堆排序）
  * 非比较排序（计数排序，基数排序，桶排序）




## 数学

* 线性代数
  * 矩阵
  * 矩阵的秩
* 高等数学
  * 链式求导
  * 梯度 && 导数 && 偏导




## 编译原理

* 待补充






