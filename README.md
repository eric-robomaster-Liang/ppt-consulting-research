# PPT Consulting Research · Presentation Skills Library

**中文：** 面向企业研究、管理咨询式汇报和多人协作演示文稿的开放式 Skill 方法库。  
**English:** A reusable collection of skills for business research, consulting-style presentations, and collaborative slide editing.

**Language / 语言：** [简体中文](#中文) · [English](#english)

---

## 中文

### 项目介绍

本仓库包含两套相互补充的 Markdown Skill 工作规范，覆盖：

**研究问题 → 证据与论证 → 演示结构 → 视觉整合 → 讲稿与质量检查。**

这里提供的是 **AI 工作指令、方法与检查清单**，而非 PowerPoint 模板或可独立运行的软件。它们可供支持自定义 Skill 的 AI 工具加载，也可作为人工制作演示文稿的工作规范。

### Skill 目录

| Skill | 核心能力 | 适用任务 | 当前版本 |
| --- | --- | --- | --- |
| [PPT Consulting Research](skills/ppt-consulting-research/SKILL.md) | 研究问题界定、论证主线、证据核验、专题分析、数据图表与限时讲稿 | 企业研究、行业分析、咨询式汇报、研究型课程展示 | v1.0.0 |
| [Editorial Presentation Visual Integration](skills/editorial-presentation-visual-integration/SKILL.md) | 整合多人PPT、统一视觉语言、保护原始素材、核对图表与讲稿、检查 Harvard 引用 | 已有PPT的视觉精修、多人汇报整合、学术或商务演示 | v1.0.0 |

**如何选择？**

- **从零开始做研究型汇报：** 优先使用 *PPT Consulting Research*，先解决研究逻辑与证据问题。
- **已有PPT需要统一排版：** 优先使用 *Editorial Presentation Visual Integration*，保护已确认的内容和原始素材。
- **既要研究又要整合：** 先使用前者梳理研究主线，再使用后者统一视觉和交付质量。

### 仓库结构

```text
ppt-consulting-research/
├── README.md
├── CHANGELOG.md
└── skills/
    ├── editorial-presentation-visual-integration/
    │   └── SKILL.md
    └── ppt-consulting-research/
        └── SKILL.md
```

两个 Skill 分别维护自身的版本。根目录的 `README.md` 是项目索引，`CHANGELOG.md` 记录仓库级改动。

### 使用方法

1. 打开相应文件夹的 `SKILL.md`，阅读适用场景、工作流程及交付检查。
2. 根据 AI 工具的实际支持情况导入该文件夹，或将 Skill 说明提供给 AI 助手作为任务规范。
3. 提供你的项目资料、正式标题、目标听众、汇报时长、页面边界和其他硬性要求。
4. 在制作前检查研究主线和证据；制作完成后检查可编辑性、视觉效果和讲稿时长。

> **注意：** 克隆此仓库不会自动在 ChatGPT 或其他工具中安装 Skill。加载方式取决于具体产品和工作环境。

**提示词示例：研究型汇报**

> 请依据 `skills/ppt-consulting-research/SKILL.md`，基于我提供的资料规划一份12分钟企业研究PPT。先输出研究主线、证据清单及页面结构。请区分事实、推论和待核实信息，不要虚构企业组织架构或经营数据。

**提示词示例：多人PPT整合**

> 请依据 `skills/editorial-presentation-visual-integration/SKILL.md`，统一这份多人制作PPT的标题、字体、配色和图表语言。保留已确认的数据及原始插画，逐页检查文字溢出、引用和讲稿对应关系。

### 共同原则

- **研究优先：** 每张幻灯片应支撑一个明确观点，而非堆积素材。
- **证据可靠：** 明确区分事实、分析推论和待核实假设；引用可追溯。
- **尊重原稿：** 用户指定保留的页面、数据、图形和设计不得擅自改动。
- **视觉清晰：** 统一设计系统，同时允许不同内容采用不同布局。
- **可编辑与可展示：** 不以整页截图替代实际PPT编辑；逐页检查投影可读性。
- **讲稿与时长一致：** 让关键结论能够在规定时间内被讲清楚。

### 版本与维护

- 各 Skill 使用语义化版本号 `vX.Y.Z`；版本号记录在各自的 Skill 文件内。
- 文档和交付成果也采用可追踪版本，例如 `项目名_v1.0.0.pptx`。
- `README.md`、`SKILL.md` 保留行业惯用固定文件名，通过 Git 历史管理其变更。
- 目前两个 Skill 的版本均为 **v1.0.0**，不等于已发布 GitHub Release 或创建版本标签。仓库变更详见 [CHANGELOG.md](CHANGELOG.md)。

### 适用边界与授权

- *PPT Consulting Research* 中关于中集来福士的约束仅是**特定项目案例**，不能自动应用于其他项目。
- *Editorial Presentation Visual Integration* 的 Harvard 引用要求应服从使用者所属学校或机构的具体指南。
- 本项目参考成熟咨询报告的信息组织方法，但不隶属于麦肯锡、罗兰贝格或其他咨询公司。
- 当前仓库**没有 LICENSE 文件**；代码或文档公开可见，不代表自动获得再分发、改编或商用许可。授权条款应由仓库维护者另行选择。

---

## English

### About this repository

This repository contains two complementary, Markdown-based skills covering the workflow from:

**Research question → Evidence and argument → Presentation structure → Visual integration → Speaker script and quality assurance.**

These files are **instructions, workflows, and checklists**, not PowerPoint templates or standalone presentation-generation software. They can be used with AI tools that support custom skills or followed as a practical guide for manual presentation work.

### Available skills

| Skill | Core capabilities | Best suited for | Current version |
| --- | --- | --- | --- |
| [PPT Consulting Research](skills/ppt-consulting-research/SKILL.md) | Define the research question, build an evidence-backed storyline, verify sources, develop thematic analysis, design data visuals, and plan a timed presentation | Company and industry research, consulting-style reports, research presentations | v1.0.0 |
| [Editorial Presentation Visual Integration](skills/editorial-presentation-visual-integration/SKILL.md) | Integrate multi-author decks, create a consistent visual language, preserve source assets, align charts and scripts, and check Harvard references | Refining existing slides, merging team contributions, academic and business presentations | v1.0.0 |

**Which skill should I use?**

- **Building a research presentation from scratch?** Start with *PPT Consulting Research* to develop the argument and verify evidence.
- **Improving or merging an existing deck?** Use *Editorial Presentation Visual Integration* to harmonize slides without changing approved material.
- **Doing both?** Apply the research skill first, followed by the visual integration skill.

### Repository structure

```text
ppt-consulting-research/
├── README.md
├── CHANGELOG.md
└── skills/
    ├── editorial-presentation-visual-integration/
    │   └── SKILL.md
    └── ppt-consulting-research/
        └── SKILL.md
```

Each skill has its own version. The root `README.md` serves as an index, while `CHANGELOG.md` records repository-level changes.

### How to use

1. Open the relevant `SKILL.md` and review its intended use, workflow, and delivery checks.
2. Import the skill directory into your AI environment if supported, or provide the instructions to an assistant as task-specific guidance.
3. Supply the source materials, approved presentation title, audience, time limit, protected slides, and other constraints.
4. Review the storyline and evidence before slide production; check editability, visual quality, and presentation timing before delivery.

> **Note:** Cloning this repository does not automatically install a skill in ChatGPT or any other product. Loading behavior depends on the tool and environment.

**Example prompt: research presentation**

> Follow `skills/ppt-consulting-research/SKILL.md` to plan a 12-minute company research presentation based on my supplied materials. Start with the storyline, evidence inventory, and slide outline. Distinguish verified facts from inferences and open questions; do not fabricate organizational structures or financial figures.

**Example prompt: multi-author deck integration**

> Follow `skills/editorial-presentation-visual-integration/SKILL.md` to unify the typography, titles, palette, and chart styling of this team presentation. Preserve approved figures and original illustrations. Check every slide for text overflow, citations, and consistency with the speaker script.

### Shared principles

- **Research before decoration:** Every slide should advance a clear argument.
- **Evidence over speculation:** Separate facts, reasoned inferences, and unverified assumptions; preserve source traceability.
- **Respect source material:** Do not silently modify protected slides, approved figures, or original visual assets.
- **Clarity without uniformity:** Use consistent visual rules without forcing every slide into the same layout.
- **Editable and presentation-ready:** Do not replace editable slides with whole-slide screenshots; check projection readability.
- **Script-aware delivery:** Ensure the main findings can be presented within the specified time.

### Versioning and maintenance

- Each skill follows semantic versioning using `vX.Y.Z` and declares its own version.
- Deliverables also use traceable filenames, for example `ProjectName_v1.0.0.pptx`.
- Standard filenames such as `README.md` and `SKILL.md` remain unchanged; Git history tracks revisions.
- Both skills are currently marked **v1.0.0**. This does not imply a GitHub Release or Git tag exists. See [CHANGELOG.md](CHANGELOG.md) for repository changes.

### Scope and licensing

- The CIMC Raffles requirements inside *PPT Consulting Research* are **project-specific examples** and must not be treated as universal rules.
- Harvard referencing in *Editorial Presentation Visual Integration* must follow the user's institution-specific guidance.
- The repository draws on established consulting-presentation practices but is **not affiliated with McKinsey, Roland Berger, or any other consulting firm**.
- There is currently **no LICENSE file**. Public visibility alone does not grant permission to redistribute, adapt, or use the work commercially. The repository maintainer should choose a license separately.

---

**Maintainer / 维护者:** [eric-robomaster-Liang](https://github.com/eric-robomaster-Liang)  
**Repository / 仓库:** [ppt-consulting-research](https://github.com/eric-robomaster-Liang/ppt-consulting-research)
