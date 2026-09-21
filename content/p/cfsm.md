+++
title = "CF-Server-Monitor"
template = "page.html"
sort_by = "none"

[extra]
logo = "/img/icons/cfsm.svg"
tagline = "跑在 Cloudflare Workers 上的免费服务器监控 —— 离线自动告警"
back_anchor = "自建"
back_label = "返回首页"
meta = ["Cloudflare Workers", "监控", "D1", "Durable Objects"]
repo = "https://github.com/huilang-me/CF-Server-Monitor"
repo_label = "github.com/huilang-me/CF-Server-Monitor"
docs = "https://demo.huilang.me"
docs_label = "官方演示站"

highlights = [
  "实时监控与离线告警",
  "Telegram / Webhook 通知",
  "历史数据与延迟追踪",
  "到期自动提醒",
  "Cloudflare 免费额度可用",
  "支持一键部署独立版本",
]

[[extra.scenarios]]
title = "监控多台 VPS 存活"
desc = "每台机器装一个轻量探针，掉线立刻收到告警，不用等自己发现。"

[[extra.scenarios]]
title = "追踪网络延迟变化"
desc = "记录历史延迟数据，能看出某条线路什么时候开始变差。"

[[extra.scenarios]]
title = "服务到期提醒"
desc = "服务器 / 域名快到期时自动提醒，避免忘记续费导致服务中断。"

[[extra.scenarios]]
title = "零成本的监控方案"
desc = "Cloudflare 免费额度足够个人使用，不用额外买监控服务或开机器。"

[[extra.related]]
slug = "vpsct"
title = "VpsCT"
desc = "服务器面板"
logo = "/img/icons/vpsct.svg"

[[extra.related]]
slug = "oneip"
title = "One IP"
desc = "网络工具箱"
logo = "/img/icons/oneip.svg"

[[extra.related]]
slug = "tgtool"
title = "unmi_TGtool"
desc = "TG 工具箱"
logo = "/img/icons/tgtool.svg"
+++

传统服务器监控要么自建一套 Prometheus + Grafana（资源消耗不小），要么买商业服务（按探针数量收费）。如果只是想**知道机器活着没有、延迟多少、什么时候掉线**，这两条路都太重。

**CF-Server-Monitor 把监控做在 Cloudflare Workers 上。** 利用 Workers + D1 + Durable Objects 实现探针调度和数据存储，**免费额度就能覆盖个人使用**。支持实时监控、离线告警、到期提醒、历史数据回看和延迟追踪，掉线会主动推送到 Telegram 或 Webhook。
