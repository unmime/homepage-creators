+++
title = "Open Source Picks"
template = "index.html"

[extra.i18n]
learn_more = "Learn More"
all_rights_reserved = "All rights reserved."
contact_email = "Email"
theme_label = "Theme"
hot = "Pick"
new = "New"

[extra.nav.message]
enable = true
text = "🎉 Open-source projects I use every day, all in one place"
url = "#精选"

[extra.nav.center]
menus = [
    { name = "Home", url = "Home", internal = true },
    { name = "Picks", url = "Picks", internal = true },
    { name = "Tools", url = "Tools", internal = true },
    { name = "Self-hosted", url = "Self-hosted", internal = true },
]

[extra.nav.right]
menus = [
    { name = "GitHub", url = "https://github.com/unmime", internal = false },
]

[[extra.index.widgets]]
type = "header"
[extra.index.widgets.value]
title_1 = "Open Source Picks"
title_2 = "Sharing what I use"
bio_1 = "Sharing the <span class=\"inline-word\">open-source projects</span> I use"
bio_2 = "and some genuinely fun stuff"
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
bio = '''I run a pile of open-source projects on my own servers, and everything I actually liked ended up here. Two rules only: I should own my data, and maintenance should stay cheap. I also write down the pitfalls and configs I hit along the way — hope some of it helps you.'''


[[extra.index.widgets]]
type = "featured-posts"
[extra.index.widgets.value]
title = "Top Picks"
bio = "If you only try a few, start here"
style = "background: linear-gradient(180deg, #f5f7fa 0%, #c3cfe2 100%);"
[[extra.index.widgets.value.columns]]
title = "⭐ Most Recommended"
[[extra.index.widgets.value.columns.items]]
title = "Vaultwarden — own your passwords"
url = "https://pwd.zlzl.io"
[[extra.index.widgets.value.columns.items]]
title = "Memos — just jot things down"
url = "https://memos.zlzl.io"
[[extra.index.widgets.value.columns.items]]
title = "RSSHub — RSS for everything"
url = "https://rss.zlzl.io"
[[extra.index.widgets.value.columns]]
title = "🧰 Handy Tools"
[[extra.index.widgets.value.columns.items]]
title = "One IP — IP & network diagnostics"
url = "https://1ip.unmi.me"
[[extra.index.widgets.value.columns.items]]
title = "Sink — URL shortener"
url = "https://s.unmi.me"
[[extra.index.widgets.value.columns.items]]
title = "Sanyue ImgHub — image host"
url = "https://img.unmi.me"
[[extra.index.widgets.value.columns]]
title = "🏠 Self-hosted"
[[extra.index.widgets.value.columns.items]]
title = "VpsCT — server panel"
url = "https://vpsct.unmi.me"
[[extra.index.widgets.value.columns.items]]
title = "Cloud Mail — mail service"
url = "https://mail.unmi.me"
[[extra.index.widgets.value.columns.items]]
title = "FlareMo — AI-native notes"
url = "https://fm.unmi.me"


[[extra.index.widgets]]
type = "product-list"
[extra.index.widgets.value]
title = "Picks"
bio = "Open-source projects I use and would happily recommend"
[[extra.index.widgets.value.items]]
logo = "/img/icons/vaultwarden.svg"
title = "Vaultwarden"
bio = "A lightweight Bitwarden server written in Rust. Syncs across phone, desktop and browser while your passwords stay with you — a few hundred MB of RAM, runs on a Raspberry Pi"
url = "https://pwd.zlzl.io"
button = "Visit"
note = "Rust · Password manager"
hot = true
[[extra.index.widgets.value.items]]
logo = "/img/icons/memos.svg"
title = "Memos"
bio = "Note-taking stripped to the essentials. Open it and write — no folders, no titles required, more like posting to your own feed. Plain Markdown, portable any time"
url = "https://memos.zlzl.io"
button = "Visit"
note = "Go · Notes"
hot = true
[[extra.index.widgets.value.items]]
logo = "/img/icons/rsshub.svg"
title = "RSSHub"
bio = "Turns the whole internet into RSS. Weibo, Bilibili, Zhihu, Xiaohongshu, podcasts — almost any site without a feed gets one generated for you"
url = "https://rss.zlzl.io"
button = "Visit"
note = "Node · Feed aggregation"
hot = true
[[extra.index.widgets.value.items]]
logo = "/img/icons/oneip.svg"
title = "One IP"
bio = "A network toolbox I built myself: IP lookup, connectivity diagnosis, browser fingerprint check and AI-service availability, all on one page. Pure frontend + Workers, zero cost"
url = "https://1ip.unmi.me"
button = "Visit"
note = "React + Workers · My own"
new = true


