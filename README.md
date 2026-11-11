# ChatGPT 流光背景

为 ChatGPT Android 添加循环流光彩色背景、控件及菜单磨砂、上下滚动边缘磨砂，并提供可选键盘黑色遮罩兼容。

## 使用环境

- Android 12L / API 32 及以上。
- 支持现代 libxposed API 102 的 LSPosed。
- ChatGPT 1.2026.307（构建 2630709、2630717、2630718）。
- 作用域：`com.openai.chatgpt`。

## 安装

下载安装 Release 中的 APK，打开模块设置，在 LSPosed 启用模块并选择 ChatGPT 作用域，强行停止并重新打开 ChatGPT。
从旧测试版迁移时，保留旧版直至新版完成首次参数导入；之后禁用旧模块并启用新版。

## 源码与支持

[NorthWolf8192/ChatGPT-Flow](https://github.com/NorthWolf8192/ChatGPT-Flow)

模块包名：`io.github.northwolf8192.chatgptflow`。本项目与 OpenAI 无关联。
