- node.js的安装(省略)
- cnpm 淘宝镜像的安装

```
npm install -g cnpm --registry=https://registry.npm.taobao.org
```
- 以后npm换成cnpm
- 同步模块,通过sync命令马上同步一个模块,只有`cnpm`命令行才有这个功能

```
cnpm sync connect
```

> online-store

- 在online-store文件夹中 `shift+鼠标右键` 在此打开命令窗口
- `npm install` 安装node_modules
- `npm run dev` 运行项目

> 前后端分离优缺点

- pc, app, pad多端适应
- SPA开发模式开始流行
- 前后端开发职责不清
- 开发效率问题, 前后端互相等待
- 前端一直配合着后端, 能力受限
- 后台开发语言和模板高度耦合, 导致开发语言依赖严重

> 缺点

- 前后端学习门槛增加
- 数据依赖导致文档重要性增加
- 前端工作量加大
- SEO的难度加大(单独做ssr)
- 后端开发模式迁移增加成本

**restful Api**

- restful api(标准, 规范)目前是前后端分离最佳实践
- 轻量,直接通过http(https),不需要额外协议 post/get/put/delete等操作
- 面向资源, 一目了然, 具有自解释性