# Changelog / 更新日志

Notable user-facing changes to Select AI are recorded here. For installation packages and complete release notes, see [GitHub Releases](https://github.com/EndlessGr1ef/select_ai/releases).

这里记录解语面向用户的重要更新。安装包与完整发布说明请前往 [GitHub Releases](https://github.com/EndlessGr1ef/select_ai/releases) 查看。

## [v0.18.0] - 2026-08-22

### Added / 新增

- YouTube bilingual subtitles can now be exported as dual-language SRT files or a plain-text transcript. / YouTube 双语字幕支持导出，可下载双语对照的 SRT 字幕文件或纯文本文稿。
- The extension now shows a one-time update notice after each update, with a link to the website changelog; future notices can be turned off. / 新增版本更新提示，扩展更新后自动展示本次更新内容，可一键查看官网更新日志，也能关闭后续提醒。

## [v0.16.1] - 2026-07-26

### Fixed / 修复

- Bilingual Translation and YouTube Bilingual Subtitles now show clearer error messages in your output language. / 对照翻译和 YouTube 双语字幕的错误提示会随输出语言显示，提示更清晰易懂。
- When the daily request limit is reached, next steps are tailored to your account status. / 用完每日额度时，会根据账号状态提供更合适的下一步操作。
- Bilingual Translation no longer briefly shows streamed content identical to the original. / 对照翻译不再短暂显示与原文相同的流式内容，阅读更连贯。
- YouTube Bilingual Subtitles stop retrying after the daily request limit is reached, avoiding repeated notices. / YouTube 双语字幕在每日额度用完后会停止重复请求，避免反复弹出提示。

## [v0.16.0] - 2026-07-23

### Added / 新增

- Bilingual Translation now processes long pages in parallel. / 对照翻译会自动并行处理长页面。
- YouTube Bilingual Subtitles now support Shorts and embedded players. / YouTube 双语字幕现已支持 Shorts 和嵌入式播放器。
- Image Recognition now supports the free MiMo Vision model and auto-configures vision-capable selections. / 图片识别支持免费 MiMo Vision 模型，并在选择支持图片理解的模型时自动完成配置。
- Image Recognition explanations now separate long source text from the explanation, with side-by-side source and translation columns. / 图片识别解释不再重复堆叠长篇原文，原文与译文支持左右对照显示。
- Select AI branding and extension icons have been refreshed for clearer display at small sizes. / 解语品牌 Logo 与扩展图标完成更新，小尺寸场景显示更清晰。
- Selection Explain floating button and settings interactions are smoother and easier to control. / 划词解释的浮动按钮和设置交互更顺畅，拖动、展开与收起更容易控制。

### Improved / 改进

- Bilingual Translation now uses model-specific output limits for more reliable long results. / 对照翻译按模型使用独立输出上限，长内容结果更稳定。
- YouTube Bilingual Subtitles keep the correct font size in windowed playback. / YouTube 双语字幕在窗口化播放时保持正确字号。
- The website About page and product introduction have been refreshed. / 官网 About 页面与产品介绍内容完成更新。

## [v0.15.5] - 2026-07-14

### Improved / 改进

- YouTube subtitles now load and display more reliably, with less flicker during playback and switching. / 提升 YouTube 字幕加载与显示稳定性，减少播放和切换字幕时的闪烁。
- Added a Microsoft Edge Add-ons store entry to the installation guide. / 安装指南新增 Microsoft Edge Add-ons 商店入口。

## [v0.15.2] - 2026-07-09

### Added / 新增

- Added a bilingual translation shortcut to the extension popup. / 弹窗新增对照翻译快捷入口。
- Added a Firefox Add-ons installation entry to the website. / 官网新增 Firefox Add-ons 商店安装入口。

### Improved / 改进

- DeepSeek requests now use the official API for improved reliability. / DeepSeek 请求改用官方 API，提升稳定性。

### Fixed / 修复

- Fixed duplicate content in bilingual translation results. / 修复对照翻译结果中出现重复内容的问题。
- Fixed permission validation for DeepSeek Pro models. / 修复 DeepSeek Pro 模型权限校验问题。

## [v0.15.1] - 2026-07-04

### Added / 新增

- Added per-provider API concurrency settings. / 新增按 AI 提供商配置的 API 并发数量设置。
- Added replacement translation mode alongside bilingual translation. / 翻译新增替换原文模式，并保留对照翻译模式。

### Fixed / 修复

- Fixed an unrelated layout filter appearing in selection explanation settings. / 修复划词解释设置中误显示布局过滤器的问题。
- Hid API concurrency settings where they do not apply to the built-in free provider. / 免费内置 AI 不再显示不适用的 API 并发数量设置。

[v0.16.0]: https://github.com/EndlessGr1ef/select_ai/releases/tag/v0.16.0
[v0.16.1]: https://github.com/EndlessGr1ef/select_ai/releases/tag/v0.16.1
[v0.15.5]: https://github.com/EndlessGr1ef/select_ai/releases/tag/v0.15.5
[v0.15.2]: https://github.com/EndlessGr1ef/select_ai/releases/tag/v0.15.2
[v0.15.1]: https://github.com/EndlessGr1ef/select_ai/releases/tag/v0.15.1
