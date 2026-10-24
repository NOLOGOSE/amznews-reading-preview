# AMZNEWS Skill 安装说明

版本：1.0.0。这是一个纯文本 Agent Skill，不包含安装器、依赖或可执行脚本。

## 安装

1. 读取 https://nologose.github.io/amznews-reading-preview/amznews-skill/SKILL.md 的原始文本，确认 frontmatter 中 name 为 amznews。
2. 按当前 Agent 的文档确认用户级或项目级 Skill 目录，优先沿用用户已经选择的范围。没有明确范围时先说明目标目录。
3. 在目标目录创建 amznews/SKILL.md 并保存完整原文，不要改动其他 Skill、配置或凭据。若存在同名目录，先报告路径和差异，征得用户同意再更新；不要另建重复副本。
4. 报告保存位置。若客户端只在会话开始时发现 Skill，请开启新会话。
5. 询问“过去 24 小时亚马逊卖家最值得关注的 5 条资讯是什么？”；真实请求服务，回答标注时间范围、中文摘要、AMZNEWS 阅读链接与原文链接。没有结果就如实说明。

## 地址与更新

本包绑定服务地址 https://nologose.github.io/amznews-reading-preview。每个新会话首次使用会读取该站的 llms.txt 和 OpenAPI；接口发生不兼容变更、站点地址改变或安装说明更新时，仍需检查并更新本 Skill，不能承诺永久无需更新。

Claude 桌面版、Cursor 的本机客户端可按其能力访问，云端远程客户端不能访问用户电脑的回环地址。正式公网域名启用后，从新域名重新获取本包。

## 不安装也能查

把 https://nologose.github.io/amznews-reading-preview/llms.txt 与 https://nologose.github.io/amznews-reading-preview/openapi-v1.json 发给 Agent，请它按公开接口匿名查询。支持远程 MCP 的客户端也可以连接 https://nologose.github.io/amznews-reading-preview/api/mcp。
