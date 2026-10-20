# Marketing Carrier Standards

> Fallback only. The canonical knowledge base is [source-docs/promotional-carrier-knowledge-base.md](source-docs/promotional-carrier-knowledge-base.md). Read this file only when the canonical file is unavailable, and disclose that it may be stale.

## Source record

- Source: `16.0设计系统-营销设计规范`, 品牌与营销设计部
- URL: https://relay.jd.com/file/design?id=2057763035308625921&page_id=13592%3A273&mode=dev
- Local extraction date: 2026-08-18
- Included: `大促链路` and `大促组件`
- Confirmed pages: 心智地图、氛围触点、页面框架、会场头图、权益优惠、商品卡片、广告资源
- Excluded: `互动链路` and `互动组件`, including 玩法策略、互动页面框架、权益弹窗、互动列表页、互动商品卡片
- Status: scoped local knowledge base. Re-check when the source version changes or the user asks for current requirements.

Use this source to learn carrier identity and good-execution criteria. Do not present this summary as a complete pixel-level implementation specification. Verify exact sizes, tokens, safe areas, durations, or component parameters at the source instead of guessing.

## 电商大促频道会场

A promotion venue is a campaign-led commerce destination rather than an ordinary category or product-list page. It coordinates campaign identity and mental availability across the path, applies atmosphere at planned touchpoints, uses a coherent page framework, and connects promotion modules to product/content conversion.

Count only complete screens or sequences establishing campaign context, page-level hierarchy, navigation/section organization, campaign-serving benefit/content/product/advertising modules, and a plausible path from promise to conversion. Exclude isolated banners, ordinary product lists without campaign framing, interaction/game pages, benefit popups, and partial crops.

Good execution means:

- `心智一致`: campaign promise and identity remain recognizable across entry, atmosphere, header, benefits, merchandise, and advertising resources.
- `首屏聚焦`: the first viewport establishes campaign identity, primary message, and next useful action.
- `层级可扫读`: users distinguish campaign message, benefits, navigation, modules, and supporting information quickly.
- `利益可理解`: eligibility, value, timing, threshold, and action remain understandable.
- `框架连续`: header, navigation, benefits, product cards, and ads form one campaign system.
- `商品可决策`: product image, title, price, promotion, trust cue, and action remain legible.
- `氛围有节奏`: atmosphere marks important touchpoints without filling every surface or damaging contrast.
- `转化连续`: visual emphasis leads toward a clear destination whose experience continues the promise.

Failure modes include atmosphere overwhelming information, equal-weight modules, disappearing campaign identity, ambiguous benefits, incomparable product cards, disruptive ad modules, and gameplay mistaken for the venue.

## 开屏广告

The supplied Relay scope primarily establishes major-promotion pathways and components, not a complete splash-ad specification. Treat exact platform parameters as unverified until a dedicated standard is supplied.

A splash advertisement is a short-exposure promotional interstitial shown during App entry, normally with a skip mechanism and destination action. It is not a neutral launch screen, loading placeholder, popup, in-feed ad, or ordinary first page.

Good execution means immediate campaign/brand recognition, one dominant message, short-exposure legibility, clear and separated skip/action states, a coherent hierarchy among celebrity/product/promotion/campaign, destination continuity, and safe composition across device crops.

Failure modes include poster-like density, generic sale symbolism, control collisions, obscured offers, disconnected destinations, and launch/loading screens mislabeled as advertisements.
