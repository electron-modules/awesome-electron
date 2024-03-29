[English](./README-en.md) | 简体中文

## 目录

- [目录](#目录)
- [官方资源](#官方资源)
- [资源](#资源)
  - [工具](#工具)
- [样板](#样板)
- [框架](#框架)
- [库](#库)
  - [进程间通信(IPC)](#进程间通信ipc)
  - [检测/判断](#检测判断)
  - [位置/尺寸](#位置尺寸)
  - [窗口相关](#窗口相关)
  - [界面相关](#界面相关)
  - [持久化](#持久化)
  - [数据库](#数据库)
  - [打包程序/安装程序](#打包程序安装程序)
  - [源码混淆/保护](#源码混淆保护)
  - [自动更新/发布服务器](#自动更新发布服务器)
  - [日志](#日志)
  - [调试](#调试)
  - [开发工具](#开发工具)
  - [测试](#测试)
  - [未分类](#未分类)
- [应用](#应用)
  - [IDE](#ide)
  - [Markdown](#markdown)
  - [记事本](#记事本)
  - [浏览器](#浏览器)
  - [Git](#git)
  - [数据库客户端](#数据库客户端)
  - [命令终端](#命令终端)
  - [图像](#图像)
  - [视频/音频](#视频音频)
  - [屏幕录制/共享](#屏幕录制共享)
  - [密码](#密码)
  - [Messenger](#messenger)
  - [Email](#email)
  - [Docker](#docker)
  - [硬件统计信息](#硬件统计信息)
  - [HTTP](#http)
  - [下载](#下载)
  - [效率](#效率)
  - [应用启动器](#应用启动器)
  - [一些非官方的应用](#一些非官方的应用)
- [相关链接](#相关链接)

## 官方资源

- [官网](https://www.electronjs.org)
- [文档](https://www.electronjs.org/zh/docs/latest/)
- [仓库](https://github.com/electron/electron) ![](https://img.shields.io/github/stars/electron/electron.svg?style=social&label=Star)
- [应用](https://www.electronjs.org/apps) - 使用 Electron 开发的应用集合。

## 资源

### 工具

- [Electron Fiddle](https://www.electronjs.org/fiddle) - 最简单的 Electron 入门方式。

## 样板

- [electron-react-boilerplate](https://github.com/chentsulin/electron-react-boilerplate) - 基于 React 和 Webpack 的样板。 ![](https://img.shields.io/github/stars/chentsulin/electron-react-boilerplate.svg?style=social&label=Star)
- [electron-vue](https://github.com/SimulatedGREG/electron-vue) - 一个 Electron 和 Vue.js 快速入门样板，带有 vue-cli 脚手架、常见的 Vue 插件、electron-packager/electron-builder、unit/e2e 测试、vue-devtools 和 webpack。 ![](https://img.shields.io/github/stars/SimulatedGREG/electron-vue.svg?style=social&label=Star)
- [electron-quick-start](https://github.com/electron/electron-quick-start) - 官方提供的快速开始。 ![](https://img.shields.io/github/stars/electron/electron-quick-start.svg?style=social&label=Star)
- [angular-electron](https://github.com/maximegris/angular-electron) - 使用 Angular、Electron、TypeScript、SASS 和 Hot Reload 快速开始。 ![](https://img.shields.io/github/stars/maximegris/angular-electron.svg?style=social&label=Star)
- [electron-boilerplate](https://github.com/szwacz/electron-boilerplate) - 甚至生成安装程序的综合样板。 ![](https://img.shields.io/github/stars/szwacz/electron-boilerplate.svg?style=social&label=Star)
- [electron-typescript-react](https://github.com/diego3g/electron-typescript-react) - 一个 Electron 样板，包括 TypeScript、React、Jest 和 ESLint。 ![](https://img.shields.io/github/stars/diego3g/electron-typescript-react.svg?style=social&label=Star)
- [secure-electron-template](https://github.com/reZach/secure-electron-template) - 以安全为中心的样板，用于使用 React、Redux、Webpack 和 i18next 创建应用程序。 ![](https://img.shields.io/github/stars/reZach/secure-electron-template.svg?style=social&label=Star)
- [bozon](https://github.com/railsware/bozon) - 搭建、运行、测试和打包您的应用程序。 ![](https://img.shields.io/github/stars/railsware/bozon.svg?style=social&label=Star)
- [generator-electron](https://github.com/sindresorhus/generator-electron) - 搭建一个应用样板。 ![](https://img.shields.io/github/stars/sindresorhus/generator-electron.svg?style=social&label=Star)
- [electron-boilerplate](https://github.com/sindresorhus/electron-boilerplate) - 启动创建应用程序的样板。 ![](https://img.shields.io/github/stars/sindresorhus/electron-better-ipc.svg?style=social&label=Star)
- [vite-electron-builder](https://github.com/cawa-93/vite-electron-builder) - 基于 Vite 的 Electron 应用程序的安全样板。 TypeScript + Vue/React/Angular/Svelte/原生JS。 ![](https://img.shields.io/github/stars/cawa-93/vite-electron-builder.svg?style=social&label=Star)
- [electron-egg](https://github.com/wallace5303/electron-egg) - 一个入门简单、快速高效、功能丰富的JS跨平台桌面软件开发框架。 ![](https://img.shields.io/github/stars/wallace5303/electron-egg.svg?style=social&label=Star)
- [electron-vite-template](https://github.com/umbrella22/electron-vite-template) - Vue3 + Vite + electron 的项目模板。 ![](https://img.shields.io/github/stars/umbrella22/electron-vite-template.svg?style=social&label=Star)

## 框架

- [electron-egg](https://github.com/dromara/electron-egg) - 一个简单的跨平台企业桌面软件开发框架。 ![](https://img.shields.io/github/stars/dromara/electron-egg.svg?style=social&label=Star)

## 库

### 进程间通信(IPC)

- [electron-better-ipc](https://github.com/sindresorhus/electron-better-ipc) - 简化 IPC 通信 ![](https://img.shields.io/github/stars/sindresorhus/electron-better-ipc.svg?style=social&label=Star)
- [ipc-stream](https://github.com/jprichardson/electron-ipc-stream) - IPC 的双工流。 ![](https://img.shields.io/github/stars/jprichardson/electron-ipc-stream.svg?style=social&label=Star)
- [electron-router](https://github.com/m0n0l0c0/electron-router) - 通过路由的方式整理IPC消息传递。 ![](https://img.shields.io/github/stars/m0n0l0c0/electron-router.svg?style=social&label=Star)
- [electron-ipc-proxy](https://github.com/frankwallis/electron-ipc-proxy) - 基于IPC进行渲染进程和主进程之间透明异步远程通信。 ![](https://img.shields.io/github/stars/frankwallis/electron-ipc-proxy.svg?style=social&label=Star)

### 检测/判断

- [electron-is-dev](https://github.com/sindresorhus/electron-is-dev) - 检查Electron是否允许在开发环境 ![](https://img.shields.io/github/stars/sindresorhus/electron-is-dev.svg?style=social&label=Star)
- [electron-is](https://github.com/delvedor/electron-is) - Electron 的“is”工具，它提供了一组方便的函数。 ![](https://img.shields.io/github/stars/delvedor/electron-is.svg?style=social&label=Star)
- [is-electron](https://github.com/cheton/is-electron) - 判断是否运行在 Electron中. ![](https://img.shields.io/github/stars/cheton/is-electron.svg?style=social&label=Star)
- [is-electron-renderer](https://github.com/jprichardson/is-electron-renderer) - 检查你的代码是否运行在 `主进程` 或 `渲染进程`. ![](https://img.shields.io/github/stars/jprichardson/is-electron-renderer.svg?style=social&label=Star)
- [electron-is-accelerator](https://github.com/brrd/electron-is-accelerator) - 检查字符串是否是有效的 Electron 快捷键。![](https://img.shields.io/github/stars/brrd/electron-is-accelerator.svg?style=social&label=Star)

### 位置/尺寸

- [electron-positioner](https://github.com/jenslind/electron-positioner) - 将窗口放置在常见位置。 ![](https://img.shields.io/github/stars/jenslind/electron-positioner.svg?style=social&label=Star)
- [electron-drag](https://github.com/kapetan/electron-drag) - 提升窗口拖拽体验。 ![](https://img.shields.io/github/stars/kapetan/electron-drag.svg?style=social&label=Star)
- [electron-window-state](https://github.com/mawie81/electron-window-state) - 存储窗口尺寸和位置。 ![](https://img.shields.io/github/stars/mawie81/electron-window-state.svg?style=social&label=Star)

### 窗口相关

- [electron-window](https://github.com/jprichardson/electron-window) - Electron 窗口管理的便捷方法。 ![](https://img.shields.io/github/stars/jprichardson/electron-window.svg?style=social&label=Star)
- [electron-windows](https://github.com/electron-modules/electron-windows) - 优雅地管理多窗口并提供强大的功能。 ![](https://img.shields.io/github/stars/electron-modules/electron-windows.svg?style=social&label=Star)

### 界面相关

- [menubar](https://github.com/maxogden/menubar) - 菜单栏应用程序框架。 ![](https://img.shields.io/github/stars/maxogden/menubar.svg?style=social&label=Star)
- [electron-context-menu](https://github.com/sindresorhus/electron-context-menu) - 可扩展的右键菜单。 ![](https://img.shields.io/github/stars/sindresorhus/electron-context-menu.svg?style=social&label=Star)
- [electron-vibrancy](https://github.com/arkenthera/electron-vibrancy) - 为窗户添加活力（模糊功能）。 ![](https://img.shields.io/github/stars/arkenthera/electron-vibrancy.svg?style=social&label=Star)
- [electron-input-menu](https://github.com/parro-it/electron-input-menu) - 输入框的下拉菜单. ![](https://img.shields.io/github/stars/parro-it/electron-input-menu.svg?style=social&label=Star)
- [electron-create-menu](https://github.com/kilian/electron-create-menu) - 跨全平台的默认菜单，易于扩展，并支持 i18n。 ![](https://img.shields.io/github/stars/kilian/electron-create-menu.svg?style=social&label=Star)

### 持久化

- [electron-store](https://github.com/sindresorhus/electron-store) - 保存和加载用户偏好、应用状态、缓存等数据。 ![](https://img.shields.io/github/stars/sindresorhus/electron-store.svg?style=social&label=Star)
- [electron-json-storage](https://github.com/jviotti/electron-json-storage) - 读写用户设置。 ![](https://img.shields.io/github/stars/jviotti/electron-json-storage.svg?style=social&label=Star)
- [electron-settings](https://github.com/nathanbuchar/electron-settings) - 读写用户设置到硬盘。 ![](https://img.shields.io/github/stars/nathanbuchar/electron-settings.svg?style=social&label=Star)

### 数据库

- [RxDB](https://github.com/pubkey/rxdb) - 实时 NoSQL 数据库。 ![](https://img.shields.io/github/stars/pubkey/rxdb.svg?style=social&label=Star)
- [NeDB](https://github.com/louischatriot/nedb) - 嵌入式持久化或内存数据库。 ![](https://img.shields.io/github/stars/louischatriot/nedb.svg?style=social&label=Star)
- [realm-js](https://github.com/realm/realm-js) - Realm 是一个移动数据库：SQLite 和 KV 存储的替代品。 ![](https://img.shields.io/github/stars/realm/realm-js.svg?style=social&label=Star)
- [better-sqlite3](https://github.com/WiseLibs/better-sqlite3) - Node.js 中最快和最简单的 SQLite3 库。 ![](https://img.shields.io/github/stars/WiseLibs/better-sqlite3.svg?style=social&label=Star)
- [trilogy](https://github.com/citycide/trilogy) - TypeScript SQLite 数据库层，支持原生 C++ 和纯 JavaScript 后端。 ![](https://img.shields.io/github/stars/citycide/trilogy.svg?style=social&label=Star)

### 打包程序/安装程序

- [electron-builder](https://github.com/electron-userland/electron-builder) - 创建安装程序。 ![](https://img.shields.io/github/stars/electron-userland/electron-builder.svg?style=social&label=Star)
- [electron-packager](https://github.com/electron-userland/electron-packager) - 打包应用。 ![](https://img.shields.io/github/stars/electron-userland/electron-packager.svg?style=social&label=Star)
- [ember-electron](https://github.com/felixrieseberg/ember-electron) - 构建、测试和打包 Ember 应用。 ![](https://img.shields.io/github/stars/felixrieseberg/ember-electron.svg?style=social&label=Star)
- [electron-installer-windows](https://github.com/unindented/electron-installer-windows) - 构建 Windows 包。 ![](https://img.shields.io/github/stars/unindented/electron-installer-windows.svg?style=social&label=Star)
- [electron-installer-debian](https://github.com/unindented/electron-installer-debian) - 构建 Debian 包。 ![](https://img.shields.io/github/stars/unindented/electron-installer-debian.svg?style=social&label=Star)
- [electrify](https://github.com/arboleya/electrify) - 打包 Meteor 应用。 ![](https://img.shields.io/github/stars/arboleya/electrify.svg?style=social&label=Star)
- [electron-installer-redhat](https://github.com/unindented/electron-installer-redhat) - 构建 Red Hat 包。 ![](https://img.shields.io/github/stars/unindented/electron-installer-redhat.svg?style=social&label=Star)

### 源码混淆/保护

- [javascript-obfuscator](https://github.com/javascript-obfuscator/javascript-obfuscator) - 一个强大的 JavaScript 和 Node.js 混淆器。 ![](https://img.shields.io/github/stars/javascript-obfuscator/javascript-obfuscator.svg?style=social&label=Star)
- [bytenode](https://github.com/bytenode/bytenode) - 用于 Node.js 的极简字节码编译器。它真正将你的 JavaScript 代码编译成 V8 字节码，这样你就可以保护你的源代码。 ![](https://img.shields.io/github/stars/bytenode/bytenode.svg?style=social&label=Star)

### 自动更新/发布服务器

- [electron-release-server](https://github.com/ArekSredzki/electron-release-server) - 具有前端和自动更新程序支持的自托管发布服务器。 ![](https://img.shields.io/github/stars/ArekSredzki/electron-release-server.svg?style=social&label=Star)
- [nuts](https://github.com/GitbookIO/nuts) - 依赖 GitHub 的自动更新发布/下载服务器。 ![](https://img.shields.io/github/stars/GitbookIO/nuts.svg?style=social&label=Star)
- [electron-dl](https://github.com/sindresorhus/electron-dl) - 简化文件下载。 ![](https://img.shields.io/github/stars/sindresorhus/electron-dl.svg?style=social&label=Star)
- [electron-download](https://github.com/electron-userland/electron-download) - 从 GitHub 下载 Electron 发布 zip。 ![](https://img.shields.io/github/stars/electron-userland/electron-download.svg?style=social&label=Star)
- [electron-gh-release](https://github.com/jenslind/electron-gh-releases) - 通过在 GitHub 上发布来自动更新。 ![](https://img.shields.io/github/stars/jenslind/electron-gh-releases.svg?style=social&label=Star)

### 日志

- [electron-log](https://github.com/megahertz/electron-log) - 简单日志记录程序。 ![](https://img.shields.io/github/stars/megahertz/electron-log.svg?style=social&label=Star)
- [electron-timber](https://github.com/sindresorhus/electron-timber) - 漂亮的日志记录程序。 ![](https://img.shields.io/github/stars/sindresorhus/electron-timber.svg?style=social&label=Star)

### 调试

- [electron-debug](https://github.com/sindresorhus/electron-debug) - 添加有用的 debug 功能。 ![](https://img.shields.io/github/stars/sindresorhus/electron-debug.svg?style=social&label=Star)
- [debugtron](https://github.com/pd4d10/debugtron) - 调试基于 Electron 的生产 App 。 ![](https://img.shields.io/github/stars/pd4d10/debugtron.svg?style=social&label=Star)
- [debug-menu](https://github.com/parro-it/debug-menu) - 类似 Chrome 右键菜单 "inspect element"。 ![](https://img.shields.io/github/stars/parro-it/debug-menu.svg?style=social&label=Star)

### 开发工具

- [devtron](https://github.com/electron/devtron) - 官方开发工具插件。 ![](https://img.shields.io/github/stars/electron/devtron.svg?style=social&label=Star)
- [electron-devtools-installer](https://github.com/GPMDP/electron-devtools-installer) - 从 Chrome 应用商城里安装 DevTools。 ![](https://img.shields.io/github/stars/GPMDP/electron-devtools-installer.svg?style=social&label=Star)
- [electron-reloader](https://github.com/sindresorhus/electron-reloader) - 在开发过程中，自动重新加载。 ![](https://img.shields.io/github/stars/sindresorhus/electron-reloader.svg?style=social&label=Star)
- [elemon](https://github.com/manidlou/elemon) - 开发过程中热更新。 ![](https://img.shields.io/github/stars/manidlou/elemon.svg?style=social&label=Star)
- [electronmon](https://github.com/catdad/electronmon) - 运行，监控并重启应用。 ![](https://img.shields.io/github/stars/catdad/electronmon.svg?style=social&label=Star)

### 测试

- [spectron](https://github.com/electron-userland/spectron) - 使用 ChromeDriver 测试 Electron 应用。 ![](https://img.shields.io/github/stars/electron-userland/spectron.svg?style=social&label=Star)
- [electron-mocha](https://github.com/jprichardson/electron-mocha) - 在 Electron 中运行 Mocha 测试用例。 ![](https://img.shields.io/github/stars/jprichardson/electron-mocha.svg?style=social&label=Star)
- [jest-electron](https://github.com/hustcc/jest-electron) - 运行和调试 Jest 单元测试到浏览器环境中。 ![](https://img.shields.io/github/stars/hustcc/jest-electron.svg?style=social&label=Star)

### 未分类

- [electron-util](https://github.com/sindresorhus/electron-util) - 用于开发应用和模块的有用工具。 ![](https://img.shields.io/github/stars/sindresorhus/electron-util.svg?style=social&label=Star)
- [electron-compile](https://github.com/electron/electron-compile) - 在您的应用程序中使用 ES2015、CoffeeScript、Less、Stylus，无需预编译。![](https://img.shields.io/github/stars/electron/electron-compile.svg?style=social&label=Star)
- [electron-rebuild](https://github.com/electron/electron-rebuild) - 重新构建当前安装的 Electron 版本的原生 Node.js 模块。 ![](https://img.shields.io/github/stars/electron/electron-rebuild.svg?style=social&label=Star)
- [auto-launch](https://github.com/Teamwork/node-auto-launch) - 在系统启动时启动应用程序。 ![](https://img.shields.io/github/stars/Teamwork/node-auto-launch.svg?style=social&label=Star)
- [electron-redux](https://github.com/hardchor/electron-redux) - 跨窗口同步 Redux 状态。 ![](https://img.shields.io/github/stars/hardchor/electron-redux.svg?style=social&label=Star)
- [electronegativity](https://github.com/doyensec/electronegativity) - 识别错误配置和安全反模式。 ![](https://img.shields.io/github/stars/doyensec/electronegativity.svg?style=social&label=Star)
- [ngx-electron](https://github.com/ThorstenHans/ngx-electron/) - 集成 Electron API 和 Angular。 ![](https://img.shields.io/github/stars/ThorstenHans/ngx-electron.svg?style=social&label=Star)
- [electron-osx-sign](https://github.com/electron-userland/electron-osx-sign) - macOS 应用程序的代码签名。 ![](https://img.shields.io/github/stars/electron-userland/electron-osx-sign.svg?style=social&label=Star)
- [adblocker-electron](https://github.com/cliqz-oss/adblocker/tree/master/packages/adblocker-electron) - 阻止广告。 ![](https://img.shields.io/github/stars/cliqz-oss/adblocker.svg?style=social&label=Star)
- [electron-localshortcut](https://github.com/parro-it/electron-localshortcut) - 在本地为窗口添加快捷键。 ![](https://img.shields.io/github/stars/parro-it/electron-localshortcut.svg?style=social&label=Star)
- [electron-about-window](https://github.com/rhysd/electron-about-window) - “关于此应用程序”窗口。 ![](https://img.shields.io/github/stars/rhysd/electron-about-window.svg?style=social&label=Star)
- [electron-unhandled](https://github.com/sindresorhus/electron-unhandled) - 捕获未处理的错误和 Promise 的 rejections。 ![](https://img.shields.io/github/stars/sindresorhus/electron-unhandled.svg?style=social&label=Star)
- [electron-sudo](https://github.com/automation-stack/electron-sudo) - 使子进程具备管理权限。 ![](https://img.shields.io/github/stars/automation-stack/electron-sudo.svg?style=social&label=Star)
- [electron-serve](https://github.com/sindresorhus/electron-serve) - 静态文件服务（对于路由很有用，类似 `react-router`）. ![](https://img.shields.io/github/stars/sindresorhus/electron-serve.svg?style=social&label=Star)
- [fix-path](https://github.com/sindresorhus/fix-path) - 从 GUI 应用程序运行时修复 macOS 上的 $PATH。在创建子进程时很有用。 ![](https://img.shields.io/github/stars/sindresorhus/fix-path.svg?style=social&label=Star)
- [electron-pdf-window](https://github.com/gerhardberger/electron-pdf-window) - 在浏览器窗口(BrowserWindow)中查看 PDF 文件。 ![](https://img.shields.io/github/stars/gerhardberger/electron-pdf-window.svg?style=social&label=Star)
- [run-electron](https://github.com/sindresorhus/run-electron) - 在没有任何垃圾输出到终端的情况下运行 Electron。 ![](https://img.shields.io/github/stars/sindresorhus/run-electron.svg?style=social&label=Star)
- [electron-process-manager](https://github.com/getstation/electron-process-manager) - 进程管理器 UI（就像 Chrome 的任务管理器）。 ![](https://img.shields.io/github/stars/getstation/electron-process-manager.svg?style=social&label=Star)
- [electron-osx-appearance](https://github.com/danhp/electron-osx-appearance) - macOS 外观设置的简化 API。 ![](https://img.shields.io/github/stars/danhp/electron-osx-appearance.svg?style=social&label=Star)
- [electron-chrome-extension](https://github.com/getstation/electron-chrome-extension) - 添加对 Chrome 扩展程序的支持。 ![](https://img.shields.io/github/stars/getstation/electron-chrome-extension.svg?style=social&label=Star)
- [electron-detach](https://github.com/parro-it/electron-detach) - 重新启动一个 Electron 应用程序作为一个独立的进程。![](https://img.shields.io/github/stars/parro-it/electron-detach.svg?style=social&label=Star)
- [babel-preset-electron](https://github.com/emorikawa/babel-preset-electron) - Babel 预设只编译特定 Electron 版本所需的内容。 ![](https://img.shields.io/github/stars/emorikawa/babel-preset-electron.svg?style=social&label=Star)
- [electron-ssl-pinning](https://github.com/dialogs/electron-ssl-pinning) - 防止中间人（MITM）。 ![](https://img.shields.io/github/stars/dialogs/electron-ssl-pinning.svg?style=social&label=Star)
- [electron-require](https://github.com/brrd/electron-require) - 简化  require。 ![](https://img.shields.io/github/stars/brrd/electron-require.svg?style=social&label=Star)
- [chromium-net-errors](https://github.com/maxkueng/chromium-net-errors) - 将Chromium 的网络错误作为自定义错误类。 ![](https://img.shields.io/github/stars/maxkueng/chromium-net-errors.svg?style=social&label=Star)

## 应用

### IDE

- [Visual Studio Code](https://github.com/Microsoft/vscode) - 跨平台的 IDE 。 ![](https://img.shields.io/github/stars/Microsoft/vscode.svg?style=social&label=Star)
- [Atom](https://github.com/atom/atom) - 代码编辑器。 ![](https://img.shields.io/github/stars/atom/atom.svg?style=social&label=Star)
- [Light Table](https://github.com/LightTable/LightTable) - 即时反馈的代码编辑器。 ![](https://img.shields.io/github/stars/LightTable/LightTable.svg?style=social&label=Star)
- [Graviton Editor](https://github.com/Graviton-Code-Editor/Graviton-App) - 跨平台的代码编辑器。 ![](https://img.shields.io/github/stars/Graviton-Code-Editor/Graviton-App.svg?style=social&label=Star)

### Markdown

- [Mark Text](https://github.com/marktext/marktext) - 实时预览的 Markdown 编辑器。 ![](https://img.shields.io/github/stars/marktext/marktext.svg?style=social&label=Star)
- [Notable](https://github.com/fabiospampinato/notable) - 基于 Markdown 的笔记。 ![](https://img.shields.io/github/stars/fabiospampinato/notable.svg?style=social&label=Star)
- [Boostnote](https://github.com/BoostIO/BoostNote-App) - 面向开发人员的 Markdown 注释和代码片段应用程序。 老版本: ![](https://img.shields.io/github/stars/BoostIO/Boostnote.svg?style=social&label=Star) 最新版本: ![](https://img.shields.io/github/stars/BoostIO/BoostNote-App.svg?style=social&label=Star)
- [Abricotine](https://github.com/brrd/Abricotine) - 带内部预览的 Markdown 编辑器。 ![](https://img.shields.io/github/stars/brrd/Abricotine.svg?style=social&label=Star)
- [Vmd](https://github.com/yoshuawuyts/vmd) - 预览 Markdown 文件。 ![](https://img.shields.io/github/stars/yoshuawuyts/vmd.svg?style=social&label=Star)
- [MarkRight](https://github.com/dvcrn/markright) - GitHub 风格的带有实时预览的 Markdown 编辑器。 ![](https://img.shields.io/github/stars/dvcrn/markright.svg?style=social&label=Star)
- [electron-markdownify](https://github.com/amitmerchant1990/electron-markdownify) - 小巧的 Markdown 编辑器。 ![](https://img.shields.io/github/stars/amitmerchant1990/electron-markdownify.svg?style=social&label=Star)
- [Shiba](https://github.com/rhysd/Shiba) - 带有 linting 的实时 Markdown 预览。 ![](https://img.shields.io/github/stars/rhysd/Shiba.svg?style=social&label=Star)
- [Marky](https://github.com/vesparny/marky) - Markdown 编辑器。 ![](https://img.shields.io/github/stars/vesparny/marky.svg?style=social&label=Star)
- [Proton](https://github.com/steventhanna/proton) - 可实时预览的 Markdown 编辑器。 ![](https://img.shields.io/github/stars/steventhanna/proton.svg?style=social&label=Star)
- [Markn](https://github.com/minodisk/markn) - 轻量的 Markdown 预览器。 ![](https://img.shields.io/github/stars/minodisk/markn.svg?style=social&label=Star)

### 记事本

- [Notable](https://github.com/fabiospampinato/notable) - 基于 Markdown 的笔记。 ![](https://img.shields.io/github/stars/fabiospampinato/notable.svg?style=social&label=Star)
- [Simplenote](https://github.com/Automattic/simplenote-electron) - 记事员。 ![](https://img.shields.io/github/stars/Automattic/simplenote-electron.svg?style=social&label=Star)
- [Tusk](https://github.com/champloohq/tusk) - 非官方 Evernote 应用. ![](https://img.shields.io/github/stars/champloohq/tusk.svg?style=social&label=Star)
- [Leanote](https://github.com/leanote/desktop-app) - 云笔记。 ![](https://img.shields.io/github/stars/leanote/desktop-app.svg?style=social&label=Star)
- [Noty](https://github.com/fabiospampinato/noty) - 自动保存便笺，支持单个窗口中的多个便笺。 ![](https://img.shields.io/github/stars/fabiospampinato/noty.svg?style=social&label=Star)
- [Yana](https://github.com/lukasbach/yana) - 带有富文本笔记、内嵌笔记组织和全局搜索的笔记应用程序。 ![](https://img.shields.io/github/stars/lukasbach/yana.svg?style=social&label=Star)
- [Moonview](https://github.com/teesloane/moonview) - 笔记应用。 ![](https://img.shields.io/github/stars/teesloane/moonview.svg?style=social&label=Star)

### 浏览器

- [Beaker](https://github.com/beakerbrowser/beaker) - 具有点对点网络协议的浏览器。 ![](https://img.shields.io/github/stars/beakerbrowser/beaker.svg?style=social&label=Star)
- [Min](https://github.com/minbrowser/min) - 小巧的网络浏览器。 ![](https://img.shields.io/github/stars/minbrowser/min.svg?style=social&label=Star)
- [Wexond](https://github.com/sential/wexond) - 基于 Electron 的现代且功能丰富的 Web 浏览器。 ![](https://img.shields.io/github/stars/sential/wexond.svg?style=social&label=Star)

### Git

- [Git-it](https://github.com/jlord/git-it-electron) - 教你使用 Git 和 GitHub。 ![](https://img.shields.io/github/stars/jlord/git-it-electron.svg?style=social&label=Star)
- [Gitify](https://github.com/manosim/gitify) - 菜单栏中的 GitHub 通知。 ![](https://img.shields.io/github/stars/manosim/gitify.svg?style=social&label=Star)
- [GReader](https://github.com/Nekle/greader) - 收集和阅读 GitHub 存储库的离线 README 文件。 ![](https://img.shields.io/github/stars/Nekle/greader.svg?style=social&label=Star)

### 数据库客户端

- [Medis](https://github.com/luin/medis) - Redis 数据库管理。 ![](https://img.shields.io/github/stars/luin/medis.svg?style=social&label=Star)
- [Beekeeper Studio](https://github.com/beekeeper-studio/beekeeper-studio) - 跨平台的 SQL 编辑器和数据库管理。 ![](https://img.shields.io/github/stars/beekeeper-studio/beekeeper-studio.svg?style=social&label=Star)
- [Sqlectron](https://github.com/sqlectron/sqlectron-gui) - SQL 客户端。 ![](https://img.shields.io/github/stars/sqlectron/sqlectron-gui.svg?style=social&label=Star)
- [Mongotron](https://github.com/officert/mongotron) - MongoDB 管理工具。 ![](https://img.shields.io/github/stars/officert/mongotron.svg?style=social&label=Star)
- [DBGlass](https://github.com/web-pal/DBGlass) - PostgreSQL 客户端。 ![](https://img.shields.io/github/stars/web-pal/DBGlass.svg?style=social&label=Star)
- [LevelUI](https://github.com/hij1nx/levelui) - LevelDB 管理. ![](https://img.shields.io/github/stars/hij1nx/levelui.svg?style=social&label=Star)
- [PB for Desktop](https://github.com/sidneys/pb-for-desktop) - Pushbullet 客户端。 ![](https://img.shields.io/github/stars/sidneys/pb-for-desktop.svg?style=social&label=Star)

### 命令终端

- [Hyper](https://github.com/zeit/hyper) - 基于 Web 技术的命令终端。 ![](https://img.shields.io/github/stars/zeit/hyper.svg?style=social&label=Star)
- [edex-ui](https://github.com/GitSquared/edex-ui) - 一个跨平台、可定制的科幻终端模拟器，具有高级监控和支持触摸屏。 ![](https://img.shields.io/github/stars/GitSquared/edex-ui.svg?style=social&label=Star)
- [Extraterm](https://github.com/sedwards2009/extraterm) - 终端模拟器的瑞士军用电锯。 ![](https://img.shields.io/github/stars/sedwards2009/extraterm.svg?style=social&label=Star)

### 图像

- [Lightgallery](https://github.com/sachinchoolur/lightgallery-desktop) - 图片查看器。 ![](https://img.shields.io/github/stars/sachinchoolur/lightgallery-desktop.svg?style=social&label=Star)
- [Imagemin](https://github.com/imagemin/imagemin-app) - 图片压缩。 ![](https://img.shields.io/github/stars/imagemin/imagemin-app.svg?style=social&label=Star)
- [ExifCleaner](https://github.com/szTheory/exifcleaner) - 通过拖放清除图片元信息。 ![](https://img.shields.io/github/stars/szTheory/exifcleaner.svg?style=social&label=Star)
- [Ansel](https://github.com/m0g/ansel) - 图片管理。 ![](https://img.shields.io/github/stars/m0g/ansel.svg?style=social&label=Star)
- [SpaceEye](https://github.com/KYDronePilot/SpaceEye) - Mac 或 Windows 桌面背景的实时卫星图像。 ![](https://img.shields.io/github/stars/KYDronePilot/SpaceEye.svg?style=social&label=Star)

### 视频/音频

- [lx-music-desktop](https://github.com/lyswhut/lx-music-desktop) - 一个基于 electron 的音乐软件。 ![](https://img.shields.io/github/stars/lyswhut/lx-music-desktop.svg?style=social&label=Star)
- [YesPlayMusic](https://github.com/qier222/YesPlayMusic) - 高颜值的第三方网易云播放器。 ![](https://img.shields.io/github/stars/qier222/YesPlayMusic.svg?style=social&label=Star)
- [lossless-cut](https://github.com/mifi/lossless-cut) - 无损视频/音频编辑。 ![](https://img.shields.io/github/stars/mifi/lossless-cut.svg?style=social&label=Star)
- [Google Play Music Desktop Player](https://github.com/MarshallOfSound/Google-Play-Music-Desktop-Player-UNOFFICIAL-) - 非官方的 Google Play 音乐应用。 ![](https://img.shields.io/github/stars/MarshallOfSound/Google-Play-Music-Desktop-Player-UNOFFICIAL-.svg?style=social&label=Star)
- [Nuclear](https://github.com/nukeop/nuclear) - 为您找到免费音乐的流媒体音乐播放器。 ![](https://img.shields.io/github/stars/nukeop/nuclear.svg?style=social&label=Star)
- [Cumulus](https://github.com/gillesdemey/Cumulus) - 菜单栏中的 SoundCloud 播放器。 ![](https://img.shields.io/github/stars/gillesdemey/Cumulus.svg?style=social&label=Star)
- [Museeks](https://github.com/KeitIG/museeks) - 音乐播放器。 ![](https://img.shields.io/github/stars/KeitIG/museeks.svg?style=social&label=Star)
- [Kaku](https://github.com/EragonJ/Kaku) - Kaku 是一个高度集成的音乐播放器，支持不同的在线平台，如 YouTube、SoundCloud、Vimeo 等。 适用于 Mac、Windows 和 Linux。 ![](https://img.shields.io/github/stars/EragonJ/Kaku.svg?style=social&label=Star)
- [Gokotta](https://github.com/Zhangdroid/Gokotta) - 音乐播放器。 ![](https://img.shields.io/github/stars/Zhangdroid/Gokotta.svg?style=social&label=Star)
- [Yoda](https://github.com/whoisandie/yoda) - 浏览和下载 YouTube 视频。 ![](https://img.shields.io/github/stars/whoisandie/yoda.svg?style=social&label=Star)
- [PupaFM](https://github.com/xwartz/PupaFM) - DoubanFM 音乐播放器。 ![](https://img.shields.io/github/stars/xwartz/PupaFM.svg?style=social&label=Star)
- [google-music-electron](https://github.com/twolfson/google-music-electron) - 非官方 Google 音乐App。 ![](https://img.shields.io/github/stars/twolfson/google-music-electron.svg?style=social&label=Star)
- [VOX](https://github.com/fresk-nc/VOX) - 非官方的 VOX 音乐播放器。 ![](https://img.shields.io/github/stars/fresk-nc/VOX.svg?style=social&label=Star)
- [Toby](https://github.com/frankhale/toby) - YouTube播放器。 ![](https://img.shields.io/github/stars/frankhale/toby.svg?style=social&label=Star)
- [Kyoku](https://github.com/cheeaun/kyoku) - 播放当前 iTunes 歌曲。 ![](https://img.shields.io/github/stars/cheeaun/kyoku.svg?style=social&label=Star)
- [Yays](https://github.com/Bahlaouane-Hamza/Yays) - 菜单栏中的 YouTube 音乐播放器。 ![](https://img.shields.io/github/stars/Bahlaouane-Hamza/Yays.svg?style=social&label=Star)
- [Tubehead](https://github.com/makotot/Tubehead) - 菜单栏中的 YouTube 音乐播放器。 ![](https://img.shields.io/github/stars/makotot/Tubehead.svg?style=social&label=Star)

### 屏幕录制/共享

- [Kap](https://github.com/wulkano/kap) - 支持 GIF 的屏幕录像。 ![](https://img.shields.io/github/stars/wulkano/kap.svg?style=social&label=Star)
- [ScreenCat](https://github.com/maxogden/screencat) - 屏幕共享和远程协作。 ![](https://img.shields.io/github/stars/maxogden/screencat.svg?style=social&label=Star)
- [Snapper](https://github.com/pt2121/Snapper) - 适用于 Android 设备的屏幕捕获和录制。 ![](https://img.shields.io/github/stars/pt2121/Snapper.svg?style=social&label=Star)

### 密码

- [KeeWeb](https://github.com/keeweb/keeweb) - 非官方的 KeePass 应用。 ![](https://img.shields.io/github/stars/keeweb/keeweb.svg?style=social&label=Star)
- [Buttercup Desktop](https://github.com/buttercup/buttercup-desktop) - 密码管理。 ![](https://img.shields.io/github/stars/buttercup/buttercup-desktop.svg?style=social&label=Star)
- [Swifty](https://github.com/swiftyapp/swifty) - 密码管理。 ![](https://img.shields.io/github/stars/swiftyapp/swifty.svg?style=social&label=Star)
- [Hawkpass](https://github.com/kalpetros/hawkpass) - 密码生成。 ![](https://img.shields.io/github/stars/kalpetros/hawkpass.svg?style=social&label=Star)

### Messenger

- [Electronic WeChat](https://github.com/geeeeeeeeek/electronic-wechat) - 非官方微信应用。 ![](https://img.shields.io/github/stars/geeeeeeeeek/electronic-wechat.svg?style=social&label=Star)
- [Caprine](https://github.com/sindresorhus/caprine) - 非官方的 Facebook Messenger 应用程序。 ![](https://img.shields.io/github/stars/sindresorhus/caprine.svg?style=social&label=Star)
- [Franz](https://github.com/meetfranz/franz) - Skype、Slack、Hangouts、WhatsApp、Grape、Telegram、FB Messenger、Hipchat 在同一个应用程序中。 ![](https://img.shields.io/github/stars/meetfranz/franz.svg?style=social&label=Star)
- [Friends](https://github.com/moose-team/friends) - 点对点聊天。 ![](https://img.shields.io/github/stars/moose-team/friends.svg?style=social&label=Star)
- [Wire](https://github.com/wireapp/wire-desktop) - Messenger 和通话。 ![](https://img.shields.io/github/stars/wireapp/wire-desktop.svg?style=social&label=Star)

### Email

- [nylas-mail](https://github.com/nylas/nylas-mail) - Nylas Mail 是一个开源邮件客户端，构建在现代网络上，使用 Electron、React 和 Flux。它被设计为易于扩展。 ![](https://img.shields.io/github/stars/Foundry376/Mailspring.svg?style=social&label=Star)
- [Mailspring](https://github.com/Foundry376/Mailspring) - 可扩展的电子邮件客户端(Fork of Nylas Mail)。 ![](https://img.shields.io/github/stars/Foundry376/Mailspring.svg?style=social&label=Star)
- [Rambox](https://github.com/saenzramiro/rambox) - 结合了 Discord、环聊、Gmail 和 Outlook 等多种服务的聊天和电子邮件。 ![](https://img.shields.io/github/stars/saenzramiro/rambox.svg?style=social&label=Star)
- [Wmail](https://github.com/Thomas101/wmail) - 非官方 Gmail 和 Google Inbox 应用程序。 ![](https://img.shields.io/github/stars/Thomas101/wmail.svg?style=social&label=Star)
- [Gmail Desktop](https://github.com/timche/gmail-desktop) - 非官方 Gmail 应用程序。 ![](https://img.shields.io/github/stars/timche/gmail-desktop.svg?style=social&label=Star)
- [ProtonMail Desktop](https://github.com/protonmail-desktop/application) - 非官方 ProtonMail 应用程序。 ![](https://img.shields.io/github/stars/protonmail-desktop/application.svg?style=social&label=Star)

### Docker

- [Kitematic](https://github.com/docker/kitematic) - Docker 容器管理。 ![](https://img.shields.io/github/stars/docker/kitematic.svg?style=social&label=Star)
- [Eintopf](https://github.com/mazehall/eintopf) - 使用 Docker 管理开发项目。 ![](https://img.shields.io/github/stars/mazehall/eintopf.svg?style=social&label=Star)
- [docker-indicator](https://github.com/khornberg/docker-indicator) - 非官方 Docker 菜单栏应。 ![](https://img.shields.io/github/stars/khornberg/docker-indicator.svg?style=social&label=Star)

### 硬件统计信息

- [SpaceRadar](https://github.com/zz85/space-radar) - 交互式磁盘空间和内存可视化。 ![](https://img.shields.io/github/stars/zz85/space-radar.svg?style=social&label=Star)
- [iStats](https://github.com/ningt/iStats) - 菜单栏上显示的 CPU 和内存统计信息. ![](https://img.shields.io/github/stars/ningt/iStats.svg?style=social&label=Star)

### HTTP

- [Insomnia](https://github.com/getinsomnia/insomnia) - 创建和管理 HTTP 请求。 ![](https://img.shields.io/github/stars/getinsomnia/insomnia.svg?style=social&label=Star)
- [James](https://github.com/uxebu/james) -  HTTP 代理，用于查看和拦截浏览器请求的。 ![](https://img.shields.io/github/stars/uxebu/james.svg?style=social&label=Star)

### 下载

- [Motrix](https://github.com/agalwood/Motrix) - 下载管理工具 ![](https://img.shields.io/github/stars/agalwood/Motrix.svg?style=social&label=Star)
- [WebTorrent](https://github.com/feross/webtorrent-app) - 流媒体下载客户端。 ![](https://img.shields.io/github/stars/feross/webtorrent-app.svg?style=social&label=Star)
- [nuTorrent](https://github.com/LeeChSien/nuTorrent) - BitTorrent 客户端。 ![](https://img.shields.io/github/stars/LeeChSien/nuTorrent.svg?style=social&label=Star)

### 效率

- [Pomotroid](https://github.com/Splode/pomotroid) - 番茄时间管理定时器。 ![](https://img.shields.io/github/stars/Splode/pomotroid.svg?style=social&label=Star)
- [Ao](https://github.com/klauscfhq/ao) - 非官方的微软 ToDo 应用。![](https://img.shields.io/github/stars/klauscfhq/ao.svg?style=social&label=Star)
- [Pomodoro](https://github.com/G07cha/pomodoro) - 基于番茄工作法的计时器。 ![](https://img.shields.io/github/stars/G07cha/pomodoro.svg?style=social&label=Star)
- [VIR](https://github.com/TommyX12/VIR) - 具有自动计划功能的智能时间管理器。 ![](https://img.shields.io/github/stars/TommyX12/VIR.svg?style=social&label=Star)
- [dida](https://github.com/xwartz/dida) - 添加任务到 TickTick (滴答清单). ![](https://img.shields.io/github/stars/xwartz/dida.svg?style=social&label=Star)

### 应用启动器

- [Cerebro](https://github.com/KELiON/cerebro) - 带内部预览的应用启动器。 ![](https://img.shields.io/github/stars/KELiON/cerebro.svg?style=social&label=Star)
- [Hain](https://github.com/appetizermonster/hain) - 用于 Windows 的应用启动器。![](https://img.shields.io/github/stars/appetizermonster/hain.svg?style=social&label=Star)
- [Zazu](https://github.com/tinytacoteam/zazu) - 应用启动器。 ![](https://img.shields.io/github/stars/tinytacoteam/zazu.svg?style=social&label=Star)
- [Dext](https://github.com/vutran/dext) - 应用启动器。 ![](https://img.shields.io/github/stars/vutran/dext.svg?style=social&label=Star)

### 一些非官方的应用

- [YakYak](https://github.com/yakyak/yakyak) - 非官方的 Google Hangouts 应用. ![](https://img.shields.io/github/stars/yakyak/yakyak.svg?style=social&label=Star)
- [Ramme](https://github.com/terkelg/ramme) - 非官方的 Instagram 应用. ![](https://img.shields.io/github/stars/terkelg/ramme.svg?style=social&label=Star)
- [DevDocs](https://github.com/egoist/devdocs-app) - 非官方的 DevDocs.io 应用. ![](https://img.shields.io/github/stars/egoist/devdocs-app.svg?style=social&label=Star)
- [Mattermost](https://github.com/mattermost/desktop) - Mattermost 客户端. ![](https://img.shields.io/github/stars/mattermost/desktop.svg?style=social&label=Star)
- [WhatsDesktop](https://github.com/mawie81/whatsdesktop) - 非官方的 WhatsApp 应用. ![](https://img.shields.io/github/stars/mawie81/whatsdesktop.svg?style=social&label=Star)
- [Fog](https://github.com/vitorgalvao/fog) - 非官方的 Overcast podcast 应用。 ![](https://img.shields.io/github/stars/vitorgalvao/fog.svg?style=social&label=Star)
- [MediumDesk](https://github.com/sivragav/mediumdesk) - 非官方的 Medium 应用。 ![](https://img.shields.io/github/stars/sivragav/mediumdesk.svg?style=social&label=Star)
- [GroupMe](https://github.com/dcrousso/GroupMe) - 非官方的 GroupMe 应用。 ![](https://img.shields.io/github/stars/dcrousso/GroupMe.svg?style=social&label=Star)
- [DTCP](https://github.com/alchen/DTCP) - 非官方的 Twitter 客户端。 ![](https://img.shields.io/github/stars/alchen/DTCP.svg?style=social&label=Star)
- [Active Collab](https://github.com/nurtext/active-collab-desktop) - 非官方的 Active Collab 应用。 ![](https://img.shields.io/github/stars/nurtext/active-collab-desktop.svg?style=social&label=Star)

## 相关链接

- [awesome-nodejs](https://github.com/huaize2020/awesome-nodejs) ![](https://img.shields.io/github/stars/huaize2020/awesome-nodejs.svg?style=social&label=Star)
