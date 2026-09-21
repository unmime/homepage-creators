+++
title = "Homepage"
template = "index.html"

[extra.i18n]
learn_more = "Learn More"
all_rights_reserved = "All rights reserved."
contact_email = "Email"
theme_label = "Theme"
hot = "Hot"
new = "New"

[extra.nav.message]
enable = true
text = "🎉 Self-hosted services and open-source projects, continuously updated"
url = "#services"

[extra.nav.center]
menus = [
    { name = "Home", url = "Home", internal = true },
    { name = "Services", url = "Services", internal = true },
    { name = "Infrastructure", url = "Infrastructure", internal = true },
    { name = "Projects", url = "Projects", internal = true },
]

[extra.nav.right]
menus = [
    { name = "Github", url = "https://github.com/unmime", internal = false },
]

[[extra.index.widgets]]
type = "header"
[extra.index.widgets.value]
title_1 = "langdon"
title_2 = "Self-hosting enthusiast"
bio_1 = "Tinkering with self-hosted services, chasing <span class=\"inline-word\">data ownership</span>"
bio_2 = "Notes on deployment and operations"
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
bio = '''Passionate about self-hosting and open source, maintaining a multi-region server fleet and keeping data and services under my own control. Focused on reverse proxies, container orchestration, automated operations and access optimization — and I like turning hard-won lessons into reusable solutions.'''


[[extra.index.widgets]]
type = "featured-posts"
[extra.index.widgets.value]
title = "Daily Services"
bio = "Self-hosted services I use every day"
style = "background: linear-gradient(180deg, #f5f7fa 0%, #c3cfe2 100%);"
[[extra.index.widgets.value.columns]]
title = "🚀 Core"
[[extra.index.widgets.value.columns.items]]
title = "Vaultwarden Password Manager"
url = "https://pwd.zlzl.io"
[[extra.index.widgets.value.columns.items]]
title = "Memos"
url = "https://memos.zlzl.io"
[[extra.index.widgets.value.columns.items]]
title = "FlareMo AI Notes"
url = "https://fm.unmi.me"
[[extra.index.widgets.value.columns]]
title = "🛠 Infrastructure"
[[extra.index.widgets.value.columns.items]]
title = "VpsCT Server Panel"
url = "https://vpsct.unmi.me"
[[extra.index.widgets.value.columns.items]]
title = "Sanyue ImgHub"
url = "https://img.unmi.me"
[[extra.index.widgets.value.columns.items]]
title = "Sink URL Shortener"
url = "https://s.unmi.me"
[[extra.index.widgets.value.columns]]
title = "🌐 Feeds & Mail"
[[extra.index.widgets.value.columns.items]]
title = "RSSHub"
url = "https://rss.zlzl.io"
[[extra.index.widgets.value.columns.items]]
title = "Cloud Mail"
url = "https://mail.unmi.me"
[[extra.index.widgets.value.columns.items]]
title = "Mailez Webmail"
url = "https://ml.zlzl.io"


[[extra.index.widgets]]
type = "product-list"
[extra.index.widgets.value]
title = "Services"
bio = "Self-hosted services currently running"
[[extra.index.widgets.value.items]]
logo = "/img/icons/vaultwarden.svg"
title = "Vaultwarden"
bio = "Self-hosted password manager with cross-platform sync"
url = "https://pwd.zlzl.io"
button = "Visit"
hot = true
[[extra.index.widgets.value.items]]
logo = "/img/icons/memos.svg"
title = "Memos"
bio = "Lightweight self-hosted note-taking"
url = "https://memos.zlzl.io"
button = "Visit"
[[extra.index.widgets.value.items]]
logo = "/img/icons/flaremo.svg"
title = "FlareMo"
bio = "AI-native notes, Memos-compatible data"
url = "https://fm.unmi.me"
button = "Visit"
new = true
[[extra.index.widgets.value.items]]
logo = "/img/icons/rsshub.svg"
title = "RSSHub"
bio = "Make the whole web RSS-feedable"
url = "https://rss.zlzl.io"
button = "Visit"
[[extra.index.widgets.value.items]]
logo = "/img/icons/imgbed.svg"
title = "Sanyue ImgHub"
bio = "Serverless image hosting on Cloudflare"
url = "https://img.unmi.me"
button = "Visit"
[[extra.index.widgets.value.items]]
logo = "/img/icons/sink.svg"
title = "Sink"
bio = "Simple, speedy, secure URL shortener on Cloudflare"
url = "https://s.unmi.me"
button = "Visit"
[[extra.index.widgets.value.items]]
logo = "/img/icons/mail.svg"
title = "Cloud Mail"
bio = "Self-hosted mail service with multi-domain support"
url = "https://mail.unmi.me"
button = "Visit"
[[extra.index.widgets.value.items]]
logo = "/img/icons/mailez.svg"
title = "Mailez Webmail"
bio = "Lightweight webmail client, ready when you are"
url = "https://ml.zlzl.io"
button = "Visit"


[[extra.index.widgets]]
type = "product-list"
[extra.index.widgets.value]
title = "Infrastructure"
bio = "What keeps all of the above running"
[[extra.index.widgets.value.items]]
logo = "/img/icons/cluster.svg"
title = "Multi-region Server Fleet"
bio = "Six servers across US West / Hong Kong / New York / Los Angeles / Guangzhou"
url = "https://vpsct.unmi.me"
button = "View Status"
note = "Oracle · Hong Kong · New York · Los Angeles · Guangzhou"
hot = true
[[extra.index.widgets.value.items]]
logo = "/img/icons/vpsct.svg"
title = "VpsCT"
bio = "Unified multi-host server management panel"
url = "https://vpsct.unmi.me"
button = "Visit"
[[extra.index.widgets.value.items]]
logo = "/img/icons/cfsm.svg"
title = "CF-Server-Monitor"
bio = "Multi-server monitoring probes on Cloudflare Workers"
url = "https://github.com/unmime/cf-server-monitor-standalone"
button = "View Project"
new = true


[[extra.index.widgets]]
type = "product-list"
[extra.index.widgets.value]
title = "Projects"
bio = "Open-source tools I built and maintain"
[[extra.index.widgets.value.items]]
logo = "/img/icons/tgtool.svg"
title = "unmi_TGtool"
bio = "Modular Telegram bot toolkit: calculator · FX · crypto quotes"
url = "https://github.com/unmime/unmi_TGtool"
button = "Visit"
note = "Pluggable · zero-dependency"
hot = true
[[extra.index.widgets.value.items]]
logo = "/img/icons/cfsm.svg"
title = "cf-server-monitor"
bio = "Standalone CF-Server-Monitor deployment for quick multi-host monitoring"
url = "https://github.com/unmime/cf-server-monitor-standalone"
button = "Visit"
note = "Cloudflare Workers"
new = true
[[extra.index.widgets.value.items]]
logo = "/img/icons/github.svg"
title = "GitHub"
bio = "All repositories and projects"
url = "https://github.com/unmime"
button = "Visit"
+++
