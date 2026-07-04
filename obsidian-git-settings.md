# Obsidian Git 插件设置指南

## Automatic（自动化）

| 界面英文                                       | 中文            | 建议值                         |
| ------------------------------------------ | ------------- | --------------------------- |
| Split timers for automatic commit and sync | 拆分自动提交和同步的计时器 | 不开启（OFF）                    |
| Auto commit interval (minutes)             | 自动提交间隔（分钟）    | `10`                        |
| Auto commit after stopping file edits      | 停止编辑后自动提交     | 开启（ON）                      |
| Auto push interval (minutes)               | 自动推送间隔（分钟）    | `10`                        |
| Auto pull interval (minutes)               | 自动拉取间隔（分钟）    | `10`                        |
| Commit message on auto commit              | 自动提交信息模板      | 默认 `vault backup: {{date}}` |

> 不开启 Split timers 时，commit 和 push 共用一个间隔，到点自动 commit → pull → push 一条龙。
> 开启后可以设置不同的 commit 和 push 间隔（如每 5 分钟 commit，每 30 分钟 push）。

## Pull（拉取）

| 界面英文 | 中文 | 建议值 |
|---------|------|--------|
| Pull on startup | 启动时自动拉取 | 开启（ON） |

## Commit-and-sync（提交并同步）

| 界面英文 | 中文 | 建议值 |
|---------|------|--------|
| Push on commit-and-sync | 手动提交时一并推送 | 开启（ON） |
| Pull on commit-and-sync | 手动提交时一并拉取 | 开启（ON） |

## Hunk management（代码块管理）

| 界面英文 | 中文 | 建议值 |
|---------|------|--------|
| Status bar with summary of line changes | 状态栏显示行变更摘要 | `Colored`（彩色） |

> 选项：Disabled（禁用）/ Colored（彩色）/ Monochrome（单色）

## Miscellaneous（杂项）

| 界面英文 | 中文 | 建议值 |
|---------|------|--------|
| Show status bar | 显示状态栏 | 开启（ON） |
| Show branch status bar | 显示分支状态栏 | 开启（ON） |

---

> 设置路径：Obsidian → 设置 → 第三方插件 → Obsidian Git（齿轮图标）
>
> 重启 Obsidian 后状态栏设置才会生效。
