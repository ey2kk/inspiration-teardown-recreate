# 灵感拆解 · 创意性复刻

一个 Codex skill：把一件视觉作品拆成可学习、可复用的方法，再把用户素材转成同思路的新作品。产出是「参考 · 观察 · 再创造」的收藏条目，或一轮独立的风格研究。

## 这是什么

这是「片刻收纳 · A little archive」个人灵感收藏项目沉淀出来的方法存档。核心是一个证据先行的三板块工作流：

1. 作者、背景与一手资源
2. 艺术风格与作品机制解析
3. 学习方法、复刻与再创造

附带品牌视觉规范、两轮真实案例，以及可复用的生成 / 素材转化 Prompt 模板。

## 安装

把本目录复制（或软链）到技能目录，例如：

```bash
cp -r inspiration-teardown-recreate ~/.codex/skills/
```

之后通过 `$inspiration-teardown-recreate` 显式调用，或在匹配「拆解一件设计作品」类请求时自动生效。

## 目录

```text
inspiration-teardown-recreate/
|-- SKILL.md                 入口：工作流、证据边界、审核与反馈
|-- README.md                本说明
|-- agents/openai.yaml       UI 元数据
`-- references/
    |-- workflow.md          完整工作约定
    |-- brand-spec.md        网站视觉规范
    |-- cases.md             已积累案例与教训
    `-- prompts.md           可复用 Prompt 模板与评审清单
```

## 来源与状态

- 来源：个人项目「片刻收纳 · A little archive」（Next.js + Cloudflare D1/R2 + Drizzle），本 skill 只含方法论与案例，不含网站代码。
- 案例 1「SBMR 蓝色纸品」：分析已由用户批准并入库。
- 案例 2「暗色史诗 · 剪影与命运路径」：草稿待用户审核，作者与来源尚未核实。

## 约定

未获批的分析不写入收藏、不发布；生成样张不冒充原作者；色值、比例与工艺推断一律标注为建议值或估计值。
