# agent-skills

开源 AI Agent Skills 集合。

## 项目结构

```text
agent-skills/
├── agents/          # Agent 定义
├── skills/          # Skill 实现（每个 skill 一个子目录）
├── templates/       # Agent / Skill 脚手架模板
├── docs/            # 架构与规范
├── examples/        # 示例
└── scripts/         # 辅助脚本
```

| 目录 | 用途 |
|------|------|
| `skills/` | Skill 实现，每个子目录一个 skill |
| `agents/` | Agent 定义 |
| `templates/` | 新建 skill / agent 时的模板 |
| `docs/` | 架构说明与贡献规范 |
| `examples/` | 用法示例 |
| `scripts/` | 仓库辅助脚本 |

## 安装

```bash
# 浏览可用 skills
npx skills add void-sleep/agent-skills --list

# 安装单个 skill
npx skills add void-sleep/agent-skills --skill <skill-name>

# 安装到用户全局目录（所有项目可用）
npx skills add void-sleep/agent-skills --global --skill <skill-name>

# 非交互式安装（CI / 脚本）
npx skills add void-sleep/agent-skills --skill <skill-name> -g -y
```

支持 **Claude Code**、**Codex**、**Cursor** 等主流 AI 编码助手。

## Skills 列表

暂无。新增 skill 后在此补充，按名称排序。

## 开发

```bash
# 要求：Node >= 26，pnpm 12
pnpm install
pnpm lint:md
```

## 贡献

[CONTRIBUTING.md](CONTRIBUTING.md)

## 相关资源

- [Claude Code 官方文档](https://docs.anthropic.com/en/docs/claude-code) — Claude Code 使用说明
- [Agent Skills 规范](https://agentskills.io/specification) — Skill 规范
- [Anthropic 官方 Skills](https://github.com/anthropics/skills) — 官方示例 skills
- [Superpowers](https://github.com/obra/superpowers) — 开源 skills 集合
- [Skills.sh](https://skills.sh/) — Skills 资源聚合站

## 贡献者

<a href="https://github.com/void-sleep/agent-skills/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=void-sleep/agent-skills" alt="贡献者头像" />
</a>

## 许可

[CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)
