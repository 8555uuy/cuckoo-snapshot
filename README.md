# 工作快照（Cuckoo Code 插件）

工作快照的**管理界面**：创建、恢复、删除。数据与 AI 的 `createSnapshot` 工具共享。

## 安装

在 Cuckoo Code 的「插件市场」搜索 **工作快照**，一键安装。

## 功能

- **创建**：把当前项目文件存一份（排除 .git/node_modules）
- **恢复**：一键回到某个快照（覆盖同名文件，破坏性操作前会确认）
- **删除**：清理旧快照
- **与 AI 共享**：界面建的，AI 能列出/恢复；AI 建的，界面立刻出现

## 数据位置

`~/.cuckoo/snapshots/`

## 依赖

需要 Cuckoo Code ≥ 0.8.8（提供 `shellAPI.listSnapshots` 等 IPC）。

## 许可证

MIT
