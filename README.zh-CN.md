<h1><img src="logo.svg" width="32" height="32" alt="logo" style="vertical-align: middle;"> 解语</h1>

[![Chrome Web Store](https://img.shields.io/badge/Chrome-应用商店-green?style=flat&logo=google-chrome)](https://chromewebstore.google.com/detail/select-ai-ai%E5%88%92%E8%AF%8D%E8%A7%A3%E9%87%8A/ehcjdmkcnjniaofflhghckpgmjmbgkjh) [![Website](https://img.shields.io/badge/官网-select--ai.cn-blue?style=flat)](https://select-ai.cn) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript) [![Version](https://img.shields.io/badge/version-v0.16.1-8338ec?style=flat)](./CHANGELOG.md) [![更新日志](https://img.shields.io/badge/更新日志-查看-orange?style=flat)](./CHANGELOG.md) [![English README](https://img.shields.io/badge/English-README-gray?style=flat)](./README.md)

<p align="center">
  <strong>💛 支持项目</strong><br/>
  <sub>独立开发，没有广告。如果解语帮到了你，欢迎请我喝瓶可乐。</sub><br/>
  <img src="./assets/wechat-reward-code.png" alt="微信赞赏码" width="200" />
</p>

---

<p align="center">
  <img src="./assets/hero-select-explain.png" alt="解语划词解释" width="90%">
</p>

<p align="center">
  <img src="./assets/demo.gif" alt="解语使用演示" width="90%">
</p>

## 🎯 选中即解，语意自明

> **选中文字，AI 基于上下文理解，直接告诉你答案。**

读外文时遇到生词，你是不是也经历过：复制、切换 App、粘贴、等待……好不容易查到意思，刚才的阅读节奏也没了。而且很多工具只给一个孤立的词义，放回原文里到底想表达什么，还是要自己猜。

**解语不是又一个查词工具。** 它想做的是让网页本身具备一层 AI 理解能力：选中就解释，不跳出、不中断，给出的理解贴合上下文。

无需注册，无需配置 API Key，安装即用。

---

## ✨ 核心功能

### 1. 划词解释

在任意网页选中文字，解语自动提取上下文并给出解释——不是简单翻译，而是真正贴合语境的理解。

<p align="center">
  <img src="./assets/feature-explain.png" alt="上下文感知的划词解释" width="80%">
</p>

- 智能识别术语、标题、代码或普通句子
- 上下文权重感知，解释更贴合原文
- 流式响应，逐字呈现

### 2. 双语翻译

长文章也能完整翻译，不再中途截断。原文与译文对照显示。

<p align="center">
  <img src="./assets/feature-translation.png" alt="双语翻译" width="80%">
</p>

- Token 感知分块，长内容翻译不截断
- 翻译和解释可配置不同的 AI 模型
- 输出语言可自定义

### 3. YouTube 视频双语字幕

看外语视频时一键开启 AI 双语字幕。复用视频已有字幕，AI 实时翻译并用独立字幕 overlay 显示。

<p align="center">
  <img src="./assets/feature-youtube.png" alt="YouTube 双语字幕" width="80%">
</p>

- 无需复制字幕，一键开启
- 跟随播放进度实时同步
- 字幕字号自由调节
- 智能合并短片段，减少闪烁

### 4. 图片识别 / 图片理解

右键网页图片或截图，使用 AI Vision 模型提取并解释其中的文字、图表与界面。

<p align="center">
  <img src="./assets/feature-ocr.png" alt="图片识别" width="80%">
</p>

- AI Vision 模式：直接看懂图表、UI 截图、手写文字
- 截图模式：框选屏幕任意区域
- 支持为图片识别配置独立的 AI 模型

### 更多能力

| | |
|:---:|:---|
| 🧠 **思考模式** | 需要更深入分析时一键开启 |
| 🔊 **文字转语音** | 朗读解释内容，解放双眼 |
| ⌨️ **键盘快捷键** | Alt+E 解释、Alt+T 翻译、Alt+S 截图识别 |
| 🇯🇵 **日语假名标注** | 自动为日文汉字标注振假名 |
| 🔒 **隐私优先** | API Key 本地存储，不追踪用户 |

---

## 💡 适合谁用

| | |
|:---:|:---|
| 🌏 外语学习者 | 💻 阅读英文技术文档的开发者 |
| 📚 文献研究者与高校师生 | ✈️ 留学生与准留学生 |
| 🇯🇵 日语学习者 | 🎬 看外语视频的用户 |
| 📰 外文资讯读者 | 📑 需要读外文合同/报告的职场人 |
| 🧑‍🏫 教师与翻译从业者 | 🌍 出境旅行规划者 |
| 🎮 浏览国际游戏社区的玩家 | ✍️ 需要研究全球趋势的内容创作者 |

---

## 🔌 AI 提供商

| 提供商 | 默认模型 | 格式 |
|--------|----------|------|
| **解语**（默认） | DeepSeek V4 Flash | OpenAI |
| **DeepSeek** | deepseek-v4-flash | OpenAI |
| **OpenAI** | gpt-5.4-mini | OpenAI |
| **Anthropic** | claude-haiku-4-5 | Anthropic |
| **MiniMax** | MiniMax-M3 | Anthropic |
| **Gemini** | gemini-3.5-flash | OpenAI |
| **智谱 AI** | glm-4-flash | OpenAI |
| **Kimi** | kimi-k2.6 | OpenAI |
| **自定义** | 用户自定义 | OpenAI / Anthropic |

### 免费额度

| 用户类型 | 每日限额 |
|----------|----------|
| 游客 | 20 次 |
| 免费用户 | 100 次 |

---

## ⌨️ 键盘快捷键

| 快捷键 | 作用 |
|--------|------|
| `Alt + E` | 解释选中文本 |
| `Alt + T` | 翻译选中文本或整页 |
| `Alt + S` | 截图识别 |
| `Esc` | 关闭解释面板 |

可在 `chrome://extensions/shortcuts` 自定义任意快捷键。

---

## 🔐 隐私与安全

| | |
|:---:|:---|
| 💾 **本地存储** | API Key 仅保存在浏览器本地 |
| 🔒 **不收集数据** | 不上传任何用户数据到服务器 |
| 🔗 **直连提供商** | 使用自定义 AI 时，请求直接发往提供商，不经我们的服务器 |
| ⚔️ **最小权限** | 仅请求功能所需的最小权限 |

---

## ❓ 常见问题

<details>
<summary><strong>解语是免费的吗？</strong></summary>

扩展本身免费安装，内置免费 AI 额度（有每日限额）。也可以添加自己的 API Key，无限使用。
</details>

<details>
<summary><strong>不填 API Key 能用吗？</strong></summary>

可以。内置免费额度开箱即用，无需任何配置。
</details>

<details>
<summary><strong>如何获取 API Key？</strong></summary>

在对应 AI 提供商官网注册账号，在控制台或 API 管理页面创建 Key。例如：OpenAI（platform.openai.com）、Anthropic（console.anthropic.com）、MiniMax（platform.minimax.io）。
</details>

<details>
<summary><strong>为什么返回结果是空的？</strong></summary>

可能原因：1) API Key 不正确或已过期；2) 网络连接问题；3) 选中文本过短。请检查 API 设置中的 Key 是否正确，并点击「测试连接」。
</details>

