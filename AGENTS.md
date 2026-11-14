# AGENTS.md

## 原则

1. **可验证输出** — 产出内容必须是可审查的（文本、diff、建议）

## 规则

- 功能重复时扩展已有 skill，不新建
- Skills 在 `skills/<name>/SKILL.md`，Agents 在 `agents/<name>/AGENT.md`
- Markdown 遵循 [docs/guidelines/markdown-spec.md](docs/guidelines/markdown-spec.md)
- 新建 skill 遵循 [docs/guidelines/skill-spec.md](docs/guidelines/skill-spec.md)
- Git 操作遵循 [docs/guidelines/git-workflow.md](docs/guidelines/git-workflow.md)
- 工具链：Node >= 26，pnpm 12
