+++
title = "个人主页"
template = "index.html"

[extra.i18n]
learn_more = "了解更多"
all_rights_reserved = "保留所有权利。"
contact_email = "联系邮箱"
theme_label = "主题"
hot = "热门"
new = "最新"

[extra.nav.message]
enable = true
text = "🎉 自托管服务与开源项目持续更新中"
url = "#services"

[extra.nav.center]
menus = [
    { name = "主页", url = "主页", internal = true },
    { name = "服务", url = "服务", internal = true },
    { name = "基础设施", url = "基础设施", internal = true },
    { name = "项目", url = "项目", internal = true },
]

[extra.nav.right]
menus = [
    { name = "Github", url = "https://github.com/unmime", internal = false },
]

[[extra.index.widgets]]
type = "header"
[extra.index.widgets.value]
title_1 = "langdon"
title_2 = "自托管爱好者"
bio_1 = "折腾自托管服务，追求<span class=\"inline-word\">数据自主</span>"
bio_2 = "记录部署与运维实践"
about_url = "#services"
cover = "/img/logo.svg"
[[extra.index.widgets.value.links]]
class_icon = " icon-github-line"
url = "https://github.com/unmime"


[[extra.index.widgets]]
type = "author"
[extra.index.widgets.value]
name = "langdon"
avatar = "/img/logo01.webp"
title = "Self-hosting enthusiast,"
bio = '''热爱自托管与开源，长期维护跨地域服务器集群，把数据和服务掌握在自己手里。关注反向代理、容器编排、自动化运维与访问优化，乐于把踩过的坑整理成可复用的方案。'''


[[extra.index.widgets]]
type = "featured-posts"
[extra.index.widgets.value]
title = "常用服务"
bio = "日常在用的自托管服务"
style = "background: linear-gradient(180deg, #f5f7fa 0%, #c3cfe2 100%);"
[[extra.index.widgets.value.columns]]
title = "🚀 主力服务"
[[extra.index.widgets.value.columns.items]]
title = "密码管理 Vaultwarden"
url = "https://pwd.zlzl.io"
[[extra.index.widgets.value.columns.items]]
title = "备忘录 Memos"
url = "https://memos.zlzl.io"
[[extra.index.widgets.value.columns.items]]
title = "AI 笔记 FlareMo"
url = "https://fm.unmi.me"
[[extra.index.widgets.value.columns]]
title = "🛠 基础设施"
[[extra.index.widgets.value.columns.items]]
title = "服务器面板 VpsCT"
url = "https://vpsct.unmi.me"
[[extra.index.widgets.value.columns.items]]
title = "图床 Sanyue ImgHub"
url = "https://img.unmi.me"
[[extra.index.widgets.value.columns.items]]
title = "短链 Sink"
url = "https://s.unmi.me"
[[extra.index.widgets.value.columns]]
title = "🌐 信息与通讯"
[[extra.index.widgets.value.columns.items]]
title = "RSS 聚合 RSSHub"
url = "https://rss.zlzl.io"
[[extra.index.widgets.value.columns.items]]
title = "邮箱 Cloud Mail"
url = "https://mail.unmi.me"
[[extra.index.widgets.value.columns.items]]
title = "Webmail Mailez"
url = "https://ml.zlzl.io"


[[extra.index.widgets]]
type = "product-list"
[extra.index.widgets.value]
title = "服务"
bio = "正在运行的自托管服务"
[[extra.index.widgets.value.items]]
logo = "/img/icons/vaultwarden.svg"
title = "Vaultwarden"
bio = "自托管密码管理器，全平台同步"
url = "https://pwd.zlzl.io"
button = "访问"
hot = true
[[extra.index.widgets.value.items]]
logo = "/img/icons/memos.svg"
title = "Memos"
bio = "轻量级自托管备忘录，随手记"
url = "https://memos.zlzl.io"
button = "访问"
[[extra.index.widgets.value.items]]
logo = "/img/icons/flaremo.svg"
title = "FlareMo"
bio = "AI 原生笔记，Memos 数据兼容"
url = "https://fm.unmi.me"
button = "访问"
new = true
[[extra.index.widgets.value.items]]
logo = "/img/icons/rsshub.svg"
title = "RSSHub"
bio = "万物皆可 RSS，为全网生成订阅源"
url = "https://rss.zlzl.io"
button = "访问"
[[extra.index.widgets.value.items]]
logo = "/img/icons/imgbed.svg"
title = "Sanyue ImgHub"
bio = "基于 Cloudflare 的无服务器图床"
url = "https://img.unmi.me"
button = "访问"
[[extra.index.widgets.value.items]]
logo = "/img/icons/sink.svg"
title = "Sink"
bio = "简洁快速的短链接服务，跑在 Cloudflare 上"
url = "https://s.unmi.me"
button = "访问"
[[extra.index.widgets.value.items]]
logo = "/img/icons/mail.svg"
title = "Cloud Mail"
bio = "自托管邮件服务，支持多域名收发"
url = "https://mail.unmi.me"
button = "访问"
[[extra.index.widgets.value.items]]
logo = "/img/icons/mailez.svg"
title = "Mailez Webmail"
bio = "轻量 Webmail 客户端，随开随用"
url = "https://ml.zlzl.io"
button = "访问"


[[extra.index.widgets]]
type = "product-list"
[extra.index.widgets.value]
title = "基础设施"
bio = "支撑上面这些服务跑起来的东西"
[[extra.index.widgets.value.items]]
logo = "/img/icons/cluster.svg"
title = "跨地域服务器集群"
bio = "六台服务器分布于美西 / 香港 / 纽约 / 洛杉矶 / 广州"
url = "https://vpsct.unmi.me"
button = "查看状态"
note = "Oracle · 香港 · 纽约 · 洛杉矶 · 广州"
hot = true
[[extra.index.widgets.value.items]]
logo = "/img/icons/vpsct.svg"
title = "VpsCT"
bio = "多机统一管理的服务器面板，所有节点统一接入"
url = "https://vpsct.unmi.me"
button = "访问"
[[extra.index.widgets.value.items]]
logo = "/img/icons/cfsm.svg"
title = "CF-Server-Monitor"
bio = "基于 Cloudflare Workers 的多服务器监控探针"
url = "https://github.com/unmime/cf-server-monitor-standalone"
button = "查看项目"
new = true


[[extra.index.widgets]]
type = "product-list"
[extra.index.widgets.value]
title = "项目"
bio = "自己写的和正在维护的开源工具"
[[extra.index.widgets.value.items]]
logo = "/img/icons/tgtool.svg"
title = "unmi_TGtool"
bio = "Telegram 机器人模块化工具箱：计算器 · 汇率 · 加密货币行情"
url = "https://github.com/unmime/unmi_TGtool"
button = "访问"
note = "可插拔 · 零依赖"
hot = true
[[extra.index.widgets.value.items]]
logo = "/img/icons/cfsm.svg"
title = "cf-server-monitor"
bio = "CF-Server-Monitor 独立部署版，一键跑起多机监控"
url = "https://github.com/unmime/cf-server-monitor-standalone"
button = "访问"
note = "Cloudflare Workers"
new = true
[[extra.index.widgets.value.items]]
logo = "/img/icons/github.svg"
title = "GitHub"
bio = "全部开源仓库与项目"
url = "https://github.com/unmime"
button = "访问"
+++
