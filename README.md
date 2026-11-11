# PPT Consulting Research · Presentation Skills Library

> 一套面向企业研究、管理咨询式汇报与多人协作PPT的 **Skill 方法库**。
>
> A practical collection of reusable skills for evidence-led business research, presentation storytelling, and visual integration.

## 项目定位 / About

本仓库存放可复用的 Markdown Skill 指令，帮助从**研究问题 → 论证框架 → 页面表达 → 协作整合 → 讲稿与交付**建立更完整的工作流程。

它不是单一PPT模板，也不是能够独立运行的PPT生成器；Skill 本身是供支持该格式的 AI 助手或人工工作流程参考的规则和检查清单。

## Skills 一览

| Skill | 主要解决的问题 | 适用场景 | 版本 |
| --- | --- | --- | --- |
| [PPT Consulting Research](skills/ppt-consulting-research/SKILL.md) | **研究逻辑与内容可信度**：核心问题、故事线、证据核验、专题研究、图表和限时讲稿 | 企业/行业分析、咨询研究报告、调研路演、研究型课程汇报 | v1.0.0 |
| [Editorial Presentation Visual Integration](skills/editorial-presentation-visual-integration/SKILL.md) | **现有PPT的视觉与内容整合**：跨成员样式统一、素材保护、图表、演讲稿与 Harvard 引用检查 | 多人制作PPT的整合、既有幻灯片精修、学生或商务汇报 | v1.0.0 |

### 该选哪个？

- **从零开始做研究型汇报**：先使用 `ppt-consulting-research`，确定研究问题、资料与结论，再组织页面。
- **已有PPT，主要需要合并和美化**：使用 `editorial-presentation-visual-integration`，保护原始素材、图表和已确认的研究内容。
- **既要深入研究，也要合并多人PPT**：先用前者明确内容和证据，再用后者完成样式与交付检查。

两者互补，不需要合并为一个冗长的 Skill。

## 仓库结构

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

每个 Skill 独立维护其 `SKILL.md` 与版本号。根目录 `README.md` 提供索引，`CHANGELOG.md` 记录仓库级内容变化。

## 使用方式 / Usage

1. 打开相应 Skill 的 `SKILL.md`，阅读 **When to use / 使用条件**、工作流和交付检查。
2. 在支持自定义 Skill 的环境中，按该环境的要求导入对应文件夹；或者将 Skill 内容作为项目级工作规则提供给 AI 助手。
3. 同时提供本次任务的**正式标题、听众、汇报时长、参考材料、需要保留的页面及修改边界**。
4. 先检查研究证据和页面大纲，再生成或编辑PPT；交付前逐页渲染检查。

**注意：** 仅克隆本仓库并不会自动在 ChatGPT 或其他平台安装 Skill；是否能自动加载取决于所使用的具体工具。

### 快速调用示例

**研究型汇报**

> 请按 `skills/ppt-consulting-research/SKILL.md` 的工作流，基于所提供的可靠资料制作12分钟企业研究汇报。先给出主线、证据清单和页面规划。所有数据标明来源，不编造组织架构或经营结论。

**多人PPT整合**

> 请按 `skills/editorial-presentation-visual-integration/SKILL.md`，统一这份多人制作PPT的字体、配色、标题和图表语言。不得删改他人提供的已确认数据或原始插画；逐页检查文字溢出和讲稿对应关系。

## 共同原则 / Shared principles

- **研究优先于装饰**：图表和视觉设计必须支持明确观点。
- **证据优先于推测**：区分事实、分析推论、尚待核实的假设。
- **整合而非覆盖**：尊重既有PPT、指定底本、他人成果和用户明确的不可修改项。
- **真实可编辑**：优先保留 PowerPoint 的可编辑对象，而非整页截图拼装。
- **投影与演讲并重**：检查内容密度、字号、图表可读性和汇报时间。
- **真实来源与引用**：数据和图片应能追溯；引用格式服从用户或机构的明确要求。
- **可追踪版本**：使用 `vX.Y.Z`，不使用“最终版”“终稿”“最新版”等名称。

## 版本管理 / Versioning

每个 Skill 在其文件内声明版本，遵循语义化版本规范：

- `vX.Y.Z`：X 为重大不兼容调整，Y 为新增功能，Z 为小修订。
- 修改 Skill 内容时同步更新其版本号和 `CHANGELOG.md`。
- PowerPoint、讲稿与PDF等成果使用 `项目名_vX.Y.Z.扩展名`。
- 仓库中的 `README.md` 和 `SKILL.md` 仍采用约定的标准文件名，通过 Git 历史追踪变化。

目前两个 Skill 均标注为 **v1.0.0**；这不代表仓库已创建 GitHub Release 或 Tag。

## 适用边界与说明

- `ppt-consulting-research` 中的中集来福士研究要求属于**特定项目示例**，不会自动套用到其他公司的研究。
- `editorial-presentation-visual-integration` 涉及的 Harvard 引用以用户提供的院校具体指南为准。
- 本仓库参考专业咨询报告的表达原则，但**不隶属于麦肯锡、罗兰贝格或任何咨询公司**。
- 本仓库目前未添加 LICENSE 文件；公开可见不等于自动获得再分发或商业使用授权。后续可由仓库所有者选择许可证。

---

**Maintainer:** [eric-robomaster-Liang](https://github.com/eric-robomaster-Liang)  
**Repository:** [ppt-consulting-research](https://github.com/eric-robomaster-Liang/ppt-consulting-research)
