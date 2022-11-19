### 微前端框架 mini-qiankun-framework

`mini-qiankun-framework` 是通过仿写qiankun来原生实现的一个轻量级微前端框架——使用方便、可扩展性强，目前已实现应用注册、应用加载、沙箱隔离、样式隔离、全局状态管理、资源预加载等基本功能。

## ✨ 特点

📦 通过仿写qiankun框架原生实现，且提供了开箱即用的 API。

📱 技术栈无关，任意技术栈的应用均可 使用/接入，不论是 React/Vue/Angular/JQuery 还是其他等框架。

💪 HTML Entry 接入方式，让你接入微应用像使用 iframe 一样简单。

🛡​ 样式隔离，确保微应用之间样式互相不干扰。

🧳 JS 沙箱，确保微应用之间 全局变量/事件 不冲突。

⚡️ 资源预加载，在浏览器空闲时间预加载未打开的微应用资源，加速微应用打开速度。

🔌 可扩展性强，支持直接修改源码来自定义属于你的微前端框架

## 快速上手

推荐使用 npm 或 yarn 的方式进行安装，不仅可以在开发环境轻松调试，也可以放心地在生产环境打包部署使用。

```bash
npm install mini-qiankun-framework --save
```

```bash
yarn mini-qiankun-framework --save
```

