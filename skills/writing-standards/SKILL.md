---
name: writing-standards
description: Apply practical writing standards to draft, critique, or revise Chinese and English academic, analytical, and AI-assisted prose. Use when the user asks for 写作规范, 论文写作规范, academic writing rules, essay polishing, AI痕迹 cleanup, clearer argumentation, direct thesis framing, abstract structure, factual support, paragraph logic, or removing unnecessary negative framing such as "不是……而是" / "not X but rather Y".
---

# 写作规范

## Core Standards

Make the writing direct, specific, verifiable, and appropriately restrained. Treat "不迂回立论 / No negative framing" as one core rule: state what the claim is before explaining what it is not.

Read `references/source-notes.md` when the task involves academic prose, abstracts, AI-writing cleanup, or the user wants the rules behind the revision.

## Workflow

1. Identify the user's target genre, audience, and register: academic paper, abstract, essay, report, proposal, note, or general explanation.
2. Extract the positive claim: actor, action, object, mechanism, evidence, and implication.
3. Remove reflexive contrast frames such as "不是 X, 而是 Y", "并非 X, 而是 Y", "not X but rather Y", "rather than", and "instead of" when X is only a rhetorical warm-up.
4. Put the claim first. Preserve necessary caveats as later qualifiers, not as the opening move.
5. Replace broad labels with concrete evidence, examples, data, methods, or observed context when the original sounds generic.
6. Improve paragraph logic without changing the user's core meaning: reorder claims, smooth transitions, and remove mechanical repetition.
7. Keep claims verifiable. Do not invent citations, data, methods, or examples; mark missing evidence as a placeholder when needed.
8. Output the revised text first. Add a brief note only when it helps the user learn the standard applied.

## Standards Checklist

- Direct argument: begin with the claim, not a negated detour.
- Evidence support: include facts, examples, data, methods, or concrete observations when available.
- Accurate restraint: use qualifiers only when they improve precision.
- Natural cohesion: avoid automatic connector chains such as "首先 / 其次 / 然后 / 综上所述" unless they fit the genre.
- Human-readable rhythm: mix sentence structures for clarity, not for artificial imperfection.
- Field fit: preserve the user's discipline, terminology, and intended level of formality.

## Rewrite Patterns

Use these transformations as defaults:

- `不是 A, 而是 B` -> `B ...`
- `This is not A, but rather B` -> `This is B ...`
- `The study does not merely X; it Y` -> `The study Y by/through ...`
- `Rather than emphasizing X, this paper focuses on Y` -> `This paper focuses on Y ...`
- `It is important to note that this is not ...` -> delete unless the warning prevents a real misread.

Keep negative contrast when the user is writing rebuttal, legal/technical qualification, misconception correction, dialectical theory, literature-gap positioning, or a sentence where the contrast itself is the evidence.

## Output Style

When editing, return:

1. `Revised:` the polished version.
2. `What changed:` one to three concise bullets, unless the user asks for only the final text.

When drafting abstracts, prefer a four-sentence structure:

1. Background plus knowledge gap.
2. What the work did.
3. Core finding in the clearest possible form.
4. Why the finding matters.
