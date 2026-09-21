+++
title = "One IP"
template = "page.html"
sort_by = "none"

[extra]
logo = "/img/icons/oneip.svg"
tagline = "IP 查询、网络诊断、浏览器检测与 AI 服务状态，一个页面看完"
back_anchor = "精选"
back_label = "返回首页"
meta = ["React 19", "TypeScript", "Cloudflare Workers", "自研"]
live = "https://1ip.unmi.me"

highlights = [
  "IP 查询：归属地 / ASN / 运营商",
  "端口与域名连通性诊断",
  "浏览器指纹与隐私检测",
  "AI 服务可用性批量检查",
  "纯前端 + Workers，零服务器成本",
  "界面清爽，移动端可用",
]

[[extra.scenarios]]
title = "快速定位自己的出口 IP"
desc = "查当前公网 IP、归属地、ASN 运营商，切换代理后可立即确认是否走了预期线路。"

[[extra.scenarios]]
title = "诊断服务连通性"
desc = "批量测端口 / 域名是否可达，判断\"网站打不开\"是自己网络问题还是对方挂了。"

[[extra.scenarios]]
title = "检查浏览器指纹泄露"
desc = "看浏览器暴露了哪些设备与网络特征，评估隐私暴露面。"

[[extra.scenarios]]
title = "AI 服务可用性检查"
desc = "一键测试常见 AI 服务在当前网络下是否可用，省去逐个打开试的时间。"

[[extra.related]]
slug = "vpsct"
title = "VpsCT"
desc = "服务器面板"
logo = "/img/icons/vpsct.svg"

[[extra.related]]
slug = "sink"
title = "Sink"
desc = "短链接服务"
logo = "/img/icons/sink.svg"

[[extra.related]]
slug = "rsshub"
title = "RSSHub"
desc = "万物皆可 RSS"
logo = "/img/icons/rsshub.svg"
+++

排查网络问题时，通常要在好几个网站之间来回跳：一个查 IP 归属地、一个测端口连通性、一个看浏览器指纹、一个试 AI 服务通不通。

**One IP 把这些工具整合进了一个页面。** 纯前端架构 + Cloudflare Workers 做后端代理，没有服务器成本。打开就知道自己在哪、网络通不通、对方服务活着没、自己的浏览器暴露了多少信息。

这个项目是我自己写的，目前**源码暂未公开**，但服务本身对外开放，可以直接使用。
