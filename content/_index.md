+++
title = "开源分享"
template = "index.html"

[extra.i18n]
learn_more = "了解更多"
all_rights_reserved = "保留所有权利。"
contact_email = "联系邮箱"
theme_label = "主题"
hot = "推荐"
new = "新"

[extra.nav.message]
enable = true
text = "🎉 我日常在用的开源项目，都整理在这里了"
url = "#精选"

[extra.nav.center]
menus = [
    { name = "首页", url = "首页", internal = true },
    { name = "精选", url = "精选", internal = true },
    { name = "工具", url = "工具", internal = true },
    { name = "自建", url = "自建", internal = true },
]

[extra.nav.right]
menus = [
    { name = "GitHub", url = "https://github.com/unmime", internal = false },
]

[[extra.index.widgets]]
type = "header"
[extra.index.widgets.value]
title_1 = "开源分享"
title_2 = "Open Source Picks"
bio_1 = "分享我在用的<span class=\"inline-word\">开源项目</span>"
bio_2 = "以及一些有趣的东西"
about_url = "#精选"
cover = "/img/logo.svg"
[[extra.index.widgets.value.links]]
class_icon = " icon-github-line"
url = "https://github.com/unmime"


[[extra.index.widgets]]
type = "author"
[extra.index.widgets.value]
name = "langdon"
avatar = "/img/logo01.webp"
title = "Self-hoster & open-source enthusiast,"
bio = '''我在自己的服务器上跑了一堆开源项目，用下来觉得好用的都放这里了。原则只有两条：数据能自己掌握、维护成本足够低。踩过的坑和配置方案也一并整理，希望对你有点用。'''


[[extra.index.widgets]]
type = "featured-posts"
[extra.index.widgets.value]
title = "精选推荐"
bio = "如果只挑几个试试，从这里开始"
style = "background: linear-gradient(180deg, #f5f7fa 0%, #c3cfe2 100%);"
[[extra.index.widgets.value.columns]]
title = "⭐ 最推荐"
[[extra.index.widgets.value.columns.items]]
title = "Vaultwarden — 密码自己管"
url = "https://pwd.zlzl.io"
[[extra.index.widgets.value.columns.items]]
title = "Memos — 随手记点什么"
url = "https://memos.zlzl.io"
[[extra.index.widgets.value.columns.items]]
title = "RSSHub — 万物皆可 RSS"
url = "https://rss.zlzl.io"
[[extra.index.widgets.value.columns]]
title = "🧰 实用工具"
[[extra.index.widgets.value.columns.items]]
title = "One IP — IP 与网络诊断"
url = "https://1ip.unmi.me"
[[extra.index.widgets.value.columns.items]]
title = "Sink — 短链接"
url = "https://s.unmi.me"
[[extra.index.widgets.value.columns.items]]
title = "Sanyue ImgHub — 图床"
url = "https://img.unmi.me"
[[extra.index.widgets.value.columns]]
title = "🏠 自建服务"
[[extra.index.widgets.value.columns.items]]
title = "VpsCT — 服务器面板"
url = "https://vpsct.unmi.me"
[[extra.index.widgets.value.columns.items]]
title = "Cloud Mail — 邮件服务"
url = "https://mail.unmi.me"
[[extra.index.widgets.value.columns.items]]
title = "FlareMo — AI 笔记"
url = "https://fm.unmi.me"


[[extra.index.widgets]]
type = "product-list"
[extra.index.widgets.value]
title = "精选"
bio = "我在用，并且愿意推荐给别人的开源项目"
[[extra.index.widgets.value.items]]
logo = "/img/icons/vaultwarden.svg"
title = "Vaultwarden"
bio = "用 Rust 写的轻量 Bitwarden 服务端。手机 / 电脑 / 浏览器全平台同步，密码握在自己手里。内存占用只有几百 MB，树莓派都能跑"
url = "https://pwd.zlzl.io"
button = "访问"
note = "Rust · 密码管理"
hot = true
[[extra.index.widgets.value.items]]
logo = "/img/icons/memos.svg"
title = "Memos"
bio = "轻量到极致的备忘录。打开就写，不需要建文件夹、不需要起标题，像发微博一样记录。数据是纯 Markdown，随时能搬走"
url = "https://memos.zlzl.io"
button = "访问"
note = "Go · 笔记"
hot = true
[[extra.index.widgets.value.items]]
logo = "/img/icons/rsshub.svg"
title = "RSSHub"
bio = "把整个互联网变成 RSS。微博、B站、知乎、小红书、播客……几乎所有没有订阅功能的网站，它都能给你生成一个源"
url = "https://rss.zlzl.io"
button = "访问"
note = "Node · 信息聚合"
hot = true
[[extra.index.widgets.value.items]]
logo = "/img/icons/oneip.svg"
title = "One IP"
bio = "自己写的网络工具箱：IP 查询、连通性诊断、浏览器指纹检测、AI 服务可用性检查，一个页面看完。纯前端 + Workers，零成本"
url = "https://1ip.unmi.me"
button = "访问"
note = "React + Workers · 自研"
new = true


