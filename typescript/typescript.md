# 一起学习TypeScript


>TypeScript is a typed superset of JavaScript that compiles to plain JavaScript。

[TypeScript](https://www.typescriptlang.org/) 是一种由微软开发的自由和开源的编程语言。它是 JavaScript 的一个超集，而且本质上向这个语言添加了可选的静态类型和基于类的面向对象编程。


## 学习目录


- [目录](#目录)
- [TypeScript 教程](#typescript-教程)
    - [为什么选择 TypeScript](#为什么选择TypeScript)
    - [学习资源](#学习资源)
        - [TypeScript 入门教程](https://github.com/xcatliu/typescript-tutorial)
        - [进阶](#进阶)
        - [实战](#实战)
- [TypeScript Starter/Boilerplate](#typescript-starterboilerplate)
- [TypeScript 设计模式](#typescript-设计模式)
- [TypeScript 视频](#typescript-视频)
    - [中文视频](#中文视频)
    - [英文视频](#英文视频)
- [TypeScript 问答](#typescript-问答)
- [TypeScript 书籍](#typescript-书籍)
    - [中文书籍](#中文书籍)
    - [英文书籍](#英文书籍)
- [TypeScript 工具/库/框架](#typescript-工具库框架)
    - [构建工具](#构建工具)
        - [webpack](#webpack)
        - [gulp](#gulp)
        - [grunt](#grunt)
        - [compiler](#compiler)
        - [linter](#linter)
    - [Ioc](#ioc)
    - [文档生成](#文档生成)
    - [数据结构](#数据结构)
    - [数据库](#数据库)
    - [Server](#server)
- [TypeScript IDE](#typescript-ide)
    - [Offline](#offline)
        - [IDE/插件](#ide插件)
    - [Online](#online)
        - [Playground](#playground)
        - [Chrome 扩展](#chrome-扩展)
- [贡献](#贡献)
    - [指南](#指南)

---
## TypeScript 教程
### 为什么选择TypeScript

- [蚂蚁金服数据体验技术团队 - TypeScript体系调研报告](https://juejin.im/post/59c46bc86fb9a00a4636f939)
- [Vilicvane - TypeScript 2.0 新特性一览](https://zhuanlan.zhihu.com/p/21629069)
- [Vilicvane - TypeScript 2.1 新特性一览](https://zhuanlan.zhihu.com/p/24267683)
- [Vilicvane - TypeScript 2.2 新特性一览](https://zhuanlan.zhihu.com/p/25579011)
- [Vilicvane - TypeScript 2.3 新特性一览](https://zhuanlan.zhihu.com/p/27349475)
- [Microsoft - TypeScript 2.4 新特性一览](https://github.com/Microsoft/TypeScript/wiki/What's-new-in-TypeScript)
- [Vilicvane - TypeScript 2.5~2.6 新特性一览](https://zhuanlan.zhihu.com/p/30760290)
- [黄子毅 - 精读<<TypeScript2.0 - 2.9>>](https://zhuanlan.zhihu.com/p/37374083)
- [Linux中国 - 一篇缺失的 TypeScript 介绍](https://zhuanlan.zhihu.com/p/28494162)
- [单纯的土豆 - ES5, ES2015 和 TypeScript 的区别](http://www.jianshu.com/p/3c8c7713fa0e)
- [三七二十 - TypeScript 的好处都有啥？和 JavaScript 的区别在哪？](https://zhuanlan.zhihu.com/p/38526585)
- [Grain 先森 - 前端-TypeScript VS JavaScript 深度对比](https://www.jianshu.com/p/0dfbcd4a0757)
- [贺贺v5 - Angular2、Ionic、TypeScript、es6的关系？](http://www.jianshu.com/p/27c026734b8d)
- [极客学院 - 使用 TypeScript 提高开发能力](http://www.jianshu.com/p/066a6017db1b)
- [Hevin - 为什么 Reddit 选择了 TypeScript？](https://zhuanlan.zhihu.com/p/27695708)
- [JiaXinYi - Angular: 我们为什么选择 TypeScript](https://segmentfault.com/a/1190000010892897)
- [Djcordhose - 对比 Flow 和 TypeScript](http://djcordhose.github.io/flow-vs-typescript/flow-typescript-2.html#/)
- [Neal1991 - 采用 Flow 以及 TypeScript](https://github.com/neal1991/articles-translator/blob/master/%E9%87%87%E7%94%A8Flow%E4%BB%A5%E5%8F%8ATypeScript.md)
- [柳佳 - Flow vs. Typescript](https://zhuanlan.zhihu.com/p/27593029)
- [SDK.cn - Slack 的 TypeScript 之路](https://sdk.cn/news/6789)
- [RDDcoding - 熟悉全栈TypeScript](https://segmentfault.com/a/1190000014414303)
- [Lxxyx - TypeScript - 不止稳，而且快](http://www.lxxyx.win/2017/07/23/2017/ts-accerlate/)

### 学习资源
#### 进阶

- [Zhongsp - TypeScript Handbook (中文版)](https://zhongsp.gitbooks.io/typescript-handbook/content/)
- [Bjcl - TypeScript 教程](https://www.w3cschool.cn/typescript/)
- [Jason - 你所不知道的 Typescript 与 Redux 类型优化](https://zhuanlan.zhihu.com/p/32112508)
- [王亦斯 - 巧用 Typescript](https://zhuanlan.zhihu.com/p/39620591)
- [三毛 - 巧用 TypeScript （一）](https://jkchao.cn/article/5bb9c63963a5d23d5ce3091b)
- [三毛 - 巧用 TypeScript （二）](https://jkchao.cn/article/5bde8fdf94307c57d4c8d37a)
- [三毛 - 巧用 TypeScript （三）](https://jkchao.cn/article/5befe57994307c57d4c8d383)
- [三毛 - 巧用 TypeScript （四）](https://jkchao.cn/article/5c162137e35fb85c4c7e1278)
- [三毛 - 巧用 TypeScript （五）](https://jkchao.cn/article/5c8a4d99e53a054fad647c15)
- [Square - TypeScript 3.0 元组类型的用法和一些奇技淫巧](https://zhuanlan.zhihu.com/p/38687656)
- [Square - Typescript 类型高级技巧，和强约束 bind 的实现](https://zhuanlan.zhihu.com/p/38789971)
- [腾讯NEXT学位 - 深入 TypeScript 的类型系统](https://zhuanlan.zhihu.com/p/38081852)
- [newraina - 手把手教写 TypeScript Transformer Plugin](https://zhuanlan.zhihu.com/p/30360931)
- [EER - TypeScript 重构 Axios 经验分享](https://juejin.im/post/5bf7f1c0e51d455ed74f625c)
- [三毛 - 深入理解 TypeScript](https://jkchao.github.io/typescript-book-chinese/)

#### 实战

**Angular**

- [Yanxiaodi - Ionic 2 With TypeScript](https://www.gitbook.com/book/yanxiaodi/ionic2-guide/details)
- [Cacivy - Angular 2 + TypeScript 实现的 Cnode 社区](https://juejin.im/entry/5811c2cba22b9d00639f69f5)

**Vue**

- [薯条真的好好吃哦 - almost最好的Vue + Typescript系列01 环境搭建篇](https://segmentfault.com/a/1190000013676663)
- [toBeTheLight - Vue 2.5中将迎来有关TypeScript的改进！](https://segmentfault.com/a/1190000011474717)
- [盘风 - Vue2.5+ Typescript 引入全面指南](https://segmentfault.com/a/1190000011853167)
- [腾讯Bugly - vuejs+ts+webpack2框架的项目实践](https://mp.weixin.qq.com/s/p2Uc9IV284MXbRHhV2Vf-g)
- [LinkFly - 从 JavaScript 到 TypeScript 6 - Vue 引入 TypeScript](https://segmentfault.com/a/1190000011520912)
- [SimonZhanglTer - 可能是最全的Vue-TypeScript教程(附实例代码和一键构建工具)](https://segmentfault.com/a/1190000012486378)
- [三命 - vue + typescript 进阶篇](https://segmentfault.com/a/1190000011878086)
- [qiangdada - TypeScript + 大型项目实战](https://juejin.im/post/5b54886ce51d45198f5c75d7)
- [距离 - Vue全家桶+TypeScript使用总结](https://segmentfault.com/a/1190000013462418)
- [海蓝2018 - vue全家桶+Typescript开发一款习惯养成APP](https://segmentfault.com/a/1190000014884801)
- [Treri - 使用FIS3 和 TypeScript 实现 vue-hackernews-2.0](https://juejin.im/entry/58d8d603b123db199f4639a3)
- [🍼holyZhengs - 记录一次基于vue、typescript、pwa的项目由开发到部署](https://juejin.im/post/5ba3d205e51d450e8477af33)
- [大转转FE - 原有vue项目接入typescript](https://mp.weixin.qq.com/s?__biz=MzU0OTExNzYwNg==&mid=2247484478&idx=1&sn=a1222cc6d327fe80690b71e4398a27a2&chksm=fbb58ff7ccc206e12b5e2d57fb7cf84f8fe31dce3213e9b2c9ea00d5555873ddbb68ff2fde84&token=1712114111&lang=zh_CN&rd2werd=1#wechat_redirect)
- [MartinYin - 使用typescript+vue 编写电影信息小项目！](https://juejin.im/post/5bc2fd06e51d450e7903c783)
- [三毛 - 在 Vue 中使用 TypeScript 的一些思考（实践）](https://jkchao.cn/article/5b3d3bbef9d34142a117b184)

**React**

- [fi3ework - 基于 React + TypeScript 的网易云音乐](https://juejin.im/post/5b715796e51d4566334ca28c)
- [iKcamp - 翻译 | 开始使用 TypeScript 和 React](https://juejin.im/post/595cc34ff265da6c3d6c262b)
- [贾顺名 - TypeScript在react项目中的实践](https://segmentfault.com/a/1190000016163937)
- [花生毛豆 - TypeScript 在 React 中使用总结](https://juejin.im/post/5bab4d59f265da0aec22629b)
- [icepy - 复杂 React 应用中的TypeScript 3.0实践](https://zhuanlan.zhihu.com/p/42141179)
- [蚂蚁金服数据体验技术团队 - TypeScript 实践](https://juejin.im/post/5a9c004a6fb9a028b92c9e91)
- [蚂蚁金服数据体验技术团队 - TypeScript 2.8下的终极React组件模式](https://juejin.im/post/5b07caf16fb9a07aa83f2977)

**React Native**

- [胡桓铭 - React Native 与 TypeScript 在企业开发中的实践](https://zhuanlan.zhihu.com/p/27029898)

**Wechat**

- [Guyoung - 使用 TypeScript 开发微信小程序](https://segmentfault.com/a/1190000008175944)

**Node.js**

- [MarxJiao - 使用webpack搭建基于typescript的node开发环境](https://www.jianshu.com/p/6aab86403dc1)
- [天猪 - 当 Egg 遇到 TypeScript，收获茶叶蛋一枚](https://zhuanlan.zhihu.com/p/35334932)
- [奇舞团 - ThinkJS 3.0 如何实现对 TypeScript 的支持](https://75team.com/post/thinkjs-3.0-with-typescript.html)
- [贾顺名 - TypeScript在node项目中的实践](https://segmentfault.com/a/1190000015719697)
- [贾顺名 - 使用 TS + Sequelize 实现更简洁的 CRUD](https://mp.weixin.qq.com/s/agjjsO-47Qdd517wthadFg)
- [YDJFE - 一次TypeScript, React, Node, MongoDB的模板式前后端分离开发实践](https://juejin.im/post/5b89e47f51882542c062651f)

---
## TypeScript 设计模式

- [蚂蚁金服数据体验技术团队 - Typescript玩转设计模式 之 创建型模式](https://juejin.im/post/59fa88ac5188255a6a0d5f31)
- [蚂蚁金服数据体验技术团队 - Typescript玩转设计模式 之 结构型模式（上）](https://juejin.im/post/5a2d16325188252da0535d73)
- [蚂蚁金服数据体验技术团队 - Typescript玩转设计模式 之 结构型模式（下）](https://juejin.im/post/5a51da10f265da3e347b1483)
- [蚂蚁金服数据体验技术团队 - Typescript玩转设计模式 之 对象行为型模式（上）](https://juejin.im/post/5a6dd4dd51882573385ffa8e)
- [蚂蚁金服数据体验技术团队 -Typescript玩转设计模式 之 对象行为型模式（下）](https://juejin.im/post/5a77211b6fb9a0635774d61a)
- [杜帅 - 浅析Typescript设计模式](https://zhuanlan.zhihu.com/p/43283016)
- [torokmark - design_patterns_in_typescript](https://github.com/torokmark/design_patterns_in_typescript)
---
## TypeScript 书籍

### 中文书籍

- [Learning TypeScript (中文版)](https://item.jd.com/12001593.html)
- [迈向 Angular 2: 基于 TypeScript 的高性能 SPA 框架](https://item.jd.com/11948831.html)

### 英文书籍

- [TypeScript Essentials](https://www.amazon.cn/dp/B00OUJL6P0)
- [Mastering TypeScript](https://www.amazon.cn/dp/B00WMLHQFC)
- [Mastering TypeScript - Second Edition](https://www.amazon.cn/dp/B01DPR2EQC/)
- [Learning TypeScript](https://www.amazon.cn/dp/B0151N0G7W/)
- [Learning TypeScript 2.x](https://www.amazon.cn/dp/B078PQ6MF4/)
- [TypeScript 2.x By Example](https://www.amazon.cn/dp/B075V9K4CC/)
- [TypeScript 2.x for Angular Developers](https://www.amazon.cn/dp/B0753J1W3Z)
- [Angular 2 Development with TypeScript ](https://www.amazon.cn/dp/1617293121)
- [TypeScript: Modern JavaScript Development](https://www.amazon.cn/dp/B01MZ2PTHY/)
- [TypeScript Blueprints](https://www.amazon.cn/dp/B01CUI0JW8)
- [Pro TypeScript](https://www.amazon.cn/dp/1484232488)
- [TypeScript Design Patterns](https://www.amazon.cn/dp/B01BSTEDI6/)
- [TypeScript High Performance](https://www.amazon.cn/dp/B071VVFD4D/)
- [TypeScript Microservices](https://www.amazon.cn/dp/B078N3XCVG/)


---
## TypeScript 工具/库/框架

### 构建工具

#### webpack

- [s-panferov - awesome-typescript-loader](https://github.com/s-panferov/awesome-typescript-loader)
- [TypeStrong - ts-loader](https://github.com/TypeStrong/ts-loader)

#### gulp

- [ivogabe - gulp-typescript](https://github.com/ivogabe/gulp-typescript)

#### grunt

- [TypeStrong - grunt-ts](https://github.com/TypeStrong/grunt-ts)

#### compiler

- [TypeStrong - ts-node](https://github.com/TypeStrong/ts-node)
- [AssemblyScript - assemblyscript](https://github.com/AssemblyScript/assemblyscript)
- [bcherny - json-schema-to-typescript](https://github.com/bcherny/json-schema-to-typescript)
- [YousefED - typescript-json-schema](https://github.com/YousefED/typescript-json-schema)

#### linter

- [palantir - tslint](https://github.com/palantir/tslint)

### Ioc

* [Inversify - InversifyJS](https://github.com/inversify/InversifyJS)
* [Inversify - inversify-express-example](https://github.com/inversify/inversify-express-example)

### 文档生成

- [TypeStrong - typedoc](https://github.com/TypeStrong/typedoc)

### 数据结构

- [dcodeIO - protobuf.js](https://github.com/dcodeIO/protobuf.js)
- [basarat - typescript-collections](https://github.com/basarat/typescript-collections)

### 数据库

- [Typeorm - typeorm](https://github.com/typeorm/typeorm)
- [RobinBuschmann - sequelize-typescript](https://github.com/RobinBuschmann/sequelize-typescript)

### Server

* [Alibaba - egg.js](https://eggjs.org/)
* [welefen - thinkjs](https://github.com/thinkjs/thinkjs)
* [kamilmysliwiec - nest](https://github.com/nestjs/nest)

---
## TypeScript IDE

### Offline

#### IDE/插件

- [Visual Studio Community](https://visualstudio.microsoft.com/zh-hans/vs/community/)
- [Visual Studio Code](https://www.visualstudio.com/en-us/products/code-vs.aspx)
- [WebStorm](https://www.jetbrains.com/webstorm/)
- [PhpStorm](https://www.jetbrains.com/phpstorm/download/)
- [TypeScript Sublime Plugin](https://github.com/Microsoft/TypeScript-Sublime-Plugin)
- [Atom TypeScript](https://github.com/TypeStrong/atom-typescript)
- [TypeScript Interactive Development Environment for Emacs](https://github.com/ananthakumaran/tide)
- [TypeScript IDE for Eclipse](http://typecsdev.com/)
- [TypeScript Syntax for VIM](https://github.com/leafgarland/typescript-vim)

### Online

#### Playground

- [TypeScript official Playground](http://www.typescriptlang.org/Playground/)
- [Stackblitz](https://stackblitz.com/)
- [JS Bin](http://jsbin.com/?js)
- [Codepen](http://codepen.io/)
- [TypeScript Editor](http://drake7707.github.io/Typescript-Editor/)
- [TypeScript Interpret - Terminal Emulator](http://niutech.github.io/typescript-interpret/)
- [TypeScript Play](https://agentcooper.github.io/typescript-play/)

#### Chrome 扩展

- [OctoLinker](https://github.com/OctoLinker/browser-extension)