[[extra.index.widgets]]
type = "product-list"
[extra.index.widgets.value]
title = "Tools"
bio = "Small tools that speed up the daily grind"
[[extra.index.widgets.value.items]]
logo = "/img/icons/sink.svg"
title = "Sink"
bio = "A URL shortener on Cloudflare. The free tier is plenty, with custom slugs, click analytics and geo breakdowns — deploys in minutes"
url = "https://s.unmi.me"
button = "Visit"
note = "Cloudflare · Link shortener"
[[extra.index.widgets.value.items]]
logo = "/img/icons/imgbed.svg"
title = "Sanyue ImgHub"
bio = "Serverless image hosting on Cloudflare, no server resources consumed. Works with PicGo-style tools for one-click uploads — great for illustrations in blog posts"
url = "https://img.unmi.me"
button = "Visit"
note = "Cloudflare · Image host"
[[extra.index.widgets.value.items]]
logo = "/img/icons/mail.svg"
title = "Cloud Mail"
bio = "Self-hosted mail service you can bind to your own domain for sending and receiving. Multi-domain, multi-user, with a clean frontend — a real way out of third-party inboxes"
url = "https://mail.unmi.me"
button = "Visit"
note = "Mail service"
[[extra.index.widgets.value.items]]
logo = "/img/icons/mailez.svg"
title = "Mailez Webmail"
bio = "A lightweight webmail client, ready whenever you open it. If you already run a mail server but lack a decent web UI, this plugs straight in"
url = "https://ml.zlzl.io"
button = "Visit"
note = "Webmail"
[[extra.index.widgets.value.items]]
logo = "/img/icons/flaremo.svg"
title = "FlareMo"
bio = "An AI-native note app with data compatible with Memos. If you want AI in your notes without migrating existing data, it is a smooth upgrade path"
url = "https://fm.unmi.me"
button = "Visit"
note = "AI notes"
new = true


[[extra.index.widgets]]
type = "product-list"
[extra.index.widgets.value]
title = "Self-hosted"
bio = "If you want to run your own services too"
[[extra.index.widgets.value.items]]
logo = "/img/icons/vpsct.svg"
title = "VpsCT"
bio = "A control panel for managing multiple servers at once. One panel for every node — check status, run commands, install agents, all in a single interface"
url = "https://vpsct.unmi.me"
button = "Visit"
note = "Server management"
[[extra.index.widgets.value.items]]
logo = "/img/icons/cluster.svg"
title = "Multi-region Fleet"
bio = "I built a self-hosting environment on six machines across US West, Hong Kong, New York, Los Angeles and Guangzhou — every node wired into the same panel"
url = "https://vpsct.unmi.me"
button = "View Status"
note = "Oracle · Hong Kong · New York · Los Angeles · Guangzhou"
[[extra.index.widgets.value.items]]
logo = "/img/icons/cfsm.svg"
title = "CF-Server-Monitor"
bio = "Server monitoring probes running on Cloudflare Workers, free tier is enough. Real-time monitoring, offline alerts, historical data and latency tracking"
url = "https://github.com/unmime/cf-server-monitor-standalone"
button = "Learn More"
note = "Cloudflare · Monitoring"
new = true


[[extra.index.widgets]]
type = "product-list"
[extra.index.widgets.value]
title = "My Projects"
bio = "Open-source projects I wrote and maintain"
[[extra.index.widgets.value.items]]
logo = "/img/icons/tgtool.svg"
title = "unmi_TGtool"
bio = "A modular Telegram bot toolkit: calculator, FX conversion, crypto quotes. Pluggable modules with zero dependencies — add a feature by dropping in a module"
url = "https://github.com/unmime/unmi_TGtool"
button = "View Source"
note = "Python · Pluggable"
hot = true
[[extra.index.widgets.value.items]]
logo = "/img/icons/oneip.svg"
title = "One IP"
bio = "IP lookup, network diagnostics, browser detection and AI-service status toolbox. React 19 + TypeScript + Cloudflare Workers, pure frontend at zero server cost"
url = "https://1ip.unmi.me"
button = "Try Online"
note = "React + Workers"
new = true
[[extra.index.widgets.value.items]]
logo = "/img/icons/cfsm.svg"
title = "cf-server-monitor"
bio = "A standalone deployment of CF-Server-Monitor. The original was tied to a specific environment; this version is decoupled so you can deploy it to your own Cloudflare account in one step"
url = "https://github.com/unmime/cf-server-monitor-standalone"
button = "View Source"
note = "Cloudflare Workers"
new = true
[[extra.index.widgets.value.items]]
logo = "/img/icons/games.svg"
title = "neon-games"
bio = "A pure frontend mini-game collection: 2048, Breakout, Flappy Bird, piano, Tetris, typing practice. Just open and play — no ads, no sign-in"
url = "https://github.com/unmime/neon-games"
button = "View Source"
note = "HTML · Mini games"
[[extra.index.widgets.value.items]]
logo = "/img/icons/github.svg"
title = "GitHub"
bio = "All repositories and projects live here"
url = "https://github.com/unmime"
button = "Visit"
+++
