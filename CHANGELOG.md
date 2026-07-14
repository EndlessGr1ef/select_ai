# Changelog / 更新日志

Notable user-facing changes to Select AI are recorded here. For installation packages and complete release notes, see [GitHub Releases](https://github.com/EndlessGr1ef/select_ai/releases).

这里记录解语面向用户的重要更新。安装包与完整发布说明请前往 [GitHub Releases](https://github.com/EndlessGr1ef/select_ai/releases) 查看。

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

[v0.15.5]: https://github.com/EndlessGr1ef/select_ai/releases/tag/v0.15.5
[v0.15.2]: https://github.com/EndlessGr1ef/select_ai/releases/tag/v0.15.2
[v0.15.1]: https://github.com/EndlessGr1ef/select_ai/releases/tag/v0.15.1
