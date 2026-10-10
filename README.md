
# RoleTrace

**Character Decision & Identity Engine**

让每个虚构角色拥有自己的判断逻辑。

RoleTrace is an Agent Skill for developing
distinct, believable, and consistent fictional characters.

RoleTrace 是面向小说、剧本、互动叙事及 AI 漫剧的
角色决策与人格一致性编辑 Skill。

## What It Does / 核心功能

- Character Decision Simulation — 角色决策模拟
- Voice Collision Detection — 声纹碰撞检测
- Character Drift Audit — 人物失真审计
- Dialogue Refinement — 人物对白润色
- Emotional Continuity — 情绪连续性审查
- Author Voice Preservation — 作者文风保护
- Self-Review Loop — 编辑结果自我复核

## Installation / 安装

Requires an Agent Skills-compatible client.

```bash
npx skills add lsk980210/roletrace
```

Replace YOUR_USERNAME with the repository owner's
GitHub username.

## Quick Start / 快速使用

### 角色诊断

使用 RoleTrace 的 AUDIT 模式，
分析下面这段小说的人物行为与对白。
指出有证据的问题，不要强制修改正常文本。

### 角色决策模拟

使用 RoleTrace 的 DECIDE 模式。

根据以下角色设定与场景条件，
分别模拟每个人物可能采取的行动。
不要预设所有人都会服从主角的计划。

### 人物润色

使用 RoleTrace 的 REWRITE 模式。

保留原剧情、人物关系和作者文风。
重点改善人物行为、情绪和语言差异。
完成后执行角色互换测试与自我复核。

### 建立角色档案

使用 RoleTrace 的 VOICEPRINT 模式，
依据已确认的角色设定建立声纹与行为档案。

## Design Philosophy

Characters should not exist merely to deliver
information or push the plot forward.

Their decisions should emerge from:
- What they know
- What they want
- What they fear
- What they believe
- What they can realistically do

The author remains in control of the story.

## Compatibility

Designed around the open Agent Skills specification.

Expected to work with compatible coding agents,
subject to each client's skill-loading behavior.

This project has no external API requirement,
no executable scripts, and no telemetry.

## Current Limitations

Version 0.1.0 is experimental.

RoleTrace does not:
- Train a new AI model
- Give characters actual consciousness
- Automatically remember an entire novel
- Guarantee better literary quality
- Guarantee detection-free AI writing

Long-form analysis requires accessible source
chapters and character reference documents.

## Testing

See tests/dialogue-test.md for a reproducible
character differentiation test.

## Privacy

Do not publish private manuscripts or
character reference documents without permission.

## License

MIT License.

## Project Status

v0.1.0 — Initial experimental release.

Feedback and test cases are welcome.
