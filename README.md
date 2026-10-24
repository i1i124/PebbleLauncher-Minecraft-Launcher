# 碎石启动器 (RubbleLauncher)

一个为低配电脑优化的第三方 Minecraft 启动器。

- 轻量、低占用，尽量让老电脑也能顺畅启动游戏
- 基于 .NET 8 + Avalonia，支持 Windows / Linux / macOS
- 使用 CmlLib.Core 作为启动核心
- 开源，欢迎分发、修改、fork

> 本项目为第三方启动器，与 Mojang Studios / Microsoft 无任何官方关联。

## 功能

- [x] 版本列表选择
- [x] 离线登录
- [ ] 自动检查并下载游戏文件（客户端、依赖库、资源）（计划中）
- [ ] 实时显示下载进度（计划中）
- [ ] 用户名、版本等设置本地保存 （计划中）
- [ ] 微软正版登录（计划中）
- [ ] BMCLAPI 镜像加速（计划中）
- [ ] Java 路径自动探测（计划中）

## 技术栈

| 组件 | 说明 |
|---|---|
| .NET 8 | 运行时 |
| Avalonia 11 | 跨平台 UI 框架 |
| CommunityToolkit.Mvvm | MVVM 支持 |
| CmlLib.Core | Minecraft 启动核心 |

## 运行

```bash
dotnet restore
dotnet run

---

## 📄 `README.en.md`（English）

```markdown
# RubbleLauncher

English | [中文](README.md)

A third-party Minecraft launcher optimized for low-end PCs.

- Lightweight and low-overhead, designed to run smoothly on older machines
- Built with .NET 8 + Avalonia, supports Windows / Linux / macOS
- Powered by CmlLib.Core
- Open source, free to use, modify, distribute and fork

> This is a third-party launcher and is not affiliated with Mojang Studios or Microsoft.

## Features

- [x] Version list selection
- [x] Offline login
- [ ] Automatic game file check and download (client, libraries, assets) (planned)
- [ ] Real-time download progress (planned)
- [ ] Local settings persistence (username, version, etc.) (planned)
- [ ] Microsoft account login (planned)
- [ ] BMCLAPI mirror acceleration (planned)
- [ ] Automatic Java path detection (planned)

## Tech Stack

| Component | Description |
|---|---|
| .NET 8 | Runtime |
| Avalonia 11 | Cross-platform UI framework |
| CommunityToolkit.Mvvm | MVVM support |
| CmlLib.Core | Minecraft launch core |

## Run

```bash
dotnet restore
dotnet run
