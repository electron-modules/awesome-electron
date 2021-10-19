[English](./README-en.md) | 简体中文

## 目录

- [目录](#目录)
- [官方资源](#官方资源)
- [资源](#资源)
  - [工具](#工具)
- [库](#库)
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
  - [效率](#效率)
  - [应用启动器](#应用启动器)
  - [一些非官方的应用](#一些非官方的应用)
- [相关链接](#相关链接)

## 官方资源

- [官网](https://www.electronjs.org)
- [文档](https://www.electronjs.org/zh/docs/latest/)
- [仓库](https://github.com/electron/electron) ![](https://img.shields.io/github/stars/electron/electron.svg?style=social&label=Star)

## 资源

### 工具

- [Electron Fiddle](https://www.electronjs.org/fiddle) - 最简单的 Electron 入门方式。

## 库

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
- [electron-reloader](https://github.com/sindresorhus/electron-reloader) - 在开发过程中，自动重新加载。 ![](https://img.shields.io/github/stars/sindresorhus/electron-reloader.svg?style=social&label=Star)
- [elemon](https://github.com/manidlou/elemon) - 开发过程中热更新。 ![](https://img.shields.io/github/stars/manidlou/elemon.svg?style=social&label=Star)
- [electronmon](https://github.com/catdad/electronmon) - 运行，监控并重启应用。 ![](https://img.shields.io/github/stars/catdad/electronmon.svg?style=social&label=Star)

### 测试

- [spectron](https://github.com/electron-userland/spectron) - 使用 ChromeDriver 测试 Electron 应用。 ![](https://img.shields.io/github/stars/electron-userland/spectron.svg?style=social&label=Star)
- [electron-mocha](https://github.com/jprichardson/electron-mocha) - 在 Electron 中运行 Mocha 测试用例。 ![](https://img.shields.io/github/stars/jprichardson/electron-mocha.svg?style=social&label=Star)
- [jest-electron](https://github.com/hustcc/jest-electron) - 运行和调试 Jest 单元测试到浏览器环境中。 ![](https://img.shields.io/github/stars/hustcc/jest-electron.svg?style=social&label=Star)

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
- [Extraterm](https://github.com/sedwards2009/extraterm) - 终端模拟器的瑞士军用电锯。 ![](https://img.shields.io/github/stars/sedwards2009/extraterm.svg?style=social&label=Star)

### 图像

- [Lightgallery](https://github.com/sachinchoolur/lightgallery-desktop) - 图片查看器。 ![](https://img.shields.io/github/stars/sachinchoolur/lightgallery-desktop.svg?style=social&label=Star)
- [Imagemin](https://github.com/imagemin/imagemin-app) - 图片压缩。 ![](https://img.shields.io/github/stars/imagemin/imagemin-app.svg?style=social&label=Star)
- [ExifCleaner](https://github.com/szTheory/exifcleaner) - 通过拖放清除图片元信息。 ![](https://img.shields.io/github/stars/szTheory/exifcleaner.svg?style=social&label=Star)
- [Ansel](https://github.com/m0g/ansel) - 图片管理。 ![](https://img.shields.io/github/stars/m0g/ansel.svg?style=social&label=Star)
- [SpaceEye](https://github.com/KYDronePilot/SpaceEye) - Mac 或 Windows 桌面背景的实时卫星图像。 ![](https://img.shields.io/github/stars/KYDronePilot/SpaceEye.svg?style=social&label=Star)

### 视频/音频

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
