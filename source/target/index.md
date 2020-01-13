---
title: 前端知识体系整理
date: 2019-12-27
toc: true
thumbnail: https://gitee.com/heptaluan/backups/raw/master/cdn/cover/88.jpg
---

> 最后更新于 2019-12-27

虽然工作时间不短了，但是却从来没有静下心来好好整理一下自己掌握的东西，博客当中的许多内容都是在工作当中遇到，然后查阅资料解决后随手记录的一些知识点，可能看上去比较零散

所以在这里打算对照当下的前端知识体系，从新的整理成一份前端知识体系，针对博文当中一些过时的内容进行剔除和补充一些之前没有涉及到的知识点

不过主要目的还是为了梳理一下自己所掌握的知识点，目标是能将下面的个人版本前端知识体系渐渐扩充起来，达到一定的广度和深度，不过路漫漫其修远兮，与君共勉

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
* HTML5
  * 语义化标签
  * [ALT 与 TITLE](https://heptaluan.github.io/2016/10/10/JavaScript/02/)
  * Canvas && Svg
  * 响应式 meta
* 渐进增强与优雅降级






## CSS

* 盒模型
* [样式来源与层叠规则](https://heptaluan.github.io/2017/09/22/CSS/03/)
  * 优先级策略（I-C-E）
  * 样式表继承
* [link 和 @import](https://heptaluan.github.io/2017/11/11/CSS/10/)
* [伪类与伪元素](https://heptaluan.github.io/2018/11/25/CSS/04/)
* 常见布局方式
  * 文档流布局 / 浮动布局 / 定位布局 / 圣杯布局 / 双飞翼布局 / flex 布局 / grid 布局
* CSS3
  * filter
  * 媒体查询
  * Transform && Animation
  * px，em，rem，vw 和 vh
  * [文本溢出隐藏](https://heptaluan.github.io/2016/12/02/CSS/02/)
* [BFC](https://heptaluan.github.io/2018/12/03/CSS/06/)
  * 高度塌陷
  * Margin 塌陷
  * position 嵌套 && 覆盖
  * [浮动清除](https://heptaluan.github.io/2016/11/09/CSS/01/)
* [IFC](https://heptaluan.github.io/2018/12/05/CSS/07/)
* [haslayout](https://heptaluan.github.io/2018/10/12/CSS/08/)



## JavaScript

* ECMAScript
  * ES5
    * 基本数据类型
      * [类型判断](https://heptaluan.github.io/2018/03/17/JavaScript/25/)
      * 类型转换
    * 运算符
      * [优先级](https://heptaluan.github.io/2018/05/27/JavaScript/28/)
      * [== 和 ===](https://heptaluan.github.io/2017/03/17/JavaScript/08/)
      * [|| 和 &&](https://heptaluan.github.io/2017/05/19/JavaScript/15/)
    * [函数](https://heptaluan.github.io/2017/10/08/JavaScript/21/)
      * [length 和 callee 属性](https://heptaluan.github.io/2017/07/04/JavaScript/17/)
      * [作用域与执行上下文栈](https://heptaluan.github.io/2017/01/18/JavaScript/03/)
      * [事件与事件流](https://heptaluan.github.io/2016/11/14/JavaScript/01/)
    * [值和引用](https://heptaluan.github.io/2017/02/22/JavaScript/06/)
    * [对象](https://heptaluan.github.io/2017/10/07/JavaScript/20/)
      * [对象的遍历](https://heptaluan.github.io/2019/06/28/JavaScript/35/)
    * [this](https://heptaluan.github.io/2017/10/09/JavaScript/22/)
      * 常用的调用方式
      * 如何确定 this 的值（reference）
    * [原型和原型对象](https://heptaluan.github.io/2017/04/08/JavaScript/09/)
      * [Object.create()](https://heptaluan.github.io/2017/03/03/JavaScript/07/)
    * [闭包](https://heptaluan.github.io/2017/05/12/JavaScript/14/)
    * 继承
      * [原型继承和类式继承](https://heptaluan.github.io/2018/01/10/JavaScript/23/)
    * [防抖和节流](https://heptaluan.github.io/2020/01/05/JavaScript/49/)
    * [深浅拷贝](https://heptaluan.github.io/2018/01/14/JavaScript/24/)
    * 高阶函数
    * 模块加载
  * ES6+
    * 块级作用域
    * 模板字符串
    * [Symbol，Set 和 Map](https://heptaluan.github.io/2019/11/07/JavaScript/48/)
    * [Promise](https://heptaluan.github.io/2018/03/19/JavaScript/26/)
    * Async
    * [Class](https://heptaluan.github.io/2017/09/20/JavaScript/19/)
    * [Reflect](https://heptaluan.github.io/2017/09/21/JavaScript/43/)
    * [迭代器与生成器](https://heptaluan.github.io/2019/07/13/JavaScript/44/)
    * proxy
    * 箭头函数
* [BOM 和 DOM](https://heptaluan.github.io/2017/11/17/JavaScript/16/)
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
    * [跨域](https://heptaluan.github.io/2018/04/26/JavaScript/33/)
      * 同源策略
      * JSONP / CORS / form / document.domain / window.name / location.hash / postMessage
      * Nginx / webpack proxy / WebSocket
  * 原生 API
    * [parseInt() 与 parseFloat()](https://heptaluan.github.io/2017/04/15/JavaScript/10/)
    * [IntersectionObserver](https://heptaluan.github.io/2019/09/22/JavaScript/46/)
    * [call 和 apply](https://heptaluan.github.io/2018/04/16/JavaScript/27/)
    * [bind](https://heptaluan.github.io/2017/05/07/JavaScript/13/)
    * [JSON.parse() 与 JSON.stringify()](https://heptaluan.github.io/2017/07/06/JavaScript/18/)
    * [Map 与 forEach](https://heptaluan.github.io/2018/09/12/JavaScript/31/)
    * [Object.defineProperty](https://heptaluan.github.io/2017/05/02/JavaScript/12/)
    * [Object.keys](https://heptaluan.github.io/2019/03/16/JavaScript/32/)
    * [requestAnimationFrame](https://heptaluan.github.io/2018/06/11/JavaScript/38/)
* [并发模型](https://heptaluan.github.io/2018/08/12/JavaScript/30/)
  * 单线程执行机制
  * 栈和堆
  * Event Loop
  * MacroTask && MicroTask
* [数据双向绑定](https://heptaluan.github.io/2018/07/10/JavaScript/29/)
  * 数据劫持
  * proxy
* [垃圾回收机制](https://heptaluan.github.io/2017/12/25/Essay/02/)
  * 标记清除
  * 引用计数
* [异步加载](https://heptaluan.github.io/2017/09/19/JavaScript/42/)
* [正则表达式](https://heptaluan.github.io/2019/10/17/JavaScript/47/)
* 设计模式
  * 单例模式 / 工厂模式 / 代理模式 / 观察者模式 / 发布订阅模式
* 第三方库
  * [jQuery](https://heptaluan.github.io/2017/06/23/jQuery/02/)
    * [jQuery.fn.init()](https://heptaluan.github.io/2017/07/11/jQuery/03/)
    * [辅助方法](https://heptaluan.github.io/2017/07/15/jQuery/04/)
  * [Zepto](https://heptaluan.github.io/2019/05/28/JavaScript/34/)
* WebAssembly




## 主流框架

* Angular
  * [Angular-CLI](https://heptaluan.github.io/2018/12/12/Angular/01/)
  * 生命周期
  * [变化检测机制](https://heptaluan.github.io/2019/07/22/Angular/16/)
  * [:host 和 ::ng-deep](https://heptaluan.github.io/2018/01/16/Angular/06/)
  * [&#91;&#91;&#93;&#93; 和 &#123;&#123;&#125;&#125; 的区别](https://heptaluan.github.io/2019/06/22/Angular/14/)
  * [Angular Component](https://heptaluan.github.io/2019/08/27/Angular/09/)
  * 依赖注入
    * [为什么要使用依赖注入](https://heptaluan.github.io/2018/12/14/Angular/02/)
    * [Angular 中的依赖注入](https://heptaluan.github.io/2018/12/26/Angular/03/)
  * [装饰器](https://heptaluan.github.io/2018/01/15/Angular/05/)
  * [表单](https://heptaluan.github.io/2019/05/27/Angular/10/)
  * [管道](https://heptaluan.github.io/2018/01/11/Angular/04/)
  * [动态加载](https://heptaluan.github.io/2019/05/12/Angular/08/)
  * [WebSocket](https://heptaluan.github.io/2019/05/20/Angular/15/)
  * [rxjs](https://heptaluan.github.io/2019/06/04/Angular/11/)
    * [高阶操作符](https://heptaluan.github.io/2019/06/08/Angular/12/)
  * ngrx
  * @effect
* Vue
  * 生命周期流程
  * 双向绑定原理
  * HTML 模板
  * 组件通信机制
  * 高阶组件
  * Router原理
  * [Mixin](https://heptaluan.github.io/2018/04/15/Vue/01/)
  * Vuex
    * [初始化装载](https://heptaluan.github.io/2018/08/13/Vue/03/)
    * [Store](https://heptaluan.github.io/2018/08/25/Vue/04/)
* React
  * [Virtual DOM 与 Diff 算法](https://heptaluan.github.io/2019/12/15/React/06/)
    * 什么是 Virtual DOM？
    * 渲染器
    * 渲染器的核心 Diff 算法
  * 生命周期
  * jsx
  * 路由
  * [Flux 与 Redux](https://heptaluan.github.io/2019/02/22/React/01/)
    * [Redux、Flux 和 React-Redux](https://heptaluan.github.io/2019/04/02/React/02/)
    * [Redux](https://heptaluan.github.io/2019/06/05/React/03/)
      * compose()
      * bindActionCreators()
      * createStore()
      * applyMiddleware()
  * [Hook](https://heptaluan.github.io/2019/11/23/React/04/)
  * [Middleware](https://heptaluan.github.io/2019/12/13/React/05/)
  * 组件状态管理






## 工程实践

* 模块化 && 组件化
* 依赖构建
  * Webpack
    * loader 和 plugin
  * Gulp
  * Rollup
* 包管理
* 性能优化
  * [前端字体优化](https://heptaluan.github.io/2019/08/18/Essay/03/)
  * base64编码 && 精灵图
  * 懒加载 && 预加载
  * 静态资源的渲染阻塞
  * CSS 选择器优化 && 表达式优化
  * CDN







## 浏览器

* [输入网址到页面显示经历的过程](https://heptaluan.github.io/2017/11/07/HTTP/01/)
* [渲染机制](https://heptaluan.github.io/2019/07/07/JavaScript/37/)
  * FOUC
  * DOM / CSSOM / Render Tree
  * 重绘 && 回流
* 浏览器缓存
  * Cookie
  * localStorage / sessionStorage
  * IndexDB
  * Service Workers
* [用户认证](https://heptaluan.github.io/2017/11/26/HTTP/02/)
  * Session
  * Cookie
  * Token
  * JWT
* [域名发散与收敛](https://heptaluan.github.io/2017/12/01/HTTP/03/)
* [字符编码](https://heptaluan.github.io/2017/12/24/Essay/01/)
  * ASCII
  * UTF-8
  * GBK && GB2312
* SEO优化
  * meta 标签
* 安全
  * TLS
    * 非对称加密原理
  * 网络攻击
    * XSS
    * CSRF
    * 数据库注入
* 体系结构与操作系统
  * 二进制 / 字节序 / 字节对齐
  * 多任务（进程与线程）
  * 内存管理
  * 磁盘调度










## 服务端

* Node.js
  * [什么是 Node.js](https://heptaluan.github.io/2019/09/01/Node/05/)
  * [CommonJS、AMD 和 CMD](https://heptaluan.github.io/2017/02/03/JavaScript/05/)
  * [module.exports 和 exports](https://heptaluan.github.io/2018/06/05/Node/03/)
  * 原生模块
    * [模块机制](https://heptaluan.github.io/2019/09/28/Node/08/)
    * [Http 模块](https://heptaluan.github.io/2019/10/02/Node/09/)
    * [Buffer 模块](https://heptaluan.github.io/2019/09/22/Node/07/)
    * [EventEmitter 模块](https://heptaluan.github.io/2019/09/12/Node/06/)
    * [Stream](https://heptaluan.github.io/2019/10/14/Node/01/)
      * Readable && Writable
      * Duplex && transform
      * 流式数据处理
      * [背压（back pressure）](https://heptaluan.github.io/2019/10/09/Node/10/)
      * Browserify && Gulp 设计机制
  * 第三方模块
    * [co](https://heptaluan.github.io/2019/01/02/Node/02/)
  * [Node.js 中的事件轮询机制](https://heptaluan.github.io/2019/07/05/Node/04/)
  * [Node.js 中的多进程](https://heptaluan.github.io/2019/05/04/Node/16/)
  * koa
    * [实现原理](https://heptaluan.github.io/2019/10/25/Node/13/)
      * 常用中间件的实现
    * [中间件](https://heptaluan.github.io/2019/10/19/Node/12/)
    * [koa.js 源码解析](https://heptaluan.github.io/2019/10/30/Node/14/)
  * [egg](https://heptaluan.github.io/2019/11/01/Node/15/)
* 数据库
  * MySQL
    * 时间函数
    * 数据类型
      * char && varchar
    * 命令调用
      * drop，delete，truncate
    * [事务和锁](https://heptaluan.github.io/2018/11/04/MySQL/02/)
    * [缓存穿透和缓存雪崩](https://heptaluan.github.io/2018/03/03/MySQL/01/)
* ELK










## 计算机网络

* 七层 OSI 模型
* HTTP
  * 1.0
  * 1.1 持久化
  * [http 2.0](https://heptaluan.github.io/2018/05/09/HTTP/06/)
    * 二进制协议
    * 多工
    * 数据流（连接共享）
    * 头信息压缩
    * 服务端推送
  * 状态码
  * [HTTP 缓存机制](https://heptaluan.github.io/2017/12/12/HTTP/04/)
    * 强缓存和协商缓存
    * Pragma
    * Cache-Control
    * Expires
    * Last-Modified && If-Modified-Since
    * ETag && If-None-Match
  * [http 报文头](https://heptaluan.github.io/2019/08/17/HTTP/07/)
* [TCP](https://heptaluan.github.io/2018/05/05/HTTP/05/)
  * 三次握手 && 四次挥手
  * 滑动窗口（慢启动 && 拥塞控制）
  * 可靠通信（TCP 状态机）
* UDP
* WebSocket






## 数据结构

* [什么是数据结构](https://heptaluan.github.io/2019/12/01/Essay/04/)
* 线性表
  * [顺序存储结构](https://heptaluan.github.io/2019/12/14/Essay/05/)
  * 链式存储结构
* 字符串 && 数组
* 哈希表 && 二叉树 && 队列 && 栈







## 算法

* BFS && DFS
* 动态规划
* 位运算
* 排序
  * 冒泡 && 选择 && 快排 && 归并
  * 分布式排序





## 数学

* 线性代数
  * 矩阵
  * 矩阵的秩
* 高等数学
  * 链式求导
  * 梯度 && 导数 && 偏导




## 编译原理

* 待补充






