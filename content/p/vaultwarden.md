+++
title = "Vaultwarden"
template = "page.html"
sort_by = "none"

[extra]
logo = "/img/icons/vaultwarden.svg"
tagline = "用 Rust 写的轻量 Bitwarden 服务端 —— 密码握在自己手里，还能全平台同步"
back_anchor = "精选"
back_label = "返回首页"
meta = ["Rust", "密码管理", "自托管", "~100MB 内存"]
repo = "https://github.com/dani-garcia/vaultwarden"
repo_label = "github.com/dani-garcia/vaultwarden"
docs = "https://github.com/dani-garcia/vaultwarden/wiki"
docs_label = "官方 Wiki 文档"
live = "https://pwd.zlzl.io"

highlights = [
  "兼容 Bitwarden 全部官方客户端",
  "Rust 编写，内存占用极低",
  "内置 TOTP 二次验证",
  "支持附件与密码分享",
  "SQLite / MySQL / PostgreSQL 任选",
  "Docker 一条命令启动",
]

[[extra.scenarios]]
title = "替换掉云密码本"
desc = "受够了某云密码本涨价、导出要会员、关停就丢数据。迁到 Vaultwarden 后客户端体验几乎一样，但数据在自己硬盘上。"

[[extra.scenarios]]
title = "给家人建独立账号"
desc = "自带多用户和组织功能，可以给家人各开一个账号互不干扰，也能共享一个\"家庭\"密码库。"

[[extra.scenarios]]
title = "存 API Key 和服务器密码"
desc = "自带密码生成器、自定义字段、安全笔记。运维场景下把 SSH 密钥、API Token、数据库密码集中管理。"

[[extra.scenarios]]
title = "浏览器扩展自动填充"
desc = "装官方 Bitwarden 扩展，指向自己的服务器地址，从此登录全部自动填充，跨设备同步。"

[[extra.related]]
slug = "memos"
title = "Memos"
desc = "随手记点什么"
logo = "/img/icons/memos.svg"

[[extra.related]]
slug = "rsshub"
title = "RSSHub"
desc = "万物皆可 RSS"
logo = "/img/icons/rsshub.svg"

[[extra.related]]
slug = "flaremo"
title = "FlareMo"
desc = "AI 原生笔记"
logo = "/img/icons/flaremo.svg"
+++

市面上密码管理器很多，但大部分把你的密码库放在别人的服务器上。**Vaultwarden 是 Bitwarden 的第三方开源服务端实现**，用 Rust 重写，保留了 Bitwarden 全部官方客户端（iOS / Android / macOS / Windows / 浏览器扩展 / CLI），但服务端极轻。

它最大的价值在于：你可以用**官方 App**，但数据存在自己的服务器上。同步、自动填充、密码分享、TOTP 二次验证、附件存储这些功能一个不少，而内存占用只要一百多 MB —— 树莓派、最低配的 VPS 都能跑。
