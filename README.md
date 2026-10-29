# Obsidian-translations

Obsidian 社区插件的中文译文仓库，由 [obsidian-i18n](https://github.com/obsidian-forged/i18n) 插件的「共建生态 / 云端发布」功能创建和维护。

*Chinese (zh-cn) translations for Obsidian community plugins, published with the obsidian-i18n plugin.*

## 这是什么

- 每个译文是一个 JSON 文件，按插件或主题存放：`plugins/<插件 ID>.json`、`themes/<主题 ID>.json`。
- 根目录的 `metadata.json` 是索引，列出已有译文（插件 ID、语言、更新时间），由 obsidian-i18n 发布时自动更新。
- 目前还没有发布任何译文（`metadata.json` 为空列表 `[]`）。

## 怎么使用

1. 在 Obsidian 里安装并启用社区插件 **obsidian-i18n**。
2. 打开 i18n 管理中心，进入「云端」视图，在「探索资源」里输入本仓库地址 `goldfishsnow/Obsidian-translations`，或在 设置 → I18N → 综合设置 → 云端仓库 填写该地址。
3. 选中需要的插件译文下载，再在管理中心里应用到对应插件。
4. 应用前建议先确认插件是否已原生支持中文，避免重复翻译；插件升级后译文可能需要重新应用。

## 发布译文（维护者）

在 设置 → I18N → 共建生态 填写 GitHub token 和本仓库名，然后在云端视图「管理中心」选择本地译文发布。发布会上传 `plugins/<id>.json` 或 `themes/<id>.json` 并更新 `metadata.json`。请不要手工改 `metadata.json` 的格式。

## 许可

本仓库的译文文本以 [MIT License](LICENSE) 发布。被翻译插件的名称、原文和代码版权归各插件作者所有；本仓库与 Obsidian 官方翻译仓库 obsidianmd/obsidian-translations 无关。
