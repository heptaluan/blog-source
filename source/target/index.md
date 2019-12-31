---
title: 前端知识体系整理
date: 2019-12-27
toc: true
thumbnail: https://gitee.com/heptaluan/backups/raw/master/cdn/cover/111.jpg
---

> 最后更新于 2019-12-27

因为年后有换工作的打算，所以准备在年前这最后一段时间当中好好复习一下，梳理一下掌握的知识结构

之前有很多内容都是在工作当中遇到，然后查阅资料解决后随手记录的一些知识点，可能看上去比较零散

所以在这里打算对照当下的前端知识体系，将博文当中的内容从新过一遍，从新的整理一下

剔除掉一些过时的内容和补充一些之前没有涉及到的知识点，不过主要目的还是为了梳理一下自己所掌握的前端知识体系和为年后的面试做准备

与君共勉

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
  * [ALT 与 TITLE](https://heptaluan.github.io/2017/01/10/JavaScript/02/)
  * canvas && svg
  * 响应式 meta
* 渐进增强与优雅降级






## CSS

* 盒模型
* [样式来源与层叠规则](http://heptaluan.github.io/2017/09/03/CSS/11/)
* [link 和 @import](https://heptaluan.github.io/2017/11/11/CSS/10/)
* 选择器
  * [优先级策略（I-C-E）](http://localhost:4000/2017/09/22/CSS/03/#%E7%89%B9%E6%8C%87%E5%BA%A6%EF%BC%88I-C-E%EF%BC%89)
  * [伪类与伪元素](http://heptaluan.github.io/2018/11/25/CSS/04/)
* 样式表继承
* [常见布局方式](https://heptaluan.github.io/2019/09/12/CSS/12/)
  * 文档流布局
  * 浮动布局
  * 定位布局
  * 圣杯布局
  * 双飞翼布局
  * flex 布局
    * [flex 取值](http://heptaluan.github.io/2019/01/12/CSS/09/)
  * grid 布局
* CSS3
  * filter
  * 媒体查询
  * Transform && Animation
  * [px，em，rem，vw 和 vh](http://heptaluan.github.io/2019/08/04/CSS/11/)
* [BFC](http://heptaluan.github.io/2018/12/03/CSS/06/)
  * [浮动原理与解决办法](https://heptaluan.github.io/2016/11/09/CSS/01/)
  * 高度塌陷
  * Margin 塌陷
  * position 嵌套 && 覆盖
* [IFC](http://heptaluan.github.io/2018/12/05/CSS/07/)
* [haslayout](http://heptaluan.github.io/2018/12/12/CSS/08/)
* [FOUC](http://heptaluan.github.io/2019/07/07/JavaScript/44/)




## JavaScript

* ECMAScript
  * ES5
    * [基本数据类型](https://heptaluan.github.io/2017/02/22/JavaScript/06/)
      * [类型判断](http://heptaluan.github.io/2018/03/17/JavaScript/30/)
      * [类型转换](https://heptaluan.github.io/2017/03/17/JavaScript/09/)
    * [运算符](http://heptaluan.github.io/2018/05/27/JavaScript/33/)
      * [== 和 ===](http://localhost:4000/2017/03/17/JavaScript/09/)
      * [|| 和 &&](https://heptaluan.github.io/2017/05/19/JavaScript/19/)
    * [函数](http://heptaluan.github.io/2017/10/08/JavaScript/26/)
      * [作用域与执行上下文栈](https://heptaluan.github.io/2017/01/18/JavaScript/03/)
      * [事件与事件流](https://heptaluan.github.io/2016/11/14/JavaScript/01/)
      * [parseInt](https://heptaluan.github.io/2017/04/15/JavaScript/12/)
    * [对象](http://heptaluan.github.io/2017/10/07/JavaScript/25/)
      * [如何遍历对象](http://heptaluan.github.io/2019/06/28/JavaScript/42/)
    * [this](http://heptaluan.github.io/2017/10/09/JavaScript/27/)
    * [原型和原型对象](http://localhost:4000/2017/04/08/JavaScript/11/)
    * [闭包](http://localhost:4000/2017/05/12/JavaScript/17/)
    * [深浅拷贝](http://localhost:4000/2018/01/14/JavaScript/29/)
    * 高阶函数
    * 模块加载
  * ES6+
    * 块级作用域
    * 模板字符串
    * [Symbol，Set 和 Map](https://heptaluan.github.io/2019/11/07/JavaScript/60/)
    * Promise
    * Async
    * [Class](http://heptaluan.github.io/2017/09/20/JavaScript/24/)
    * [Reflect](http://heptaluan.github.io/2017/09/21/JavaScript/53/)
    * [迭代器与生成器](http://heptaluan.github.io/2019/07/13/JavaScript/56/)
    * proxy
    * 箭头函数
* [DOM](http://heptaluan.github.io/2017/06/26/JavaScript/21/)
  * 创建节点 / 插入节点 / 删除节点 / 替换节点 / 克隆节点 / 览器对象
  * Window 对象
  * History 对象
  * Location 对象
  * Screen 对象
* offset，scroll，client
* Event 事件
* XHR API
  * 同源策略
  * [跨域](http://heptaluan.github.io/2018/04/26/JavaScript/39/)
    * JSONP / CORS / form / document.domain / window.name / location.hash / postMessage / Nginx / webpack proxy / WebSocket
* [并发模型](http://heptaluan.github.io/2018/08/12/JavaScript/36/)
  * Event Loop
  * 进程与线程
  * MacroTask && MicroTask
  * [单线程执行机制](http://heptaluan.github.io/2019/05/04/JavaScript/54/)
  * [栈和堆](http://heptaluan.github.io/2019/05/05/JavaScript/55/)
* [垃圾回收机制](http://heptaluan.github.io/2017/12/25/Essay/02/)
  * 标记清除
  * 引用计数
* WebAssembly
* [IntersectionObserver](https://heptaluan.github.io/2019/09/22/JavaScript/58/)
* [正则表达式](https://heptaluan.github.io/2019/10/17/JavaScript/59/)
* [设计模式](http://heptaluan.github.io/2017/08/17/JavaScript/47/)
  * [单例模式/工厂模式/代理模式/观察者模式/发布订阅模式](https://heptaluan.github.io/2019/08/02/JavaScript/57/#%E5%8D%95%E4%BE%8B%E6%A8%A1%E5%BC%8F)






## 主流框架

* Angular
  * 生命周期
  * [依赖注入](http://heptaluan.github.io/2018/12/26/Angular/03/)
  * [装饰器](http://heptaluan.github.io/2018/01/15/Angular/05/)
  * [管道](http://heptaluan.github.io/2018/01/11/Angular/04/)
  * [动态加载](http://heptaluan.github.io/2019/05/12/Angular/08/)
  * [变化检测机制](http://heptaluan.github.io/2019/07/22/Angular/16/)
  * [rxjs](http://heptaluan.github.io/2019/06/04/Angular/11/)
  * ngrx
  * @effect
* Vue
  * 生命周期流程
  * [双向绑定原理](http://heptaluan.github.io/2018/07/10/JavaScript/34/)
  * HTML 模板
  * 组件通信机制
  * 高阶组件
  * Router原理
  * [Mixin](http://heptaluan.github.io/2018/04/15/Vue/02/)
  * [Vuex](http://heptaluan.github.io/2018/08/13/Vue/07/)
    * [State，Getter，Mutation，Action](http://heptaluan.github.io/2018/08/15/Vue/06/)
    * [Store](http://heptaluan.github.io/2018/08/25/Vue/09/)
    * [installModule，resetStoreVM，plugins](http://heptaluan.github.io/2018/09/04/Vue/10/)
* React
  * [Virtual DOM 与 Diff 算法](http://localhost:4000/2019/12/22/React/18/)
    * [什么是 Virtual DOM？](http://localhost:4000/2019/12/15/React/15/)
    * [渲染器](http://localhost:4000/2019/12/20/React/16/)
    * [渲染器的核心 Diff 算法](http://localhost:4000/2019/12/22/React/17/)
  * 生命周期
  * jsx
  * [路由](http://heptaluan.github.io/2019/01/12/React/04/)
  * [Redux](https://heptaluan.github.io/2019/11/25/React/15/#Redux%E3%80%81Flux-%E5%92%8C-React-Redux)
    * Flux
    * Redux
    * Redux 官方示例剖析
    * React-Redux
    * Redux、Flux 和 React-Redux 三者之间的区别
    * Redux 源码初探
  * [Hook](https://heptaluan.github.io/2019/11/23/React/14/)
  * 组件状态管理






## 工程实践

* 模块化 && 组件化
* 用户鉴权
  * OAuth
* 依赖构建
  * Webpack
    * [loader 和 plugin](http://heptaluan.github.io/2018/09/12/Vue/13/)
  * Gulp
  * Rollup
* 包管理
* 性能优化
  * [前端字体优化](https://heptaluan.github.io/2019/08/18/Essay/04/)
  * base64编码 && 精灵图
  * 懒加载 && 预加载
  * 静态资源的渲染阻塞
  * CSS 选择器优化 && 表达式优化
  * CDN







## 浏览器

* 渲染机制
  * DOM
  * CSSOM
  * 重绘 && 回流
  * shadow DOM
* 浏览器缓存
  * Cookie
  * Storage
  * IndexDB
  * Service Workers
* [域名发散与收敛](http://heptaluan.github.io/2017/12/01/HTTP/03/)
* [字符编码](http://heptaluan.github.io/2017/12/24/Essay/01/)
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











## 服务端

* Node.js
  * [什么是 Node.js](https://heptaluan.github.io/2019/09/01/Node/08/)
  * [CommonJS、AMD 和 CMD](https://heptaluan.github.io/2017/02/03/JavaScript/05/)
  * [Node.js 中的 libuv](https://heptaluan.github.io/2019/07/05/Node/06/)
  * [Node.js 的模块机制](https://heptaluan.github.io/2019/09/28/Node/11/)
  * [module.exports 和 exports](http://heptaluan.github.io/2018/06/05/Node/04/)
  * [Http 模块](https://heptaluan.github.io/2019/10/02/Node/12/)
  * [Buffer 模块](https://heptaluan.github.io/2019/09/22/Node/10/)
  * [EventEmitter 模块](https://heptaluan.github.io/2019/09/12/Node/09/)
  * [Stream](http://heptaluan.github.io/2018/07/12/Node/01/)
    * Readable && Writable
    * Duplex && transform
    * 流式数据处理
    * [背压（back pressure）](https://heptaluan.github.io/2019/10/09/Node/13/)
    * Browserify && Gulp 设计机制
  * 模块
    * [co](http://heptaluan.github.io/2018/07/22/Node/02/)
    * [SuperAgent](http://heptaluan.github.io/2019/01/02/Node/03/)
  * koa
    * [简易 koa 的实现](https://heptaluan.github.io/2019/10/25/Node/16/#%E6%A1%86%E6%9E%B6%E7%9A%84%E5%AE%9E%E7%8E%B0)
    * [中间件](https://heptaluan.github.io/2019/10/19/Node/15/)
    * [常用中间件的实现](https://heptaluan.github.io/2019/10/25/Node/16/#koa-logger)
    * [koa.js 源码解析](https://heptaluan.github.io/2019/10/30/Node/17/)
  * egg
    * [实现一个接口服务](https://heptaluan.github.io/2019/11/01/Node/18/)
    * [相关问题汇总](https://heptaluan.github.io/2019/11/06/Node/19/)
* 数据库
  * SQL
    * 时间函数
    * 读锁和写锁
    * 数据类型
      * char && varchar
    * 命令调用
      * drop，delete，truncate
    * [事务和锁](http://heptaluan.github.io/2018/11/04/MySQL/02/)
    * [缓存穿透和缓存雪崩](http://heptaluan.github.io/2018/03/03/MySQL/01/)
* ELK
* 进程与线程
  * 互斥与死锁











## 计算机网络

* 七层 OSI 模型
* HTTP
  * 1.0 && 1.1 && 2.0
    * 1.0
    * 1.1 持久化
    * [http 2.0](http://heptaluan.github.io/2018/05/09/HTTP/06/)
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
  * [http 报文头](http://heptaluan.github.io/2019/08/17/HTTP/07/)
* TCP
  * 三次握手 && 四次挥手
  * 滑动窗口（慢启动 && 拥塞控制）
  * 可靠通信（TCP 状态机）
* UDP
* WebSocket






## 数据结构

* 字符串 && 数组 && 链表
* 哈希表 && 二叉树 && 队列 && 栈







## 算法

* BFS && DFS
* 动态规划
* 位运算
* 排序
  * 冒泡 && 选择 && 快排 && 归并
  * 分布式排序
* 滑动窗口





## 数学

* 线性代数
  * 矩阵
  * 矩阵的秩
* 高等数学
  * 链式求导
  * 梯度 && 导数 && 偏导




## 编译原理

* 待补充






