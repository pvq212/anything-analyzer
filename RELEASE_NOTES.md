# Anything Analyzer v3.3.3

## 新功能

- **追问对话持久化** — AI 分析报告的追问问答现在会保存到数据库，重启应用后自动恢复
  - 每个分析报告拥有独立的对话历史
  - 多次分析同一 Session 互不影响
  - 切换 Session 或重启后自动加载最新报告的完整对话

## 改进

- **LLM 超时时间延长** — 连接超时从 2 分钟延长至 10 分钟，避免慢速中转服务误报超时
  - 用户可随时通过取消按钮手动中止

## 下载

| 平台 | 文件 |
|------|------|
| Windows | `Anything-Analyzer-Setup-3.3.3.exe` |
| macOS (Apple Silicon) | `Anything-Analyzer-3.3.3-arm64.dmg` |
| macOS (Intel) | `Anything-Analyzer-3.3.3-x64.dmg` |
| Linux | `Anything-Analyzer-3.3.3.AppImage` |
