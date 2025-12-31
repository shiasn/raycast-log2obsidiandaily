# Log 2 Obsidian Daily

向 Obsidian 日记中插入片段。

## 配置

- 在 Raycast 命令偏好里填入 Obsidian Vault 路径（根目录）。
- 命令会读取 Vault 下的 `.obsidian/daily-notes.json`，根据其中的 `folder` 和 `format` 计算当日的日记路径。`format` 支持 `YYYY`、`YY`、`MM/M`、`DD/D`，包含 `/` 时会生成多级文件夹（例如 `YYYY/MM/DD`）。
- 可设置插入的目标标题，默认 `## 临时便签`。
- 可配置记录模式：`Callout`（默认，引用块形式）或 `简洁文本`（格式为 `**HH:MM**` 换行后内容）。
