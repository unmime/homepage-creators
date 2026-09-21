+++
title = "RSSHub"
template = "page.html"
sort_by = "none"

[extra]
logo = "/img/icons/rsshub.svg"
tagline = "把整个互联网变成 RSS —— 万物皆可订阅"
back_anchor = "精选"
back_label = "返回首页"
meta = ["Node.js", "RSS", "信息聚合", "5000+ 路由"]
repo = "https://github.com/DIYgod/RSSHub"
repo_label = "github.com/DIYgod/RSSHub"
docs = "https://docs.rsshub.app"
docs_label = "docs.rsshub.app"
live = "https://rss.zlzl.io"

highlights = [
  "覆盖 5000+ 站点路由",
  "支持无账号浏览公开内容",
  "可自建，不受公共实例限流",
  "支持过滤、全文抓取等参数",
  "Docker 一键部署",
  "社区持续更新路由规则",
]

[[extra.scenarios]]
title = "订阅没有 RSS 的平台"
desc = "B站 UP 主更新、微博博主、知乎专栏、小红书账号、播客节目……全部转成 RSS，统一在阅读器里看。"

[[extra.scenarios]]
title = "追更资讯站和博客"
desc = "技术博客、新闻站、论坛帖子、GitHub Release 更新，聚合成一个信息流，不用逐个打开网页。"

[[extra.scenarios]]
title = "配合自动化工作流"
desc = "把 RSS 源接到 n8n / Node-RED / 自写脚本，实现\"有新内容就推送到 Telegram / 存进笔记 / 触发某个动作\"。"

[[extra.scenarios]]
title = "为阅读器提供源"
desc = "配合 FreshRSS 或任意 RSS 阅读器使用，把碎片化的信息收敛回一个不被打扰的地方。"

[[extra.related]]
slug = "sink"
title = "Sink"
desc = "短链接服务"
logo = "/img/icons/sink.svg"

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
+++

RSS 是一种很老但很好用的技术：网站更新时主动推给你，而不是你反复去刷。可惜越来越多的平台取消了 RSS 输出 —— 微博、B站、知乎、小红书、抖音，全都没有。

**RSSHub 做的就是把这些内容"重新变回 RSS"。** 它内置了几千条路由规则，覆盖国内外主流平台：你只要把链接拼成特定格式，就能得到一个标准的 RSS 源，塞进任意阅读器。一个 RSSHub 实例，等于给整个互联网装上了订阅按钮。
