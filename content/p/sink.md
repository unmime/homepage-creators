+++
title = "Sink"
template = "page.html"
sort_by = "none"

[extra]
logo = "/img/icons/sink.svg"
tagline = "简洁快速的短链接服务 —— 跑在 Cloudflare 上，免费额度绰绰有余"
back_anchor = "工具"
back_label = "返回首页"
meta = ["Cloudflare", "短链接", "无服务器"]
repo = "https://github.com/miantiao-me/Sink"
repo_label = "github.com/miantiao-me/Sink"
docs = "https://sink.cool"
docs_label = "sink.cool 官方站"

highlights = [
  "自定义短码",
  "点击量与地理统计",
  "可选密码保护与过期时间",
  "Cloudflare Workers 运行，零服务器成本",
  "REST API 支持批量生成",
  "界面简洁，响应极快",
]

[[extra.scenarios]]
title = "分享链接去长尾巴"
desc = "把带一堆 tracking 参数的电商 / 文档链接压成几个字符，发出去干净好看。"

[[extra.scenarios]]
title = "看谁点了链接"
desc = "按国家、设备、来源站点统计点击量，发出去的链接有没有人看一目了然。"

[[extra.scenarios]]
title = "自用短域名"
desc = "用自己域名做短链（如 <code>s.example.com/abc</code>），比用第三方短链更可信，也不会因为是陌生域名被拦截。"

[[extra.scenarios]]
title = "给团队内部用"
desc = "支持多用户和 API，可以用脚本批量生成短链，接入自己的发布流程。"

[[extra.related]]
slug = "imgbed"
title = "Sanyue ImgHub"
desc = "无服务器图床"
logo = "/img/icons/imgbed.svg"

[[extra.related]]
slug = "rsshub"
title = "RSSHub"
desc = "万物皆可 RSS"
logo = "/img/icons/rsshub.svg"


[[extra.shots]]
src = "/img/shots/sink-1.webp"
caption = "访问统计仪表盘：点击量趋势、地理分布与来源渠道"

[[extra.shots]]
src = "/img/shots/sink-2.webp"
caption = "链接管理列表：短码、目标地址与实时点击数据"


+++

短链接服务的需求很朴素：**把长网址变短，顺便看看有多少人点了**。但市面上要么收费，要么加广告跳转页，要么哪天就关停了。

**Sink 把这件事做得很干净。** 它跑在 Cloudflare Workers 上，用 KV 存数据、Analytics Engine 记访问，完全不占服务器。支持自定义短码、密码保护、过期时间、按地理位置和来源渠道看统计。部署只要绑定一个域名，几分钟就好。
