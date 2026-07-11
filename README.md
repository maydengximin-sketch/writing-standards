# Writing Standards Skill

一个面向 Codex / ChatGPT skill 的实用写作规范包，用于改写、审校和起草中文与英文的学术、分析型和 AI 辅助文本。

核心原则来自公开小红书笔记中提到的「不迂回立论 / No negative framing」：先说明事物是什么，再说明它不是什么。除非反面框架能真正帮助读者理解，否则不要用「不是……而是」或 `not X but rather Y` 作为默认立论方式。

## What It Helps With

- 直接立论，减少不必要的反面铺垫
- 优化论文、摘要、报告和分析文本的表达
- 清理常见 AI 写作痕迹
- 强化事实支撑与段落逻辑
- 保留必要限定，避免过度绝对化
- 中英文写作规范化与改写

## Skill Location

The Codex skill lives at:

```text
skills/writing-standards/
```

Key files:

- `skills/writing-standards/SKILL.md`
- `skills/writing-standards/references/source-notes.md`
- `skills/writing-standards/agents/openai.yaml`

## Example Prompt

```text
Use $writing-standards to revise this paragraph according to practical writing standards.
```

中文也可以这样用：

```text
用 $writing-standards 按写作规范帮我改写这段论文摘要，重点去掉不必要的“不是……而是”。
```

## Install

Copy `skills/writing-standards` into your Codex skills directory, for example:

```text
~/.codex/skills/writing-standards
```

Then restart or refresh Codex so the skill metadata can be discovered.

## License

MIT
