# X Ops Diary

一个 AI 垂类 X（Twitter）账号的**公开运营日记**：内容策略、工具搭建、数据变化、复盘实验。

> Building in public: an AI-focused X account, documented daily — what I try, what breaks, and what the numbers say.

公开的原因很简单——我在这件事上没有先验优势，把过程写出来，一来逼自己复盘，二来认识同路人。

## 怎么读

| 想知道 | 看这里 |
|---|---|
| 我每天干了什么、踩了什么坑 | [`diary/`](diary/) 按月一篇 |
| 数据长什么样 | [`data/metrics.csv`](data/metrics.csv) 每天一行 |
| 方法论 | [`playbooks/`](playbooks/) 钩子库、周复盘模板 |
| 为什么这么选 | [`docs/decisions.md`](docs/decisions.md) 关键决策记录 |

## 我在做什么

运营一个聚焦 AI 的 X 账号，内容覆盖五个板块：

| 板块 | 例子 |
|---|---|
| 模型 / 产品发布 | 新模型、新 API、开源权重 |
| 论文热度 | HF Daily Papers、arXiv 上的高讨论度工作 |
| 开发者社区 | HN、GitHub Trending、LocalLLaMA |
| 产品 / 搞钱 | Product Hunt 新品、AI 创业融资 |
| 人物言论 | 一线从业者的公开观点与分歧 |

目标不是“发得多”，是**在素材还热的时候，用一句话说清它为什么重要**。

## 目录

```
diary/        按月一个 md，每天一节
playbooks/    可复用的方法论：钩子句式、周复盘模板
data/         metrics.csv（每天一行）+ 字段说明
docs/         关键决策记录（ADR 风格）
```

## 更新节奏

- **日记**：工作日每天一节，写进当月的 `diary/YYYY-MM.md`；周末不定
- **数据**：每天一行，抄 4 个数字，30 秒
- **复盘**：每周日填一次 `playbooks/review.md`

每节日记固定四段：**今天做了什么 / 关键决策 / 踩坑 / 数据与明天**。

## 免责

- 这里记录的是真实过程，包含大量失败和返工，不构成任何建议。
- 不包含他人隐私、私信内容或未公开信息。
- 不含任何 API Key、Cookie、令牌。

## License

MIT
