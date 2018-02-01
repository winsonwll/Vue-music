# Vue音乐播放器

## 技术栈

### 【前端】

> Vue：用于构建用户界面的 MVVM 框架。它的核心是响应的数据绑定和组系统件

> vue-router：为单页面应用提供的路由系统，项目上线前使用了 Lazy Loading Routes 技术来实现异步加载优化性能

> vuex：Vue 集中状态管理，在多个组件共享某些状态时非常便捷

> vue-lazyload：第三方图片懒加载库，优化页面加载速度

> better-scroll：iscroll 的优化版，使移动端滑动体验更加流畅

> Sass(Scss)：css 预编译处理器

> ES6：ECMAScript 新一代语法，模块化、解构赋值、Promise、Class 等方法非常好用


### 【后端】

> Node.js：利用 Express 起一个本地测试服务器

> jsonp：服务端通讯。抓取 QQ音乐(移动端)数据

> axios：服务端通讯。结合 Node.js 代理后端请求，抓取 QQ音乐(PC端)数据

### 【自动化构建及其他工具】

> vue-cli：Vue 脚手架工具，快速初始化项目代码

> eslint：代码风格检查工具，规范代码书写

> vConsole：移动端调试工具，在移动端输出日志


## Build Setup

### 下载或克隆下来，然后安装依赖

> npm install

### 开发预览

> npm run dev

### 打包发布，生成的文件在dist文件夹中

> npm run build
