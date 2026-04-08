# Product Manager Skill

一个面向 Vibe Coding 时代的产品经理全栈技能包，覆盖从 PRD 撰写、Agent 工作流编排、架构决策、安全审计、风险评估、技术债管理，到上线发布与商业化变现的完整闭环。

这个 skill 适合：

- 想用 AI 工具快速做 MVP 的产品经理
- 正在做独立产品、Micro SaaS、AI 产品的创业者
- 需要把“想法 -> PRD -> 实现 -> 上线 -> 收费”串成一套流程的人
- 非技术背景，但正在用 Cursor、Codex、Claude Code、Replit、Bolt、Lovable 等工具做产品的人

## 解决什么问题

在 AI 能大幅提升开发速度之后，真正稀缺的不是“把东西做出来”，而是：

- 想清楚做什么
- 用正确的方式让 AI 落地
- 避免把安全、数据、权限和技术债问题一起带进生产
- 尽早验证付费意愿和商业化路径

这个 skill 的目标，是让产品经理在享受 Vibe Coding 速度的同时，仍然能保持产品、工程和商业上的判断力。

## 覆盖内容

- AI-Native PRD 写法
- Agent 工作流编排
- 安全检查与上线门禁
- 数据架构与技术选型
- 技术债识别与管理
- 风险评估与预警
- 商业化、定价、单位经济学与增长飞轮
- 极简创业与“先手动交付，再产品化”的方法论

## 仓库结构

```text
.
├── SKILL.md
└── references/
    ├── architecture-patterns.md
    ├── minimalist-entrepreneur.md
    ├── monetization-playbook.md
    ├── prd-template.md
    ├── risk-framework.md
    └── security-checklist.md
```

## 文件说明

- [`SKILL.md`](./SKILL.md)：主技能文件，定义触发场景、核心方法论和完整执行框架
- [`references/prd-template.md`](./references/prd-template.md)：AI-Native PRD 模板
- [`references/architecture-patterns.md`](./references/architecture-patterns.md)：架构决策与技术选型指南
- [`references/security-checklist.md`](./references/security-checklist.md)：开发、集成、上线阶段的安全检查清单
- [`references/risk-framework.md`](./references/risk-framework.md)：风险评估、预警与升级判断框架
- [`references/monetization-playbook.md`](./references/monetization-playbook.md)：商业化、定价、收入模型与增长机制
- [`references/minimalist-entrepreneur.md`](./references/minimalist-entrepreneur.md)：极简创业方法论与前 100 个客户路径

## 如何使用

如果你想把它作为 Codex skill 使用，保持当前目录结构不变即可。仓库根目录就是 skill 根目录。

典型触发场景包括：

- “帮我写个 PRD”
- “这个功能怎么设计”
- “我想做个 AI 产品，先做什么”
- “这个架构有没有问题”
- “上线前我该检查什么”
- “这个产品怎么收费”
- “怎么找到第一批付费用户”

## 核心思路

这个 skill 的底层逻辑可以概括为两句话：

1. 先验证问题和付费意愿，再让 AI 帮你放大效率。
2. 先把 PRD、权限、安全、数据和发布门禁想清楚，再去追求开发速度。

## 适合搭配的工作方式

- 用 `SKILL.md` 先做整体规划和风险识别
- 在需求细化时复用 `prd-template.md`
- 在架构选型时查阅 `architecture-patterns.md`
- 在开发和上线前跑 `security-checklist.md`
- 在评估是否该继续推进、降级或升级时参考 `risk-framework.md`
- 在准备收费、订阅和增长策略时使用 `monetization-playbook.md`

## License

当前仓库未附带单独许可证。如需开源复用规则，建议补充 `LICENSE` 文件。
