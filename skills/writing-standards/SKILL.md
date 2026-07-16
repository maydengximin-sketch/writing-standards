---
name: writing-standards
description: Apply practical writing standards to draft, critique, or revise Chinese and English academic, analytical, and AI-assisted prose. Use when the user asks for 写作规范, 论文写作规范, academic writing rules, essay polishing, abstract writing, AI痕迹 cleanup, clearer argumentation, paragraph logic, factual support, concise rewriting, direct thesis framing, or removing unnecessary negative framing such as "不是……而是" / "not X but rather Y".
---

# 写作规范

## Core Principle

Make the writing direct, specific, verifiable, coherent, and appropriately restrained. Prefer a clear positive claim over rhetorical detours. Treat "不迂回立论 / No negative framing" as one core standard: state what the claim is before explaining what it is not.

Read `references/revision-playbook.md` when the task involves multi-paragraph revision, academic prose, abstracts, AI-writing cleanup, or the user wants an explanation of the standards applied. Read `references/source-notes.md` only when provenance from the original Xiaohongshu discussion is relevant.

## Task Router

- **Polish or rewrite**: preserve the user's meaning; improve directness, evidence, cohesion, rhythm, and register.
- **Diagnose writing**: return the highest-impact issues first, grouped by argument, evidence, structure, style, and AI texture.
- **Draft from notes**: build a claim-first structure before writing; mark missing evidence rather than inventing it.
- **Abstract writing**: use the four-sentence inverted-pyramid pattern unless the target venue requires a different structure.
- **AI trace cleanup**: reduce mechanical transitions, formulaic parallelism, empty intensifiers, and unsupported generalities while keeping the prose natural and precise.

## Revision Workflow

1. Identify the genre, audience, language, and expected formality.
2. Extract the central claim: actor, action, object, evidence, mechanism, and implication.
3. Put the positive claim first. Move caveats, contrasts, and limitations after the claim unless they are necessary to prevent misunderstanding.
4. Remove reflexive contrast frames such as "不是 X, 而是 Y", "并非 X, 而是 Y", "not X but rather Y", "rather than", and "instead of" when X is only a rhetorical warm-up.
5. Replace vague labels with concrete support from the user's material: examples, data, method context, observed cases, or causal mechanisms.
6. Improve paragraph logic by ordering sentences as claim -> support -> explanation -> implication.
7. Preserve accuracy. Do not invent citations, data, methods, findings, or examples. Use `[需要证据]` / `[evidence needed]` when support is missing.
8. Return the revised text first unless the user explicitly asks for diagnosis before rewriting.

## Non-Negotiable Standards

- Keep the user's intended meaning, field, and stance.
- Prefer concrete nouns and active verbs over abstract filler.
- Use qualifiers only when they improve accuracy.
- Avoid automatic connector chains such as "首先 / 其次 / 然后 / 综上所述" unless the genre expects them.
- Avoid over-polishing into generic, prestige-sounding prose.
- Keep necessary negative contrast for rebuttal, misconception correction, legal or technical qualification, dialectical argument, literature-gap positioning, or cases where the contrast itself is the evidence.

## Output Contracts

For most revisions:

```text
Revised:
...

What changed:
- ...
```

For diagnosis:

```text
Top issues:
1. ...

Revision priorities:
1. ...
```

For final-only requests, output only the revised text.

For uncertain claims, preserve the claim but flag the uncertainty inline with `[需要证据]` or briefly under `Notes:`.
