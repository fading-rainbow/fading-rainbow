# MonHamed 项目作品集

整理日期：2026-09-10。项目定位以现有源码为依据，验证情况见 VALIDATION.md。采用成熟开源组件构建应用，明确区分底层项目、定制工作与可验证成果。

| 项目 | 技术与展示重点 | 仓库 / 交付状态 |
|---|---|---|
| Mon_Token | Go、Vue、PostgreSQL、Redis；基于 Sub2API 的网关定制、计费与并发语义 | 已有私有仓库，保留私有；提供技术案例 |
| Mon_Foree / Mon_VPN | Go、Kotlin、WPF/.NET；客户端生命周期、权限隔离、故障恢复 | 已有私有仓库，保留私有；提供技术案例 |
| Genshin Subtitle Translator | Python、OCR、Windows 覆盖层；按需翻译与异步处理 | 本次整理脱敏源码 |
| Sandrone Codex Pet | WebP 精灵图、JSON 配置；宠物素材与打包 | 本次整理实际安装资源 |
| Sandrone QQ Bot | Python、SQLite、QQ SDK；记忆、任务取消、图片编辑与隔离 | 本次整理脱敏源码与测试 |
| QQ Poker Bot | Python、WebSocket、SQLite；牌局状态机、边池结算与消息去重 | 本次整理脱敏源码与测试 |
| Delta_God / Delta_see | AHK、Python；日志增量解码、状态重建与证据分级 | 已有公开 DeltaForce-Log-Reconstruction；原始抓包和日志不发布 |
| developer set | PowerShell；开发环境配置、验证与回退脚本 | 本机运维材料，需提炼为通用脚本后发布 |
| SVG 动画练习 | 单文件 HTML/SVG；动画、天气变化与交互 | 独立练习，辅助展示 |

## 现有公开作品

- [DeltaForce Log Reconstruction](https://github.com/fading-rainbow/DeltaForce-Log-Reconstruction)
- [muduo_study](https://github.com/fading-rainbow/muduo_study)
- [ClashRoyaleBuildABot](https://github.com/fading-rainbow/ClashRoyaleBuildABot)
- [deltaforce_map](https://github.com/fading-rainbow/deltaforce_map)
- [Fakerunstep](https://github.com/fading-rainbow/Fakerunstep)

后四项为 GitHub 已有仓库，本轮未审计实现与贡献，不添加未经核实的履历声明。

## 面试表达

优先介绍能现场解释并运行的两到三个项目：问题是什么、采用了哪些开源组件、自己做了哪些集成和修复、怎样测试、还有哪些限制。网关项目明确说明基于 Sub2API 二次开发；宠物按资源作品展示；AI 辅助开发经历据实说明，不把测试数量换算为业务规模或性能提升。