[[extra.index.widgets]]
type = "product-list"
[extra.index.widgets.value]
title = "工具"
bio = "提升日常效率的小工具"
[[extra.index.widgets.value.items]]
logo = "/img/icons/sink.svg"
title = "Sink"
bio = "跑在 Cloudflare 上的短链接服务。免费额度内完全够用，支持自定义短码、访问统计、地理位置分析，部署只要几分钟"
url = "https://s.unmi.me"
button = "访问"
note = "Cloudflare · 短链"
[[extra.index.widgets.value.items]]
logo = "/img/icons/imgbed.svg"
title = "Sanyue ImgHub"
bio = "基于 Cloudflare 的无服务器图床，不占服务器资源。配合 PicGo 之类的工具可以一键上传，写博客插图很方便"
url = "https://img.unmi.me"
button = "访问"
note = "Cloudflare · 图床"
[[extra.index.widgets.value.items]]
logo = "/img/icons/mail.svg"
title = "Cloud Mail"
bio = "自建邮件服务，可以绑定自己的域名收发信。支持多域名、多用户，前端界面清爽，适合摆脱第三方邮箱"
url = "https://mail.unmi.me"
button = "访问"
note = "邮件服务"
[[extra.index.widgets.value.items]]
logo = "/img/icons/mailez.svg"
title = "Mailez Webmail"
bio = "轻量 Webmail 客户端，随开随用。如果你已经有邮件服务器但缺个好用的网页端，这个可以直接接上"
url = "https://ml.zlzl.io"
button = "访问"
note = "Webmail"
[[extra.index.widgets.value.items]]
logo = "/img/icons/flaremo.svg"
title = "FlareMo"
bio = "AI 原生的笔记应用，数据格式兼容 Memos。想给笔记加 AI 能力又不想换掉已有数据的话，它是个平滑的升级路径"
url = "https://fm.unmi.me"
button = "访问"
note = "AI 笔记"
new = true


[[extra.index.widgets]]
type = "product-list"
[extra.index.widgets.value]
title = "自建"
bio = "如果你也想把自己的服务跑起来"
[[extra.index.widgets.value.items]]
logo = "/img/icons/vpsct.svg"
title = "VpsCT"
bio = "多台服务器统一管理的控制面板。一台面板管所有节点，看状态、执行命令、装 agent 都在一个界面完成"
url = "https://vpsct.unmi.me"
button = "访问"
note = "服务器管理"
[[extra.index.widgets.value.items]]
logo = "/img/icons/cluster.svg"
title = "跨地域服务器集群"
bio = "我用六台不同机房的机器搭了一套自托管环境，分布在美西、香港、纽约、洛杉矶、广州。所有节点都接进了同一套面板管理"
url = "https://vpsct.unmi.me"
button = "查看状态"
note = "Oracle · 香港 · 纽约 · 洛杉矶 · 广州"
[[extra.index.widgets.value.items]]
logo = "/img/icons/cfsm.svg"
title = "CF-Server-Monitor"
bio = "跑在 Cloudflare Workers 上的服务器监控探针，免费额度足够。支持实时监控、离线告警、历史数据和延迟追踪"
url = "https://github.com/unmime/cf-server-monitor-standalone"
button = "了解详情"
note = "Cloudflare · 监控"
new = true


[[extra.index.widgets]]
type = "product-list"
[extra.index.widgets.value]
title = "自研"
bio = "自己写和维护的开源项目"
[[extra.index.widgets.value.items]]
logo = "/img/icons/tgtool.svg"
title = "unmi_TGtool"
bio = "Telegram 机器人模块化工具箱：计算器、汇率换算、加密货币行情。模块可插拔、零依赖，想加功能直接写个模块丢进去"
url = "https://github.com/unmime/unmi_TGtool"
button = "查看源码"
note = "Python · 可插拔"
hot = true
[[extra.index.widgets.value.items]]
logo = "/img/icons/oneip.svg"
title = "One IP"
bio = "IP 查询、网络诊断、浏览器检测与 AI 服务状态工具箱。React 19 + TypeScript + Cloudflare Workers，纯前端架构，零服务器成本"
url = "https://1ip.unmi.me"
button = "在线体验"
note = "React + Workers"
new = true
[[extra.index.widgets.value.items]]
logo = "/img/icons/cfsm.svg"
title = "cf-server-monitor"
bio = "CF-Server-Monitor 的独立部署版本。原项目绑定了特定环境，这个版本脱钩出来，可以一键部署到自己的 Cloudflare 账号"
url = "https://github.com/unmime/cf-server-monitor-standalone"
button = "查看源码"
note = "Cloudflare Workers"
new = true
[[extra.index.widgets.value.items]]
logo = "/img/icons/games.svg"
title = "neon-games"
bio = "一个纯前端小游戏合集：2048、打砖块、Flappy Bird、钢琴、俄罗斯方块、打字练习。打开就能玩，没有广告没有登录"
url = "https://github.com/unmime/neon-games"
button = "查看源码"
note = "HTML · 小游戏"
[[extra.index.widgets.value.items]]
logo = "/img/icons/github.svg"
title = "GitHub"
bio = "全部开源仓库与项目都在这里"
url = "https://github.com/unmime"
button = "访问"
+++
