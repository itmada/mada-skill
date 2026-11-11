# mada-skill

个人 Skill 合集，适用于各类支持 skill 机制的 AI 助手。

## Skill 列表

| Skill | 说明 |
|---|---|
| [requirement-workflow](requirement-workflow/SKILL.md) | 需求开发协作流程：接到新需求后，和助手逐块讨论并写定需求开发文档（目标与范围、设计决策、涉及改动、验收标准），定稿后按指令实现，完成后整体验收。 |

## 安装

把需要的 skill 目录复制到你所用工具配置的 skills 目录：

```bash
git clone https://github.com/itmada/mada-skill.git
cp -r mada-skill/requirement-workflow <你的 skills 目录>/
```

安装后通过 `/requirement-workflow` 手动调用，具体调用方式以所用工具的文档为准。

## 目录结构

```
mada-skill/
└── requirement-workflow/
    └── SKILL.md
```

## 格式说明

每个 skill 是一个独立目录，内含 `SKILL.md`：开头为 `name`、`description` 等字段的元数据，正文为完整的操作说明。可按所用工具的约定调整元数据字段，正文内容通用。
