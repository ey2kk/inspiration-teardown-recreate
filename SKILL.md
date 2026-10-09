---
name: inspiration-teardown-recreate
description: Break down a visual artwork or design reference into three evidence-grounded sections (origin & first-hand resources, formal/style analysis, learning & recreation prompts), then write new-work and image-transformation prompts. Use for turning user-supplied images, screenshots, links, or videos into an analysis-plus-recreation study or a personal inspiration-archive entry. Not for generic one-shot image generation or unrelated app building.
---

# 灵感拆解 · 创意性复刻

把一件设计作品拆成可学习、可复用的方法，再把用户的素材转成同思路的新作品。产出是一份「参考·观察·再创造」的收藏条目，或一轮独立的风格研究。

## 固定产出：每轮三个板块

用户提供图片、截图、链接或视频后，每轮固定依次输出，先在对话中给用户审核：

1. **作者、背景与一手资源**：核实作者、作品名、年代、项目、媒介。优先找官网、工作室、博物馆、画廊、委托方页面，给出可打开链接并注明「展示图 / 高清图 / 原始文件」的实际可获得程度，不把缩略图叫原图。区分「已核实 / 可能归属 / 未确认」，找不到作者不强行归因。
2. **艺术风格与作品机制解析**：用画面可见证据分析色彩、明度、面积比例、构图、网格、视觉重心、层级、留白、字体、形状、材质、光影、空间、节奏。说明手法如何形成观看路径与情绪，避免只写「高级、复古」。区分「这件作品的独特选择」与「可迁移的规律」。截图取色、比例、工艺推断标为估计；动效只依据实际录屏，不从静态图臆测时序。
3. **学习方法、复刻与再创造**：给出可操作步骤；拆分「必须保留的风格核心」与「可变的题材/构图/参数」；提供可直接复制的新作 Prompt，以及把用户素材转成该风格的编辑 Prompt，用可观察视觉特征描述而非堆艺术家名字；明确保留项/变化项/应避免的问题；未生成的 Prompt 标「待测试」。

## 证据边界（不可省略）

- 署名或标题只是查找线索，不是结论。
- 相似作品只作比较参考，不冒充原作、不拿来归因。
- 生成样张不能冒充艺术家原作；保留原作与生成样张的区分。
- 色值、比例、工艺一律标「建议值 / 估计值」，除非有作者自述或官方数据。

## 审核、保存与反馈

- 三板块先给用户审核；未获批不写入收藏、不发布；允许在项目内保留研究草稿。
- 用户批准后直接同步该版本，不再重复询问同一授权；部分批准只同步获批部分。
- 入库保留来源、原作与生成样张的区分、分析、Prompt、反馈和版本；完整研究不能被字段限制静默截断。
- 把用户纠正与认可的理由记为案例经验，区分「单案例偏好」与「通用偏好」，不把一次选择固化成所有规则。

## 引用

- 完整工作约定与证据规则：见 [references/workflow.md](references/workflow.md)。
- 网站视觉规范（纸品、配色、字体、间距、动效）：见 [references/brand-spec.md](references/brand-spec.md)。
- 已积累案例与经验：见 [references/cases.md](references/cases.md)。
- 可复用的新作 / 转化 Prompt 模板：见 [references/prompts.md](references/prompts.md)。

## 何时不适用

- 只想直接生成一张图、不做拆解分析时，走图像生成工具，不必套用本流程。
- 与视觉作品解析无关的网站或应用搭建，不属于本 skill。
