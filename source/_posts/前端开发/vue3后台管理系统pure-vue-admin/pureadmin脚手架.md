---
title: pureadmin脚手架
tags:
  - pureadmin
  - cli
categories:
  - 前端开发
  - vue3后台管理系统pure-vue-admin
date: 2024-05-05 16:39:24
---
文档地址[pure-admin/pure-admin-cli: 快速构建pure-admin相关项目的命令行工具 (github.com)](https://github.com/pure-admin/pure-admin-cli#pureadmincli)

## 🏠 模板类型

---

| **模板类型**   | **仓库地址**                                                                          |
| :--------- | :-------------------------------------------------------------------------------- |
| `admin`    | [vue-pure-admin 完整版本](https://github.com/pure-admin/vue-pure-admin)               |
| `thin`     | [vue-pure-admin 非国际化精简版本](https://github.com/pure-admin/pure-admin-thin)          |
| `i18n`     | [vue-pure-admin 国际化精简版本](https://github.com/pure-admin/pure-admin-thin/tree/i18n) |
| `tauri`    | [vue-pure-admin 的 tauri 版本](https://github.com/pure-admin/tauri-pure-admin)       |
| `electron` | [vue-pure-admin 的 electron 版本](https://github.com/pure-admin/electron-pure-admin) |

## 📦 全局安装

---

```shell
npm install -g @pureadmin/cli
# or
yarn global add @pureadmin/cli
# or
pnpm add -g @pureadmin/cli
```

## 🚀 全局升级

---

```shell
npm update -g @pureadmin/cli
# or
yarn global upgrade --latest @pureadmin/cli
# or
pnpm up --latest -g @pureadmin/cli
```

## ⛽ 全局卸载

---

```shell
npm uninstall -g @pureadmin/cli
# or
yarn global remove @pureadmin/cli
# or
pnpm remove -g @pureadmin/cli
```

## ⚙️ 用法

---

pure init `模板类型` `项目名称`

```shell
pure init thin myproject
```

交互式选择模板并创建项目

```shell
pure create
```

当然也可以选择不安装`@pureadmin/cli`创建项目

```shell
npx @pureadmin/cli init thin myproject
# or
npx @pureadmin/cli create
```

## 🔎 更多命令

---

检查版本，也可以用于检查是否成功安装`@pureadmin/cli`

```shell
pure -v
```

类似下图所示，代表安装成功

[![pure-v](https://camo.githubusercontent.com/3b7ca3edf7c6d53ef8e3c6503d49a532b7c5eca7127e5f2c1e25bf0208dcef4c/68747470733a2f2f7869616f7869616e3532312e6769746875622e696f2f68797065726c696e6b2f696d672f70757265436c69762e6a7067)](https://camo.githubusercontent.com/3b7ca3edf7c6d53ef8e3c6503d49a532b7c5eca7127e5f2c1e25bf0208dcef4c/68747470733a2f2f7869616f7869616e3532312e6769746875622e696f2f68797065726c696e6b2f696d672f70757265436c69762e6a7067)

更多帮助信息

```shell
pure -h
```