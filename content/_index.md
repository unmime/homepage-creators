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
text = "🎉 自托管服务已全部上线"
url = "#services"

[extra.nav.center]
menus = [
    { name = "主页", url = "主页", internal = true },
    { name = "服务", url = "服务", internal = true },
    { name = "自托管", url = "自托管", internal = true },
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
title = "RSS 阅读 FreshRSS"
url = "https://rss.zlzl.io"
[[extra.index.widgets.value.columns]]
title = "🛠 基础能力"
[[extra.index.widgets.value.columns.items]]
title = "服务器管理面板 VpsCT"
url = "https://vpsct.unmi.me"
[[extra.index.widgets.value.columns.items]]
title = "图床 CloudFlare-ImgBed"
url = "https://img.unmi.me"
[[extra.index.widgets.value.columns.items]]
title = "笔记 FlareMo"
url = "https://fm.unmi.me"
[[extra.index.widgets.value.columns]]
title = "🌐 开源项目"
[[extra.index.widgets.value.columns.items]]
title = "Telegram 工具箱 unmi_TGtool"
url = "https://github.com/unmime/unmi_TGtool"
[[extra.index.widgets.value.columns.items]]
title = "GitHub 主页"
url = "https://github.com/unmime"


[[extra.index.widgets]]
type = "product-list"
[extra.index.widgets.value]
title = "服务"
bio = "正在运行的自托管服务"
[[extra.index.widgets.value.items]]
logo = "/img/internet.svg"
title = "Vaultwarden"
bio = "自托管密码管理器，全平台同步"
url = "https://pwd.zlzl.io"
button = "访问"
hot = true
[[extra.index.widgets.value.items]]
logo = "/img/internet.svg"
title = "Memos"
bio = "轻量级自托管备忘录，随手记"
url = "https://memos.zlzl.io"
button = "访问"
[[extra.index.widgets.value.items]]
logo = "/img/internet.svg"
title = "FreshRSS"
bio = "自托管 RSS 阅读器，信息流自主掌控"
url = "https://rss.zlzl.io"
button = "访问"
[[extra.index.widgets.value.items]]
logo = "/img/internet.svg"
title = "VpsCT"
bio = "多机统一管理的服务器面板"
url = "https://vpsct.unmi.me"
button = "访问"
note = "服务器管理"
[[extra.index.widgets.value.items]]
logo = "/img/internet.svg"
title = "CloudFlare-ImgBed"
bio = "基于 Cloudflare 的无服务器图床"
url = "https://img.unmi.me"
button = "访问"
[[extra.index.widgets.value.items]]
logo = "/img/internet.svg"
title = "FlareMo"
bio = "AI 原生笔记，Memos 兼容"
url = "https://fm.unmi.me"
button = "访问"
new = true


[[extra.index.widgets]]
type = "product-list"
[extra.index.widgets.value]
title = "项目"
bio = "自己写的和正在维护的开源工具"
[[extra.index.widgets.value.items]]
logo = "/img/internet.svg"
title = "unmi_TGtool"
bio = "Telegram 机器人模块化工具箱"
url = "https://github.com/unmime/unmi_TGtool"
button = "访问"
note = "可插拔、零依赖"
hot = true
[[extra.index.widgets.value.items]]
logo = "/img/internet.svg"
title = "GitHub"
bio = "全部开源仓库与项目"
url = "https://github.com/unmime"
button = "访问"
+++
