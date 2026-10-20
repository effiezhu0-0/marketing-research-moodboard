---
name: marketing-research-moodboard
description: 中文名称「营销趋势调研&情绪板」。用户提及该名称时使用此技能。Research e-commerce promotion venues and in-app splash advertisements, confirm screenshot-backed evidence in Markdown before synthesizing standards, feedback, visual trends, and three directions in one final HTML. Use for major-sale channel pages, campaign venues, promotional splash ads, and campaign visual-direction briefs. Exclude interactive-game and general brand-identity research.
---

# 营销趋势调研&情绪板

After first-stage collection, always create a Chinese Markdown `证据确认板` for user review. After the user confirms the retained evidence, create one Chinese visual HTML that combines `视觉趋势` and `视觉参考` for exactly three evidence-backed directions by default. Supported carriers are `电商大促频道会场` and `开屏广告`.

## Read Before Acting

- Read [references/calibration-baseline.md](references/calibration-baseline.md) at every invocation.
- Read `/Users/zhuruoyan1/Documents/Marketing Moodboard/大促会场与开屏广告设计规范知识库.md` when accessible; it is the canonical local carrier standard.
- If the canonical file is unavailable, read [references/carrier-standards.md](references/carrier-standards.md) and disclose that the fallback may be stale.
- Read [references/research.md](references/research.md) before feedback or observation research.
- Read [references/strategy.md](references/strategy.md) before deriving directions.
- Read [references/workflow.md](references/workflow.md) before collection.
- Read [references/selection-rules.md](references/selection-rules.md) before shortlisting.
- Read [references/output-schema.md](references/output-schema.md) before recording structured data or composing the HTML.
- Read [references/evidence-confirmation.md](references/evidence-confirmation.md) before first-stage collection and before composing the default Markdown evidence board.

Current user instructions override references. Do not import branding, App Store, Google Play, Mobbin, Apple HIG, Material Design, or interactive-game rules into this workflow.

## Start-of-Task User Guide

On every explicit invocation that starts a research project, make the first assistant response the concise Chinese `使用流程` guide below before opening a browser, collecting evidence, or creating project files. This is a user-facing orientation, not an internal plan. Requests to explain, inspect, or edit the skill itself do not start research and do not require the kickoff guide.

Render five separate fenced `text` blocks in the order shown. Every card contains `我会做什么` and `你需要参与`. Place the project-input request in plain text immediately after all five cards. Do not use a bullet list as the primary process layout, show invocation syntax, or place this guide in the final HTML.

The Markdown evidence-confirmation board is a mandatory stage after first-stage collection. Do not derive directions or collect final visual references until the user has confirmed the retained evidence. If the user specifies a stage constraint, repeat it in the relevant card and follow it. Reuse information already supplied rather than asking for it again; a partial brief is enough to start. After showing the guide, extract inputs and proceed with independent work. Ask at most one focused question if a missing field materially changes research. Obtain copyright-use acknowledgement before the first evidence screenshot or image download, as required below; do not treat silence as acknowledgement.

### 使用流程展示样式

- 参照用户提供的截图组织视觉层级：一个「使用流程」标题，下方五张独立的纵向卡片，卡片之间保留清晰留白。
- 在对话中使用五个独立的 fenced `text` blocks 呈现卡片，由客户端负责卡片外观；不把五步合并到同一代码块，不改成表格或普通列表。
- 每张卡片依次显示步骤标题、「我会做什么」、「你需要参与」，三行左对齐；保持正文自然换行，不用空格模拟布局，不加入装饰图标或额外标签。
- 项目资料填写区放在全部卡片之后，使用普通文本，每个字段单独一段。
- 截图仅作为展示样式参考。严格保留下方模板的步骤顺序、步骤名称、正文、平台范围与确认节点，不采用截图中的流程或文案。

### Required First-Response Template

Use this structure, adapting the input placeholders and any supplied stage constraint to the brief:

````markdown
## 使用流程

```text
01｜输入背景
我会做什么：根据你提供的资料明确项目目标、核心感知、载体范围与研究重点。
你需要参与：在全部流程卡片后提供项目资料；资料不全也可开始。
```

```text
02｜规范与证据采集
我会做什么：读取载体规范，在小红书、微博和用户之声采集近 24 个月反馈与案例，保存可追溯证据。
你需要参与：首次截图或下载前确认素材用于研究、学习、内部对齐或本地归档；采集中无需持续跟进。
```

```text
03｜证据确认【需要你确认】
我会做什么：生成证据确认板 MD，展示视觉案例与用户反馈、截图预览、来源和降级链接。
你需要参与：确认保留、排除或补充证据；确认后才进入方向提炼。
```

