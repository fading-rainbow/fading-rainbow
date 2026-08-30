# MonHamed

软件工程本科生 · 游戏客户端 / Windows 工具 / 跨平台网络客户端

> 关注客户端生命周期、日志可观测性、状态机与工程可靠性。习惯把非结构化输入还原为可验证状态，再用回放、测试和真实运行证据完成闭环。

## Featured work

### [DeltaForce.log 实时分析工具](https://github.com/fading-rainbow/DeltaForce-Log-Reconstruction)

**AutoHotkey v1 · Windows File API · XOR/UTF-8 · Regex · State Machine**

- 面向本地客户端日志的只读分析与工程验证工具，不读取进程内存、不注入游戏、不修改网络协议。
- 发现并实现逐字节 `0x5C` XOR 增量解码，处理共享只读 I/O、UTF-8 半行缓存、日志截断/重建与启动时回扫。
- 以 UID 关联开局名单、队伍、倒地/死亡、救援、盒子、撤离和结算等乱序事件，输出候选剩余人数、分类列表和可审计时间线。
- 对直接事实、跨行关联、超时推定、历史参考位置与未知信息分级标注，避免把弱证据包装成确定结论。

### [Mon_Foree 网络客户端与控制平台](https://www.542576.xyz/)

**C#/.NET 8/WPF · Windows Service/IPC · Wintun/WFP · Kotlin/VpnService · Go/Linux**

- 设计 Windows GUI 与 LocalSystem Service 的权限边界，通过受限 named-pipe IPC 隔离普通界面和高权限操作。
- 实现 DPAPI/CNG 会话保护、连接状态机、Wintun 虚拟网卡接入，以及 WFP/路由/DNS 的 fail-closed 清理。
- 围绕驱动、核心进程、端口和网卡建立分阶段诊断、资源租约、幂等清理、恢复任务与发布验证。

### [Mon_Token 多模型 AI API 网关](https://token.542576.xyz/)

**Go/Gin · Vue 3/TypeScript · PostgreSQL · Redis · Docker Compose**

- 基于成熟开源项目二次开发，梳理请求、映射、上游、计费与失败回退语义。
- 处理粘性会话、并发/RPM、429 冷却、邮件链路和低资源 VPS 上的健康检查、备份与可回滚发布。

## AI-assisted engineering

日常使用 Codex（GPT-5.6 sol/luna 等）、GitHub Copilot 和其他代码模型完成需求拆解、仓库级阅读、跨语言修改、测试补齐、代码审查与发布验证；最终以源码、测试和真实运行证据做工程判断。

## Technical focus

- **Languages:** C++ / STL · Go · C#/.NET · Kotlin · AutoHotkey · TypeScript/Vue
- **Client & systems:** Windows File API · WPF · Windows Service · named-pipe IPC · Android VpnService · Wintun/WFP · Linux/systemd
- **Engineering:** state machines · asynchronous event correlation · replay-based testing · fault recovery · evidence-driven debugging

## Links

- [DeltaForce log reconstruction](https://github.com/fading-rainbow/DeltaForce-Log-Reconstruction)
- [个人作品与项目主页](https://www.542576.xyz/)
- [Codeforces](https://codeforces.com/profile/MonHamed)

---

作品内容经过脱敏，重点展示客户端工程、状态建模、可靠性与验证能力。
