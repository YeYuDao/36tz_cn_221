# 36tz_cn_221
React服务器渲染原理解析与实践
React服务器渲染原理解析与实践
👇👇👇👇👇👇👇👇点击下载地址👇👇👇👇👇👇👇
[![download](https://51xueit.vip/muke_img/5fce02d609b9854b05400304.jpg "下载地址")](http://www.36tz.cn "下载地址")
### 第1章 服务器端渲染基础 

#### 本章主要讲解客户端与服务器端渲染的概念，分析客户端渲染和服务器端渲染的利弊，带大家对服务器端渲染有一个粗浅认识。
1-1 课程导学 (09:28)

1-2 什么是服务器端渲染 (10:02)

1-3 什么是客户端渲染 (05:10)

1-4 React 客户端渲染的优势与弊端 (08:59)


### 第2章 React中的服务器端渲染

#### 本章将借助Node.js，Webpack等工具的帮助，带大家实现一个非常基础的基于React.js技术栈的服务器端渲染模型，过程中还会讲解虚拟DOM与服务器端渲染的内在联系。
2-1 在服务器端编写 React 组件 (06:34)

2-2 服务器端 Webpack 的配置 (18:25)

2-3 实现服务器端组件渲染 (10:02)

2-4 建立在虚拟DOM上的服务器端渲染 (06:50)

2-5 Webpack 的自动打包与服务器自动重启 (12:01)

2-6 使用 npm-run-all 提升开发效率 (06:15)


### 第3章 同构的概念的梳理 

#### 服务器端渲染与同构的概念实际上并不完全一致，React中的SSR实际上指的是同构技术，那么什么是同构技术，它和服务器端渲染的关系是什么，React中如何实现同构呢？这一章节将给大家详细讲解。
3-1 什么是同构 (04:10)

3-2 在浏览器上执行一段 JS 代码 (05:57)

3-3 让 React 代码在浏览器上运行 (12:52)

3-4 工程代码优化整理 (07:25)

3-5 阶段总结 (02:06)


### 第4章 在SSR框架中引入路由机制

#### 本章将给大家讲解如何在当前的SSR框架中引入React-Router，从而使得我们的服务器端渲染框架能够支持路由跳转，SSR的路由跳转比前端路由或后端路由都要复杂一些，这张我们将细致的讲解整个SSR路由的执行流程。
4-1 服务器端渲染中的路由 (12:47)

4-2 多页面路由跳转 (06:47)

4-3 使用Link标签串联起整个路由流程 (07:34)


### 第5章 SSR框架与Redux的结合 

#### 本章将讲解如何将Redux数据管理框架与SSR框架做结合，使SSR框架能够支撑复杂业务的开发。在这一章节中，我们将详细讲解服务器端异步数据获取的流程和方法，同时也给大家讲解清楚什么是同构中的数据脱水与注水。
5-1 我们常常听说的中间层是什么？ (06:08)

5-2 同构项目中引入 Redux (11:13)

5-3 创建 Store 代码的复用 (06:29)

5-4 构建 Redux 代码结构 ( 1 ) (19:08)

5-5 构建Redux代码结构(2) (12:37)

5-6 如何获取最新的secret值 (01:49)

5-7 流程回顾及问题分析 (10:32)

5-8 异步数据服务器渲染： loadData方法及路由重构 (20:21)

5-9 Favicon 及多级路由问题的处理 (09:22)

5-10 服务器端渲染获取数据 (20:56)

5-11 数据的脱水和注水 (13:53)


### 第6章 使用Node作为数据获取中间层

#### 本章将讲解真正服务器端渲染中的代码架构体系，Node.js如何在这个体系中充当中间层的作用，这里面我们将详细讲解数据代理转发，cookie登陆状态传递，axios实例等概念。
6-1 使用proxy代理，让中间层承担数据获取职责 (19:26)

6-2 服务器端请求和客户端请求的不同处理 (07:43)

6-3 axios中instance的使用 (11:49)

6-4 redux-thunk中的withExtraArgument (11:37)

6-5 renderRoutes 方法实现对多级路由的支持 (16:38)

6-6 登陆功能的制作 (15:51)

6-7 登陆接口打通 (16:43)

6-8 登陆状态切换 (15:18)

6-9 解决登陆 cookie 传递问题 (09:03)

6-10 翻译列表页面制作 (25:23)


### 第7章 细节问题处理

#### 本章将讲解在SSR框架中，如何处理301重定向，404页面不存在的情况，以及面对异步数据获取失败的情况，应该如何借助Promise解决问题。
7-1 secret统一管理 (06:55)

7-2 借助 context 实现404页面功能 (17:03)

7-3 实现服务器端301重定向 (07:56)

7-4 数据请求失败情况下 promise 的处理 (17:28)


### 第8章 处理SSR框架中的CSS样式

#### 本章将讲解在SSR框架中，组件和页面中CSS样式的处理方案，在这章中，我们还会应用高阶组件等设计技巧，提高代码复用性。
8-1 如何支持 CSS 样式修饰 (16:18)

8-2 如何实现CSS样式的服务器端渲染 (12:05)

8-3 多组件中的样式如何整合 (10:37)

8-4 LoadData 方法潜在问题的修正 (04:53)

8-5 使用高阶组件精简代码 (11:50)

8-6 列表样式优化 (09:14)


### 第9章 SEO技巧的融入

#### 本章将讲解SEO中的一些基本技巧，以及如何通过React-helmet等技术，提升当前SSR框架的SEO效果，最后，还会给大家讲解SSR外的另一种解决SEO问题的思路：预渲染。
9-1 什么是SEO， 为什么服务器端渲染对SEO更加友好 ？ (08:50)

9-2 Title 和 Description的真正作用 (06:28)

9-3 如何做好 SEO (09:09)

9-4 React-Helmet 的使用 (12:07)

9-5 课程总结 (12:08)

9-6 使用预渲染解决SEO问题的新思路 (20:29)


[下载地址](http://www.36tz.cn "下载地址")