```text
04｜趋势分析与方向提炼
我会做什么：仅基于已确认的证据，结合官方趋势提炼 3 个视觉方向，说明依据、风险和载体应用方式。
你需要参与：查看分析，可补充项目限制或指出需要补充的证据。
```

```text
05｜方向确认、参考采集与整合交付
我会做什么：呈现 3 个候选方向；确认后在 Pinterest、Behance、站酷筛选去重，每个方向目标为 5 张灵感参考＋5 张执行参考，另选 4 个反面案例，生成一个整合 HTML 并检查桌面与手机显示。
你需要参与：选择、调整或否决方向，并查看成品；合格素材不足时会如实说明，不凑数。
```

请先提供项目资料；资料不全也可开始：

项目名称：<活动或项目名称>

设计载体：<电商大促频道会场 / 开屏广告 / 两者 / 暂不确定>

项目目标与核心感知：<希望达成什么、用户首先感受到什么；可暂不确定>

活动节点与目标人群：<如双 11、年货节；人群可选填>

如有 Brief、PRD、链接或截图，也可一并补充。
````

## Scope And Inputs

Extract project background, priority goal, core perception, carrier boundary, campaign node, audience when provided, and research openness. Ask at most one focused follow-up if a material field cannot be inferred.

- A promotion venue coordinates campaign identity, navigation, benefits, content/product modules, and conversion paths.
- A splash advertisement is a time-limited, dismissible promotional interstitial at App entry. It is not a neutral launch screen, loading state, popup, or ordinary first screen.
- Exclude App icons, onboarding, ordinary product pages, general brand identity, packaging, physical space, unrelated advertising, and interactive-game content.

## Source And Evidence Rules

- Use the logged-in browser session and enter platforms directly. Do not use general search engines or search-result pages as evidence.
- Before the first evidence screenshot or image download, tell the user that references are usually copyrighted and obtain acknowledgement for research, study, internal alignment, or local archival use.
- For first-stage evidence, use Xiaohongshu, Weibo, and Voice of User when relevant and accessible. Treat platforms as search surfaces, then classify each opened detail only as `用户反馈` or `视觉案例`.
- Build separate query families for every selected carrier and both evidence tracks. Adapt queries using visible platform vocabulary; stop repeating empty or irrelevant variants.
- Open the original detail/source page before counting or interpreting an item. If a Xiaohongshu detail page is inaccessible because of anti-bot controls, preserve the result-search page URL that visibly contains the post as the audit link instead. Record the failed detail URL when known and the reason, and treat only information visibly available on that search page as evidence; do not invent missing post context, date, engagement, or comments.
- Record platform, carrier, evidence type, stage, login state, query, adaptation reason, URL, visible date, outcome, screenshot path, quote, observable fact, interpretation, and limitation.
- Count or quote user feedback only inside the exact rolling 24-month window. Target at least 10 qualified unique feedback items when available; disclose genuine shortfalls.
- Every counted social post or case needs a genuine complete source screenshot. Never substitute a search thumbnail, recreated text card, isolated asset, or contextless crop.
- For Xiaohongshu, preserve the complete readable two-column post detail with media and creator/copy/date/engagement/comment context. Use measured element, stitched, or viewport capture; do not shrink the post inside a broad full-page screenshot.
- Never bypass authentication, paywalls, download restrictions, or technical controls.

## Mandatory Evidence Confirmation Board

After first-stage collection, create and show `证据确认板.md` before trend synthesis. This is the default research deliverable and is separate from the final HTML.

- Include only two evidence types: `用户反馈` and `视觉案例`. A visual case may be a complete venue page, venue module, campaign visual, animation, or design draft when it is relevant to the carrier. Do not exclude a design draft solely because its online status cannot be verified; state its visible source status accurately and do not describe it as a verified live page.
- A user feedback item must directly concern the venue, venue entry, benefit comprehension, category/product continuation, or campaign-value perception. Do not count generic Double 11 discussion merely because it matches a query.
- Preserve the existing first-stage source coverage of Xiaohongshu, Weibo, and Voice of User. Do not replace it with fixed brand/platform grouping; use brand names only as adaptable query vocabulary and card metadata when relevant.
- Use the card fields, link degradation rules, exclusions, and confirmation prompt in [references/evidence-confirmation.md](references/evidence-confirmation.md).
- When the user supplies screenshots, treat them as project reference material unless the user explicitly requests them to become evidence. Do not add a separate screenshot-calibration stage.

## Research And Trend Synthesis