<details>
<summary><strong>错误代码代表什么？</strong></summary>

- 401：API Key 无效
- 403：权限不足或未开通模型
- 429：请求过于频繁，稍后重试
- 500：AI 服务端问题
</details>

<details>
<summary><strong>支持哪些语言？</strong></summary>

支持底层 AI 模型能处理的所有语言，包括中文、英语、日语、韩语、西班牙语、法语、德语等。
</details>

<details>
<summary><strong>支持所有网站吗？</strong></summary>

支持大多数网站，chrome:// 等系统页面和部分受限域名除外。
</details>

<details>
<summary><strong>图片识别需要下载什么？</strong></summary>

使用 AI Vision 模型进行图片识别，无需下载额外文件。你可以为图片识别配置独立的 AI 模型，也可以使用支持 Vision 的主解释模型。
</details>

---

## 🚀 快速开始

```
1. 从最新 Release 下载 select-ai.zip
2. 解压 → 打开 Chrome → 访问 chrome://extensions/
3. 开启开发者模式 → 加载已解压的扩展程序
4. 在任意网页选中文字 → 点击悬浮 AI 按钮
```

也可以直接从 [Chrome 应用商店](https://chromewebstore.google.com/detail/select-ai-ai%E5%88%92%E8%AF%8D%E8%A7%A3%E9%87%8A/ehcjdmkcnjniaofflhghckpgmjmbgkjh) 安装。

---

## 📬 反馈

由 [EndlessGr1ef](https://github.com/EndlessGr1ef) 独立开发与维护。遇到 bug、有想法，或者只是想聊聊，欢迎提交 issue 或联系作者。

<div align="center">

⭐ 喜欢的话，点个 Star 支持

*Made with ❤️，让外文阅读更轻松*

</div>
