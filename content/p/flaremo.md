+++
title = "FlareMo"
template = "page.html"
sort_by = "none"

[extra]
logo = "/img/icons/flaremo.svg"
tagline = "Cloudflare 原生的团队知识库 —— 一个人用是私人笔记，一个团队用是共享知识库"
back_anchor = "工具"
back_label = "返回首页"
meta = ["AI 原生", "知识库", "Memos 兼容", "MCP"]
repo = "https://github.com/realchendahuang/FlareMo"
repo_label = "github.com/realchendahuang/FlareMo"

highlights = [
  "与 Memos 数据 / API 兼容",
  "原生支持 MCP 协议",
  "个人 / 团队双模式",
  "Cloudflare 原生，部署轻量",
  "AI 可直接读写笔记",
  "支持多用户与权限管理",
]

[[extra.scenarios]]
title = "从 Memos 平滑升级"
desc = "数据格式兼容，不用迁移历史笔记，直接接上就能继续记。"

[[extra.scenarios]]
title = "让 AI 处理你的笔记"
desc = "通过 MCP 协议，可以让 Claude 等 AI 直接搜索、总结、整理你的笔记内容。"

[[extra.scenarios]]
title = "团队共享知识库"
desc = "多人的笔记汇聚到同一个空间，新成员入职时能快速查到团队积累的东西。"

[[extra.scenarios]]
title = "沉淀项目文档"
desc = "把项目相关的决策记录、踩坑笔记、接口说明集中存放，支持全文检索。"

[[extra.related]]
slug = "memos"
title = "Memos"
desc = "随手记点什么"
logo = "/img/icons/memos.svg"

[[extra.related]]
slug = "vaultwarden"
title = "Vaultwarden"
desc = "密码自己管"
logo = "/img/icons/vaultwarden.svg"

[[extra.related]]
slug = "rsshub"
title = "RSSHub"
desc = "万物皆可 RSS"
logo = "/img/icons/rsshub.svg"
+++

如果你已经在用 Memos，可能会遇到一个瓶颈：**想到处用 AI 处理笔记，但不知道从哪下手**；或者团队里想共享一些文档，又不想再引入一套重型知识库系统。

**FlareMo 是 Cloudflare 原生的知识库应用**，一个人用就是私人笔记，一个团队用就是共享知识库。它提供**与 Memos 兼容的 API**，所以已有数据可以直接接过来；同时支持 **MCP 协议**，意味着可以让 AI 直接读写你的笔记。
