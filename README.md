[English](./README-en.md) | 简体中文

## 目录

- [目录](#目录)
- [官方资源](#官方资源)
- [资源](#资源)
  - [工具](#工具)
- [GIT 仓库](#git-仓库)
  - [进程间通信(IPC)](#进程间通信ipc)
  - [检测/判断](#检测判断)
  - [位置/尺寸](#位置尺寸)
  - [窗口相关](#窗口相关)
  - [界面相关](#界面相关)
  - [持久化](#持久化)
  - [数据库](#数据库)
  - [打包程序/安装程序](#打包程序安装程序)
  - [自动更新/发布服务器](#自动更新发布服务器)
  - [日志](#日志)
  - [调试](#调试)
  - [开发工具](#开发工具)
  - [测试](#测试)

## 官方资源

- [官网](https://www.electronjs.org)
- [文档](https://www.electronjs.org/zh/docs/latest/)
- [仓库](https://github.com/electron/electron) ![](https://img.shields.io/github/stars/electron/electron.svg?style=social&label=Star)

## 资源

### 工具

- [Electron Fiddle](https://www.electronjs.org/fiddle) - The easiest way to get started with Electron.

## GIT 仓库

### 进程间通信(IPC)

- [electron-better-ipc](https://github.com/sindresorhus/electron-better-ipc) - 简化 IPC 通信 ![](https://img.shields.io/github/stars/sindresorhus/electron-better-ipc.svg?style=social&label=Star)
- [ipc-stream](https://github.com/jprichardson/electron-ipc-stream) - IPC 的双工流。 ![](https://img.shields.io/github/stars/jprichardson/electron-ipc-stream.svg?style=social&label=Star)
- [electron-ipc-proxy](https://github.com/frankwallis/electron-ipc-proxy) - 基于IPC进行渲染进程和主进程之间透明异步远程通信。 ![](https://img.shields.io/github/stars/frankwallis/electron-ipc-proxy.svg?style=social&label=Star)

### 检测/判断

- [electron-is-dev](https://github.com/sindresorhus/electron-is-dev) - 检查Electron是否允许在开发环境 ![](https://img.shields.io/github/stars/sindresorhus/electron-is-dev.svg?style=social&label=Star)
- [electron-is](https://github.com/delvedor/electron-is) - Electron 的“is”工具，它提供了一组方便的函数。 ![](https://img.shields.io/github/stars/delvedor/electron-is.svg?style=social&label=Star)
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

- [electron-context-menu](https://github.com/sindresorhus/electron-context-menu) - 可扩展的右键菜单。 ![](https://img.shields.io/github/stars/sindresorhus/electron-context-menu.svg?style=social&label=Star)
- [electron-vibrancy](https://github.com/arkenthera/electron-vibrancy) - 为窗户添加活力（模糊功能）。 ![](https://img.shields.io/github/stars/arkenthera/electron-vibrancy.svg?style=social&label=Star)
- [electron-create-menu](https://github.com/kilian/electron-create-menu) - 跨全平台的默认菜单，易于扩展，并支持 i18n。 ![](https://img.shields.io/github/stars/kilian/electron-create-menu.svg?style=social&label=Star)

### 持久化

- [electron-store](https://github.com/sindresorhus/electron-store) - 保存和加载用户偏好、应用状态、缓存等数据。 ![](https://img.shields.io/github/stars/sindresorhus/electron-store.svg?style=social&label=Star)
- [electron-json-storage](https://github.com/jviotti/electron-json-storage) - 读写用户设置。 ![](https://img.shields.io/github/stars/jviotti/electron-json-storage.svg?style=social&label=Star)
- [electron-settings](https://github.com/nathanbuchar/electron-settings) - 读写用户设置到硬盘。 ![](https://img.shields.io/github/stars/nathanbuchar/electron-settings.svg?style=social&label=Star)

### 数据库

- [RxDB](https://github.com/pubkey/rxdb) - 实时 NoSQL 数据库。 ![](https://img.shields.io/github/stars/pubkey/rxdb.svg?style=social&label=Star)
- [NeDB](https://github.com/louischatriot/nedb) - 嵌入式持久化或内存数据库。 ![](https://img.shields.io/github/stars/louischatriot/nedb.svg?style=social&label=Star)
- [trilogy](https://github.com/citycide/trilogy) - TypeScript SQLite 数据库层，支持原生 C++ 和纯 JavaScript 后端。 ![](https://img.shields.io/github/stars/citycide/trilogy.svg?style=social&label=Star)

### 打包程序/安装程序

- [electron-builder](https://github.com/electron-userland/electron-builder) - 创建安装程序。 ![](https://img.shields.io/github/stars/electron-userland/electron-builder.svg?style=social&label=Star)
- [electron-packager](https://github.com/electron-userland/electron-packager) - 打包应用。 ![](https://img.shields.io/github/stars/electron-userland/electron-packager.svg?style=social&label=Star)
- [ember-electron](https://github.com/felixrieseberg/ember-electron) - 构建、测试和打包 Ember 应用。 ![](https://img.shields.io/github/stars/felixrieseberg/ember-electron.svg?style=social&label=Star)
- [electron-installer-windows](https://github.com/unindented/electron-installer-windows) - 构建 Windows 包。 ![](https://img.shields.io/github/stars/unindented/electron-installer-windows.svg?style=social&label=Star)
- [electron-installer-debian](https://github.com/unindented/electron-installer-debian) - 构建 Debian 包。 ![](https://img.shields.io/github/stars/unindented/electron-installer-debian.svg?style=social&label=Star)
- [electrify](https://github.com/arboleya/electrify) - 打包 Meteor 应用。 ![](https://img.shields.io/github/stars/arboleya/electrify.svg?style=social&label=Star)
- [electron-installer-redhat](https://github.com/unindented/electron-installer-redhat) - 构建 Red Hat 包。 ![](https://img.shields.io/github/stars/unindented/electron-installer-redhat.svg?style=social&label=Star)

### 自动更新/发布服务器

- [electron-release-server](https://github.com/ArekSredzki/electron-release-server) - 具有前端和自动更新程序支持的自托管发布服务器。 ![](https://img.shields.io/github/stars/ArekSredzki/electron-release-server.svg?style=social&label=Star)
- [nuts](https://github.com/GitbookIO/nuts) - 依赖 GitHub 的自动更新发布/下载服务器。 ![](https://img.shields.io/github/stars/GitbookIO/nuts.svg?style=social&label=Star)

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

### 测试

- [spectron](https://github.com/electron-userland/spectron) - 使用 ChromeDriver 测试 Electron 应用。 ![](https://img.shields.io/github/stars/electron-userland/spectron.svg?style=social&label=Star)
- [electron-mocha](https://github.com/jprichardson/electron-mocha) - 在 Electron 中运行 Mocha 测试用例。 ![](https://img.shields.io/github/stars/jprichardson/electron-mocha.svg?style=social&label=Star)