1. Define carrier boundaries and good-execution criteria from the brief and canonical standard.
2. Research recent feedback and public visual observations by carrier and evidence type.
3. Read current Pinterest Predicts, Canva Design Trends, and Adobe Creative Trends as directional context, not user evidence.
4. Translate `evidence → observable fact → design interpretation → project implication`.
5. Tag evidence strength only as `较强公开证据`, `方向性证据`, `单点观察`, `设计推断`, or `证据冲突`.
6. Tag recurring mechanisms `新兴`, `成熟`, or `泛滥`, with maturity explicitly marked as inference and given a confidence level.
7. Assess `载体成立与任务清晰`, `感知契合`, and raw `公开信号` separately. Do not collapse them into one score.

For promotion venues, analyze campaign identity, hierarchy, benefit comprehension, navigation/module continuity, product legibility, atmosphere rhythm, and conversion continuity.

For splash advertisements, analyze instant campaign recognition, message focus, brand-campaign relationship, brief-exposure legibility, skip/action clarity, safe cropping, and destination continuity.

Derive exactly three visual directions by default from the collected cases, visual trends, and carrier evidence. A direction should be a coherent, evidence-backed visual/design proposition; it may be framed through communication, perception, visual language, composition, material, interaction rhythm, or another recurring mechanism revealed by the research. Do not preset directions as “communication goal and first perception,” and do not reduce one to an isolated technique such as gradient, 3D, glow, collage, celebrity, product cutout, or red. For multi-carrier briefs, state the transfer separately for each carrier.

Present the three provisional directions and their confirmed supporting evidence in the conversation, then obtain explicit approval before collecting final visual references. The final output remains one combined HTML.

## Visual Reference Collection

Collect references after the three directions are evidence-supported. Use Pinterest, Behance, and ZCOOL by default. Search each platform directly and open detail pages before counting.

For each direction:

1. Create short terms from perception, carrier, campaign node, hierarchy, atmosphere, typography, material, composition, and motion.
2. Target 40 opened detail pages per platform across all three directions. Record platform visits and failures. Author information is optional; retain visible date and original link.
3. Screen visible candidates before downloading. Rank direction relevance, carrier transfer value, visual quality, source confidence, and distinctness.
4. Reject unidentifiable, irrelevant, broken, or caption-dependent images. Remove near-duplicates and keep the candidate with stronger carrier relevance.
5. Select exactly 10 qualified references per direction when available: 5 `灵感参考` and 5 `执行参考`.

`执行参考` should be mobile promotion venues, splash advertisements, campaign pages, or directly transferable marketing executions. `灵感参考` may be posters, web, illustration, 3D, campaign graphics, space, or other media only when the visual mechanism clearly transfers. Give each image a concise distinct caption and admission reason.

Also select exactly four negative examples across the final output, each exposing a different carrier-specific risk. Keep them separate from the positive 10-image direction grids.

## Single HTML Output Contract

Create `marketing-research-moodboard-<project-slug>.html`. Do not create separate research and moodboard HTML files by default.

The file contains, in order:

1. Brief summary, carrier definitions, research scope, date window, source coverage, and limitations.
2. `视觉趋势`: standards, recent feedback synthesis, public observations, numbered insights, mechanisms/maturity, evidence strength, and exactly three directions. Each direction shows its rationale, supporting evidence, risks, and carrier translation.
3. `视觉参考`: exactly three direction sections, each with a stable 5-column by 2-row positive-reference grid when 10 qualified samples exist. Preserve the complete image with `object-fit:contain` or equivalent; include platform, visible date, original link, role, caption, and admission reason.
4. `反面参考`: exactly four examples with exclusion reason and carrier-specific risk.
5. Source and rights footer plus platform visits, reviewed counts, degradation notes, and audit links.

Evidence and feedback cards use two equal-width columns at desktop width. Keep one carrier per evidence card and show a carrier tag. Use responsive centered HTML, near-`#F8FAFC` canvas, white borderless cards, dark readable text, and one saturated accent sparingly. Keep operational metadata out of visible narrative while retaining it in embedded structured data or an adjacent data file when produced.

## Degradation And Quality Gate

- Use bounded navigation and analysis timeouts. Record a failed URL and continue instead of repeatedly retrying it.
- If a platform reviews fewer than 40 details, finish using qualified accessible evidence and disclose the exact reviewed count and failure reason.
- If a direction has fewer than 10 qualified references, deliver the smaller set rather than padding it with irrelevant or duplicate images.
- Do not invent feedback, dates, engagement, carrier assignment, or visual claims.
- Fail visual-reference collection only when all platforms yield zero usable samples. Surface authentication blockers for user action.
- Verify the rendered HTML at 1440px and a mobile width. It fails quality review if it has broken images, cropping, overflow, overlap, unreadable text, inconsistent carrier tags, image-caption contradictions, or missing source links.
- Preserve platform visits, query families, adaptation reasons, dates, URLs, screenshot provenance, judgments, directions, selected images, limitations, and local-standard version in structured data when one is produced.

