# 本轮验证记录

日期：2026-09-10。检查对象为本次整理的展示副本，不是正在运行的生产目录。

| 对象 | 本轮结果 | 边界 |
|---|---|---|
| Sandrone QQ Bot | 193 项 pytest 测试通过，4.45 秒 | 使用模拟接口，未实发 QQ 消息或调用付费模型 |
| QQ Poker Bot | 29 项 unittest 测试通过，0.040 秒 | 本地逻辑和存储测试，不是平台联调 |
| Genshin Subtitle Translator | Python AST 解析通过；配置模板不含密钥 | 未启动游戏、UAC 或覆盖层，未实测 OCR 和翻译接口 |
| Sandrone Codex Pet | JSON 可解析，引用的 WebP 可读，1536 × 2288 | 未逐帧检查动作或重新验收应用加载 |
| 发布副本 | 白名单复制，排除运行配置、数据库、日志、缓存与虚拟环境；真实 QQ 标识已替换 | 补充的凭据特征扫描不能保证检测所有未知秘密 |
| Mon_Token / Mon_Foree | 核对现有仓库与项目说明，保留私有 | 未部署、未重新运行生产验收 |

聊天机器人使用独立 Python 3.13 环境，从展示目录设置 `PYTHONPATH=src` 后执行 `python -m pytest -q`；牌局机器人执行 `python -m unittest discover -s tests -q`。测试依赖安装在工作目录，未使用生产凭据。

尚未完成：独立项目 GitHub 仓库创建与源码推送（本机 GitHub CLI 未登录）。个人主页的项目总览、工程案例和验证记录已通过已连接插件发布。