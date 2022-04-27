---
home: true
title: 首页
heroImage: https://shawnzhou-image.oss-cn-beijing.aliyuncs.com/blog/vine-js-web.png
heroText: Vine.js
tagline: 一个灵活、易用的静态网站搭建框架
actions: 
- text: → 快速上手
  link: zh/guide
  type: primary
- text: 项目简介
  link: zh/about
  type: secondary
features:
- title: 全新设计
  details: 页面由主核心 + 扩展件组合生成，通过更细致地拆分页面组件职责，做到更低成本的功能扩展。
- title: 基于Vite
  details: 享受 Vue 3 + Rollup 的高性能开发体验，可短时间内迅速渲染大量页面，同时允许用户使用 Vue 深度定制主题。
- title: 注重体验
  details: Vine 配备了丰富的命令行提示，拥有独立的图形化操作面板，力争降低用户的使用门槛。
- title: 丰富扩展
  details: Vine 拥有一个逐渐丰富的插件社区，你可以在主核心兼容范围内自由选取插件。
- title: 快速部署
  details: 仅需一条指令，Vine 即可将网站发布至 GitHub Pages，云服务器或其他平台。
- title: 多样主题
  details: 以扩展件的形式将样式抽离，更换主题只需添加对应扩展，不需要更改模板。
footer: MIT Licensed | Copyright © 2022 Shawn Zhou
---

### 开始使用

```sh
# 全局安装 Vine.js CLI
npm install vinejs-cli

# 新建一个 Vine 项目，选择一个主核心
vine create mywebsite

# 开启本地调试，Vine 将自动构建静态网站并启动调试服务器
vine debug 

# 启动图形化操作面板，自由配置你的网站！
vine guider
```

**本站点还在建设中**