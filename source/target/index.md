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
  * ALT 与 TITLE
  * canvas && svg
  * 响应式 meta
* 渐进增强与优雅降级






## CSS

* 盒模型
* 样式来源与层叠规则
* link 和 @import
* 选择器
  * 优先级策略（I-C-E）
  * 伪类与伪元素
* 样式表继承
* 常见布局方式
  * 文档流布局
  * 浮动布局
  * 定位布局
  * 圣杯布局
  * 双飞翼布局
  * flex 布局
    * flex 取值
  * grid 布局
* CSS3
  * filter
  * 媒体查询
  * Transform && Animation
  * px，em，rem，vw 和 vh
* BFC
  * 浮动原理与解决办法
  * 高度塌陷
  * Margin 塌陷
  * position 嵌套 && 覆盖
* IFC
* haslayout



## JavaScript

* ECMAScript
  * ES5
    * 基本数据类型
      * 类型判断
      * 类型转换
    * 运算符
      * == 和 ===
      * || 和 &&
    * 函数
      * 作用域与执行上下文栈
      * 事件与事件流
      * parseInt
    * 对象
      * 如何遍历对象
    * this
    * 原型和原型对象
    * 闭包
    * 深浅拷贝
    * 高阶函数
    * 模块加载
  * ES6+
    * 块级作用域
    * 模板字符串
    * Symbol，Set 和 Map
    * Promise
    * Async
    * Class
    * Reflect
    * 迭代器与生成器
    * proxy
    * 箭头函数
* DOM
  * 创建节点 / 插入节点 / 删除节点 / 替换节点 / 克隆节点 / 览器对象
  * Window 对象
  * History 对象
  * Location 对象
  * Screen 对象
* offset，scroll，client
* Event 事件
* XHR API
  * 同源策略
  * 跨域
    * JSONP / CORS / form / document.domain / window.name / location.hash / postMessage / Nginx / webpack proxy / WebSocket
* 并发模型
  * Event Loop
  * 进程与线程
  * MacroTask && MicroTask
  * 单线程执行机制
  * 栈和堆
* 垃圾回收机制
  * 标记清除
  * 引用计数
* WebAssembly
* IntersectionObserver
* 正则表达式
* 设计模式
  * 单例模式/工厂模式/代理模式/观察者模式/发布订阅模式





## 主流框架

* Angular
  * 生命周期
  * 依赖注入
  * 装饰器
  * 管道
  * 动态加载
  * 变化检测机制
  * rxjs
  * ngrx
  * @effect
* Vue
  * 生命周期流程
  * 双向绑定原理
  * HTML 模板
  * 组件通信机制
  * 高阶组件
  * Router原理
  * Mixin
  * Vuex
    * State，Getter，Mutation，Action
    * Store
    * installModule，resetStoreVM，plugins
* React
  * Virtual DOM 与 Diff 算法
    * 什么是 Virtual DOM？
    * 渲染器
    * 渲染器的核心 Diff 算法
  * 生命周期
  * jsx
  * 路由
  * Redux
    * Flux
    * Redux
    * Redux 官方示例剖析
    * React-Redux
    * Redux、Flux 和 React-Redux 三者之间的区别
    * Redux 源码初探
  * Hook
  * 组件状态管理






## 工程实践

* 模块化 && 组件化
* 用户鉴权
  * OAuth
* 依赖构建
  * Webpack
    * loader 和 plugin
  * Gulp
  * Rollup
* 包管理
* 性能优化
  * 前端字体优化
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
* 域名发散与收敛
* 字符编码
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
  * CommonJS、AMD 和 CMD
  * Node.js 中的 libuv
  * 原生模块
    * module.exports 和 exports
    * Node.js 中的模块机制
    * Node.js 中的 Http 模块
    * Node.js 中的 Buffer 模块
    * Node.js 中的 EventEmitter 模块
    * Stream
      * Readable && Writable
      * Duplex && transform
      * 流式数据处理
      * 背压（back pressure）
      * Browserify && Gulp 设计机制
  * 第三方模块
    * co
  * koa
    * 简易 koa 的实现
    * 中间件
    * 常用中间件的实现
    * koa.js 源码解析
  * egg
* 数据库
  * SQL
    * 时间函数
    * 读锁和写锁
    * 数据类型
      * char && varchar
    * 命令调用
      * drop，delete，truncate
    * 事务和锁
    * 缓存穿透和缓存雪崩
* ELK
* 进程与线程
  * 互斥与死锁











## 计算机网络

* 七层 OSI 模型
* HTTP
  * 1.0 && 1.1 && 2.0
    * 1.0
    * 1.1 持久化
    * http 2.0
      * 二进制协议
      * 多工
      * 数据流（连接共享）
      * 头信息压缩
      * 服务端推送
  * 状态码
  * HTTP 缓存机制
    * 强缓存和协商缓存
    * Pragma
    * Cache-Control
    * Expires
    * Last-Modified && If-Modified-Since
    * ETag && If-None-Match
  * http 报文头
* TCP
  * 三次握手 && 四次挥手
  * 滑动窗口（慢启动 && 拥塞控制）
  * 可靠通信（TCP 状态机）
* UDP
* WebSocket






## 数据结构

* 什么是数据结构？
* 线性表
  * 顺序存储结构
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






