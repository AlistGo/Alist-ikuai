# iKuai 路由器 Alist 插件

[![Build Alist ipkg](https://github.com/AlistGo/Alist-ikuai/actions/workflows/build.yml/badge.svg)](https://github.com/AlistGo/Alist-ikuai/actions/workflows/build.yml)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/AlistGo/Alist-ikuai)](https://github.com/AlistGo/Alist-ikuai/releases)

本仓库提供了一个自动构建系统，用于将 [Alist](https://github.com/AlistGo/alist) 打包为适用于 iKuai 路由器的 `.ipkg` 应用。

## 🚀 功能特性

- **自动更新**: 每日自动检查 Alist 官方版本发布。
- **Docker 集成**: 专为 iKuai Docker 环境优化。
- **自动配置**: 若配置文件不存在，自动初始化管理员密码为 `123456`。

## 📦 安装说明

1. 前往 [Releases](https://github.com/AlistGo/Alist-ikuai/releases) 页面。
2. 下载最新的 `.ipkg` 文件 (例如 `alist-v3.57.0.ipkg`)。
3. 通过 iKuai 应用中心 -> 第三方应用 (或本地应用) 上传并安装。

## ⚙️ 使用说明

- **默认地址**: `http://<路由器IP>:5244`
- **默认账号**: `admin`
- **默认密码**: `123456` (⚠️ 登录后请立即修改!)

## 🔗 相关链接

- [Alist 官方仓库](https://github.com/AlistGo/alist)
- [iKuai 官网](https://www.ikuai8.com/)

---
*Built with ❤️ by [Attributes](https://github.com/attributes)*
