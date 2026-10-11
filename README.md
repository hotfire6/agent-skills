# Agent Skills

个人技能库，保存可以在支持 Agent Skills 的 AI 工具之间复用的技能。

## 已收录技能

| 技能 | 用途 | 原始来源 |
| --- | --- | --- |
| [find-skills](skills/find-skills/SKILL.md) | 根据任务寻找和安装相关技能 | [Vercel Labs](https://github.com/vercel-labs/skills/tree/main/skills/find-skills) |

## 安装

本仓库位于 `hotfire6/agent-skills`，是公开仓库。支持 Agent Skills 的工具可以使用以下命令安装：

```bash
npx skills add hotfire6/agent-skills --skill find-skills -g -y
```

需要 Node.js / npm 和网络连接。也可以先克隆仓库，再从本地安装：

```bash
git clone https://github.com/hotfire6/agent-skills.git
npx skills add ./agent-skills --skill find-skills -g -y
```

没有技能安装器的 AI 工具，可以手动导入完整技能文件夹，或显式让 agent 阅读对应的 `SKILL.md`。是否自动触发取决于目标工具对技能的支持。

## 后续添加技能

每个技能放在 `skills/<技能名称>/` 目录中，至少包含 `SKILL.md`。保留原作者许可证，注明来源，并在上表登记用途。

## 许可证

每个技能遵循自己的许可证。`find-skills` 使用 MIT 许可证，完整许可文本位于 [skills/find-skills/LICENSE](skills/find-skills/LICENSE)。

这里保存的是技能快照，不会自动跟随上游更新。

