# GeniusBotsLab — 智能体系统与可靠的 AI 自动化

**面向可控、可衡量业务流程的 AI 自动化工程师。**

我设计 AI 系统，让专业智能体通过明确的任务交接、权限、预算、日志，以及对重要操作的人类审批，完成调研、规划、执行、审查、验证和报告。

[English](en.md) · [Русский](ru.md) · [Română](ro.md) · [简体中文](zh-CN.md) · [עברית](he.md) · [Français](fr.md) · [Deutsch](de.md) · [Español](es.md) · [Português (Brasil)](pt-BR.md) · [日本語](ja.md) · [العربية](ar.md) · [Українська](uk.md)

---

## 能力

- **多智能体编排** — 调研员、分析师、规划员、执行者、审查员、验证员和报告角色，职责明确。
- **长时工作流** — 状态、队列、排期、检查点、重试、超时、告警、审计日志和审批关卡。
- **AI 辅助软件交付** — Claude、Claude Code 和 ChatGPT 协助调研、实现、审查、测试设计与文档；架构、安全、验证、发布和决策责任由人承担。
- **获授权的社交与媒体工作流** — 经批准的发布、评论审核与回复、内容规划、图像/视频/语音流水线、报告及内部运营。

## 工程实践

```text
流程审计 → 试点指标 → 角色与访问权限 → 构建 → 测试与 QA → 受控发布 → 监控成本、质量和错误 → 改进
```

在适用的情况下，单元测试、集成测试和端到端测试是必需的，CI 运行约定的自动检查。对结构化输入和输出进行验证；含糊或高影响的结果交由人工审核。

### 模型、RAG 与可靠性

- 按任务复杂度、质量要求和成本选择模型。
- 控制上下文，缓存可复用结果，并设置 token 与操作预算。
- 在需要基于资料检索时使用 RAG 和有状态工作流。
- 通过可观测性、权限、交付状态、重试/回退路径和已文档化的故障处理来运行系统。

## 技术栈

**AI 与智能体：** Claude · Claude Code · ChatGPT · OpenAI 兼容 API · 基于角色的智能体 · 工具调用 · RAG

**工程：** Python · TypeScript / JavaScript · SQL · REST API · Webhook · Docker · Git/GitHub · CI · 自动化测试 · 数据库 · 队列 · 监控

**自动化与媒体：** 合规的浏览器/API 集成 · Telegram Bot API · ElevenLabs · 面向文本、图像、视频和语音的 AI 流水线

## 精选公开项目

- [**Social Media Crossposter**](https://github.com/GeniusBotsLab/social-crossposter-comment-module) — 通过允许的集成向获授权账户和频道发布文本、图像与视频的工作区。
- [**Swarm Agent Coordinator**](https://github.com/GeniusBotsLab/swarm-agent-coordinator) — 用于智能体团队、任务、角色和工作空间的自托管协调系统。
- [**TextFix**](https://github.com/GeniusBotsLab/textfix) — 通过 OpenAI 兼容 API 进行 AI 辅助文本校正的 Windows 工具。
- [**NeuroMedia Marketplace**](https://github.com/GeniusBotsLab/neuromedia-marketplace) — 公开的多语言 AI Marketplace 展示与安全目录同步。
- [**Self-Correcting Link Parser**](https://github.com/GeniusBotsLab/self-correcting-link-parser) — 用于合规研究工作流的公开链接收集、规范化和质量控制。

## 负责任的自动化

我仅使用经授权的账户、数据和集成，并取得所有者同意且遵守平台规则。我**不会**构建或运行垃圾信息、虚假身份、人为互动量、绕过平台规则、绕过 CAPTCHA 或反欺诈机制，或未经授权的访问。本文不对大规模注册账户作任何声明。

## 联系方式

- **邮箱：** [BotsLab@proton.me](mailto:BotsLab@proton.me)
- **Telegram：** [@TheBotsLab](https://t.me/TheBotsLab)

---

<sub>仅为公开职业作品集。不含凭证、客户数据、私有基础设施或未发布材料。量化和生产环境声明仅在有允许公开的工件或匿名证据支持时发布。</sub>
