# Product Design Skill

一个用于产品设计与设计评审的 Codex skill。

它帮助你在产品交互上做创新设计，也可以检查已有设计稿、截图、文档、HTML 原型或线上系统是否合理。核心判断标准是：少用脑、少用手、少用眼，同时保留用户掌控感、美学、人性和选择架构伦理。

## 适用场景

- 从 0 到 1 设计产品功能、页面结构、任务流程或交互原型。
- 检查 App、Web、SaaS、CRM、AI 产品、工作台、后台、创作工具等设计是否合理。
- 根据截图、录屏、PRD、PPT、HTML 原型或线上页面给出设计问题与改进建议。
- 输出页面线框说明、任务流、组件清单、设计评分、改版建议或 HTML 原型说明。

## 核心原则

- 少用脑：用户不需要解释、不需要猜、不需要学习复杂概念，就知道怎么用。
- 少用手：减少输入、配置、跳转、重复操作和手动整理。
- 少用眼：界面简洁、层级清楚，一眼能看到重点。
- 有掌控：用户知道系统状态，能撤销、修改、恢复、跳过或人工接管。
- 有美感：视觉服务于理解、效率、情绪和品牌气质。
- 有人性：减少焦虑、打断、误导和被迫感。

## 文件结构

```text
product-design-skill/
|-- SKILL.md
|-- agents/
|   `-- openai.yaml
`-- references/
    |-- 01-basic-principles.md
    |-- 02-classic-theories.md
    |-- 03-input-inventory.md
    |-- 04-interaction-visual-aesthetics.md
    |-- 05-ai-product-interaction.md
    |-- 06-product-type-patterns.md
    |-- 07-design-review-checklists.md
    |-- 08-design-scoring-system.md
    |-- 09-design-output-templates.md
    |-- 10-post-generation-self-check.md
    |-- 11-case-library-template.md
    |-- 12-excellent-case-library.md
    |-- 13-nudge.md
    |-- 14-source-map.md
    |-- 15-ued-ui-visual-review.md
    `-- README.md
```

## 安装方式

把本仓库放到 Codex 的 skills 目录中，例如：

```bash
mkdir -p ~/.codex/skills
cp -R product-design-skill ~/.codex/skills/product-design
```

也可以把仓库内容复制到：

```text
~/.codex/skills/product-design/
```

## 使用示例

```text
使用 product-design skill，帮我检查这个 App 首页是否符合少用脑、少用手、少用眼。
```

```text
基于这些截图，给出产品设计问题、严重程度、违反原则、用户影响和改进建议。
```

```text
为这个 AI 生成工具设计一个首页交互原型，要求用户不需要写复杂 prompt。
```

## 开源协议

本项目使用 MIT License 开源。
