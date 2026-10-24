# 亚马逊AI代理精简供应商价目表

> 原标题：A supplier sends me a 5,000-line price list. My AI agent cuts it to about 600 before I ever look at it.

- 来源：X · Dan Boufford
- 原文发布时间：2026-10-23 03:59
- 本站收录时间：2026-10-22T20:17:29.797Z
- AMZNEWS：https://nologose.github.io/amznews-reading-preview/items/ofwc1un87xk74fcl1ji8k14lu
- 原文：https://x.com/1000asins/status/2113359514279780623

## 摘要

供应商发给我一份5,000行的价目表。在我查看之前，我的AI代理将其缩减到约600行。

它通过UPC将每一行匹配到ASIN，如果没有UPC则通过标题匹配。它检查我是否获得品牌授权，从Keepa拉取数据，剔除销售排名超过300,000的产品，并标记利润率。

构建它大约花了30分钟的提示词编写时间。

## 正文

A supplier sends me a 5,000-line price list. My AI agent cuts it to about 600 before I ever look at it.

It matches every line to an ASIN by UPC, or by title if there's no UPC. It checks whether I'm approved for the brand, pulls the numbers from Keepa, drops anything over a 300,000 sales rank, and flags the margin.

Building it took about 30 minutes of prompting.
