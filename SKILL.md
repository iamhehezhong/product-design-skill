---
name: product-design
description: Create product interaction designs and review product design artifacts such as documents, screenshots, prototypes, and HTML against the user's design principles.
---

# Product Design

Use this skill when the user asks for product design, interaction innovation, UX review, UI/UX critique, product prototype feedback, AI product interaction design, design rationality checks, or improvement suggestions for design artifacts.

The governing principle is: **少用脑、少用手、少用眼**. Product design should reduce cognitive effort, input effort, and visual scanning effort while preserving user control, aesthetics, and humanity.

## Required Priority

Always read [references/01-basic-principles.md](references/01-basic-principles.md) before making product design judgments. These basic principles override generic trends, industry habits, and fashionable visual patterns.

When using theory, translate it into concrete product decisions. Do not merely name theories. Explain how a recommendation helps the product become easier to understand, easier to operate, easier to scan, more controllable, more aesthetic, or more humane.

## Task Routing

For creating a product design output:

- Read [references/03-input-inventory.md](references/03-input-inventory.md) to identify needed inputs and gaps.
- Read [references/02-classic-theories.md](references/02-classic-theories.md) when the design needs theoretical grounding.
- Read [references/13-nudge.md](references/13-nudge.md) when the design involves defaults, recommendations, choices, pricing, onboarding, reminders, behavior change, conversion, retention, or decision guidance.
- Read [references/04-interaction-visual-aesthetics.md](references/04-interaction-visual-aesthetics.md) when choosing flows, components, interaction patterns, layout, visual hierarchy, aesthetic direction, mobile experience, Apple/iOS style, or App design quality.
- 当产品类型匹配 AI 生成、工作台、管理后台、创作工具、计费、上传转化、内容或效率工具等常见模式时，读取 [references/06-product-type-patterns.md](references/06-product-type-patterns.md)。
- Read [references/05-ai-product-interaction.md](references/05-ai-product-interaction.md) when the product includes AI, agents, automation, generation, analysis, recommendation, or conversational interfaces.
- 当用户需要结构化交付物、设计评审、页面诊断、线框图、交互原型、组件清单或 HTML 原型时，读取 [references/09-design-output-templates.md](references/09-design-output-templates.md)。
- 在完成较完整设计输出前，读取 [references/10-post-generation-self-check.md](references/10-post-generation-self-check.md)，用于自检并修正明显问题。

For reviewing imported or existing design artifacts:

- Inspect the artifact first. For text documents, read the relevant content. For HTML, inspect structure, CSS, interaction states, and if feasible render or screenshot it. For images/screenshots, visually inspect the actual image.
- Read [references/07-design-review-checklists.md](references/07-design-review-checklists.md) and apply the review checklist.
- 当用户询问设计是否优秀、需要比较多个版本，或需要可量化评分时，读取 [references/08-design-scoring-system.md](references/08-design-scoring-system.md)。
- Read [references/13-nudge.md](references/13-nudge.md) if the artifact contains defaults, ranking, recommendations, upgrade paths, cancellation, onboarding, pricing, consent, or any choice architecture.
- Read [references/05-ai-product-interaction.md](references/05-ai-product-interaction.md) if the artifact contains AI behavior or AI-generated outputs.
- 当评审对象涉及流程、组件、页面层级、视觉风格、美学、人性、移动端、App、iOS、Apple 美学或 HIG 质量标准时，读取 [references/04-interaction-visual-aesthetics.md](references/04-interaction-visual-aesthetics.md)。
- Use [references/09-design-output-templates.md](references/09-design-output-templates.md) for the review format when useful.

For collecting or expanding examples:

- Use [references/11-case-library-template.md](references/11-case-library-template.md) to record positive cases, negative cases, industry samples, and design red lines.
- 当设计需要案例方向、成熟案例参照，或需要判断交互方案是否达到优秀标准时，使用 [references/12-excellent-case-library.md](references/12-excellent-case-library.md)。

## Design Output Requirements

When producing a design proposal, include the following if relevant:

- User scenario and core task.
- Human insight: what the user wants to save, avoid, understand, or control.
- Core path and key screens.
- Interaction design: inputs, defaults, feedback, state transitions, recovery, and shortcuts.
- Visual hierarchy and aesthetic direction.
- How the proposal reduces brain, hand, and eye burden.
- Risks, tradeoffs, and simpler alternatives.
- Validation method or success indicators.

对于较完整的设计输出，完成前应根据 [references/10-post-generation-self-check.md](references/10-post-generation-self-check.md) 做自检。如果方案仍存在主任务不清、输入过多、层级薄弱、状态缺失或可避免的 AI 不确定性，应先修正再回复。

If information is missing, make reasonable assumptions and label them briefly. Ask questions only when the missing information would materially change the design direction.

## Review Output Requirements

When reviewing a design artifact, lead with the highest-impact issues. For each issue, state:

- Problem.
- Severity.
- Violated principle.
- User impact.
- Concrete improvement.

Use severity levels:

- P0: Blocks the core task or causes serious misunderstanding.
- P1: Significantly increases cognitive, input, or visual burden.
- P2: Usable but inefficient, unclear, or emotionally rough.
- P3: Detail polish.

Also preserve what works well. Good review should not only criticize; it should identify which parts should remain because they already reduce user burden.

## Choice Architecture Ethics

When recommendations, defaults, ranking, pricing, reminders, consent, cancellation, or behavior-change mechanisms are involved, apply the Nudge ethics test:

- Is the guidance transparent?
- Can the user easily choose another path?
- Is the action reversible or recoverable?
- Does the default serve the user's interest?
- Is any friction necessary for safety, or is it sludge that blocks the user?
- Would the design still be defensible if openly explained to the user?

Never recommend manipulative patterns, hidden defaults, fake urgency, shame pressure, hard-to-cancel flows, or designs that make user-beneficial actions unnecessarily difficult.
