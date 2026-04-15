<h1><img src="logo.svg" width="32" height="32" alt="logo" style="vertical-align: middle;"> AI划词解释</h1>

[![Chrome Web Store](https://img.shields.io/badge/Chrome-应用商店-green?style=flat&logo=google-chrome)](https://chromewebstore.google.com/detail/select-ai-ai%E5%88%92%E8%AF%8D%E8%A7%A3%E9%87%8B/ehcjdmkcnjniaofflhghckpgmjmbgkjh) [![Website](https://img.shields.io/badge/官网-select--ai.cn-blue?style=flat)](https://select-ai.cn) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript) [![English README](https://img.shields.io/badge/English-README-gray?style=flat)](./README.md)

**版本**: v0.8.3

---

## 🎯 什么是 AI 划词解释？

> **选中文字，AI 基于上下文理解，直接告诉你答案**

你有没有过这样的经历：读一篇外语文章，突然遇到一个生词，然后就开始复制、切换搜索引擎、粘贴、等待加载……好不容易查到意思了，刚才看到哪儿了？

**AI 划词解释就是为了解决这个问题而生的。** 在任何网页上选中文字，就能获得即时、符合上下文的解释，不会打断你的阅读节奏。

---

## ✨ 核心功能

| | |
|:---:|:---|
| 🎯 **AI 划词解释** | 选中文字，悬浮立刻显示 AI 解释与翻译 |
| 🧠 **上下文理解** | 基于当前页面内容智能分析，给出更准确的释义 |
| 🇯🇵 **日语假名流式标注** | 选中日语自动标注假名，汉字读音一目了然 |
| 📖 **双语字幕式翻译** | 原文+译文对照阅读，完美支持英语/日语/外文网站 |
| 🖼️ **OCR 图文识别** | 右键图片或截图提取文字并解释 |
| 🌊 **流式响应** | 实时观看 AI 生成答案，无需等待 |
| ⚡ **6 大 AI 提供商** | OpenAI、Anthropic、DeepSeek、MiniMax、智谱 AI，或内置免费额度 |
| 🔒 **隐私优先** | API Key 本地存储，不收集任何数据 |

### 适合谁用？

| 目标用户 | |
|:---|:---|
| 🌏 外语学习者 | 💻 程序员 |
| 📚 文献阅读者 | ✈️ 留学党 |
| 🇯🇵 日语爱好者 | 🌍 多语言工作者 |

---

## 💡 产品理念

> **不只是翻译。在你阅读的时候，帮你把卡住的地方直接解开，不打断你。**

- ⚡ **快** — 选中就有答案，不打断阅读节奏
- 🧠 **懂你** — 明白你读的语境，不只是孤立查词
- 📝 **总结** — 选中标题或段落，直接整理整篇内容
- 🔒 **安全** — 你的数据只在你本地，不会上传到服务器

---

## 🔌 支持的 API

| 提供商 | 默认模型 | 格式 |
|----------|---------------|--------|
| **免费**（默认） | MiniMax-M2.7-highspeed | Anthropic |
| **DeepSeek** | deepseek-chat | OpenAI |
| **OpenAI** | gpt-4o | OpenAI |
| **Anthropic** | claude-sonnet-4-20250514 | Anthropic |
| **MiniMax** | MiniMax-M2.7-highspeed | Anthropic |
| **智谱 AI** | glm-4-flash | Anthropic |

### 调用限额

| 用户类型 | 每日限额 |
|-----------|-------------|
| 访客 | 40 次 |
| 免费用户 | 100 次 |
| Pro 用户 | 自定义 |

---

## 🔐 隐私与安全

| | |
|:---:|:---|
| 💾 **本地存储** | 你的 API Key 保存在浏览器本地 |
| 🔒 **无数据收集** | 不向任何服务器上传用户数据 |
| ⚔️ **最小权限** | 仅请求功能所需的必要权限 |

---

## ❓ 常见问题

<details>
<summary><strong>AI划词解释是免费的吗？</strong></summary>

扩展程序免费安装。你只需支付所使用的 AI API 调用费用（DeepSeek、OpenAI 等）。大多数提供商都有慷慨的免费额度。
</details>

<details>
<summary><strong>没有 API 也能用吗？</strong></summary>

可以！插件内置了免费大模型 API，无需配置即可直接使用。每日有限次免费额度，用完可自行配置 API Key 继续使用。
</details>

<details>
<summary><strong>支持哪些语言？</strong></summary>

支持 AI 模型所支持的所有语言 — 包括英语、中文、日语、韩语、西班牙语、法语、德语等。
</details>

<details>
<summary><strong>在所有网站都能用吗？</strong></summary>

大多数网站都支持。不支持 chrome:// 系统页面和部分受限域名。
</details>

<details>
<summary><strong>OCR 功能呢？</strong></summary>

右键点击任意图片或截图提取文字并解释。语言包首次使用时自动下载（英语: 20MB / 日语: 50MB / 中文: 50MB）。
</details>

---

## 🚀 快速开始

```
1. 下载 select-ai.zip
2. 解压 → Chrome → chrome://extensions/
3. 开启开发者模式 → 加载已解压的扩展程序
4. 打开选项页面 → 添加你的 API Key（或使用内置免费额度）
5. 在任意网页选中文字 → 点击悬浮按钮
```

---

<div align="center">

⭐ 如果对你有帮助，欢迎给我们一个 Star

---

*用 ❤️ 让外语阅读不再困难*

</div>