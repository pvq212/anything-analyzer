# Anything Analyzer v3.3.6

## Bug 修复

- **修复追问时 FOREIGN KEY 约束错误** — AI Report 追问期间，若用户切换或删除 Session，LLM 响应后持久化消息会因 report 被级联删除而报错 `SqliteError: FOREIGN KEY constraint failed`。现在通过 `activeChatReports` 机制保护正在追问的 report 不被删除，确保追问消息正常持久化

## 下载

| 平台 | 文件 |
|------|------|
| Windows | `Anything-Analyzer-Setup-3.3.6.exe` |
| macOS (Apple Silicon) | `Anything-Analyzer-3.3.6-arm64.dmg` |
| macOS (Intel) | `Anything-Analyzer-3.3.6-x64.dmg` |
| Linux | `Anything-Analyzer-3.3.6.AppImage` |
