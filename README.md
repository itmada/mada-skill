# mada-skill

个人 Claude Code Skill 合集。

## Skill 列表

| Skill | 说明 |
|---|---|
| [requirement-workflow](requirement-workflow/SKILL.md) | 需求开发协作流程：接到新需求后，和 Claude 逐块讨论并写定需求开发文档（目标与范围、设计决策、涉及改动、验收标准），定稿后按指令实现，完成后整体验收。 |

## 安装

把需要的 skill 目录复制到 Claude Code 的 skills 目录（`~/.claude/skills/`）：

```bash
git clone https://github.com/itmada/mada-skill.git
cp -r mada-skill/requirement-workflow ~/.claude/skills/
```

安装后在 Claude Code 中通过 `/requirement-workflow` 手动调用。

## 目录结构

```
mada-skill/
└── requirement-workflow/
    └── SKILL.md
```
