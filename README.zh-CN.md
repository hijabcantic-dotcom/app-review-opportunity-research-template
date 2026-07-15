# 应用评论机会调研模板

这是一份面向创始人的实用模板，用于把公开的 App Store 和 Google Play 评论转化为客户访谈问题和产品假设。

目标不是收集功能需求，而是寻找反复出现的工作流失败：谁在什么场景下无法完成什么任务，造成了什么代价，再决定是否值得访谈和验证。

## 45 分钟使用方法

1. 选择一个围绕同一用户任务的竞品。
2. 收集 20 到 50 条近期低评分评论。
3. 将有用的原文摘录填入 [`research-template.md`](research-template.md)。
4. 只有当评论描述的是相同任务、相同失败和相同后果时，才将它们归为一类。
5. 为每个重复痛点写一个访谈问题。评论是线索，不是市场需求的证明。

优先验证同时具备重复性、具体场景和明确代价的痛点。随后在两到四个相近竞品中重复检查，跨竞品重复出现的模式更值得研究。

需要处理更大样本时，[Review2Idea](https://review2idea.com/zh/free-app-review-analysis-tool?utm_source=github&utm_medium=referral&utm_campaign=app_review_research_template) 可以将公开评论聚类为带原始证据的痛点。仍应保留原评论，并通过真实用户访谈验证假设。

如果你正在查看竞品应用页面，可选的 [Chrome 扩展](https://github.com/hijabcantic-dotcom/review2idea-competitor-analyzer) 会把当前 App Store 或 Google Play 链接直接带入这一流程，无需手动复制。

## 在 AI Agent 中使用

可在兼容 Skills 的 AI Agent 中安装证据调研工作流：

```bash
npx skills add hijabcantic-dotcom/app-review-opportunity-research-template --skill app-review-evidence-research
```

查看英文完整模板：[README.md](README.md)。
