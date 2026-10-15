# bookokrat

[English Version](./README.md)

终端 EPUB / PDF / DJVU 电子书阅读器，主打速度、流畅导航和 Vim 风格操作。| A terminal EPUB / PDF / DJVU book reader focused on speed, smooth navigation, and Vim-style workflows.

[![x-cmd/install — bookokrat Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/bookokrat.svg)](https://x-cmd.com/install/bookokrat)

## 安装

```sh
x install bookokrat
```

## 源码

- **上游仓库**: <https://github.com/bugzmanov/bookokrat>
- **项目主页**: <https://bugzmanov.github.io/bookokrat/index.html>
- **许可证**: AGPL-3.0

## 主要特性

- 一个 TUI 应用同时支持 EPUB、PDF 与 DJVU
- 分栏布局：左侧为书库 / 目录，右侧为阅读区
- 支持终端的 PDF / DJVU 渲染管线（Kitty SHM 图像传输）
- 搜索、书签、跳转历史、阅读统计
- 内联批注 / 评论，持久化存储并支持 Markdown 导出
- Vim 风格快捷键与 normal 模式