+++
title = "Mailez Webmail"
template = "page.html"
sort_by = "none"

[extra]
logo = "/img/icons/mailez.svg"
tagline = "轻量 Webmail 客户端 —— 已经有邮件服务器，就差个好用的网页端"
back_anchor = "工具"
back_label = "返回首页"
meta = ["Webmail", "轻量", "纯前端"]
repo = "https://github.com/mailez-hq/mailez"
repo_label = "github.com/mailez-hq/mailez"
docs = "https://mailez.net"
docs_label = "mailez.net 官方站"
live = "https://ml.zlzl.io"

highlights = [
  "轻量快速，打开即用",
  "支持键盘快捷键",
  "移动端适配良好",
  "对接标准 IMAP / SMTP",
  "界面简洁无广告",
  "无需安装客户端",
]

[[extra.scenarios]]
title = "给自建邮件服务器配网页端"
desc = "已有 SMTP/IMAP 服务，接上 Mailez 就有网页收发信界面，不用装客户端。"

[[extra.scenarios]]
title = "手机上随时查邮箱"
desc = "浏览器打开即用，不需要在手机上装额外的邮件 App。"

[[extra.scenarios]]
title = "键盘流用户"
desc = "支持快捷键操作，翻信、回复、删除都能手不离键盘完成。"

[[extra.scenarios]]
title = "多账号统一查看"
desc = "可以配置多个邮件账号，在一个界面里切换查看。"

[[extra.related]]
slug = "cloud-mail"
title = "Cloud Mail"
desc = "自建邮件服务"
logo = "/img/icons/mail.svg"

[[extra.related]]
slug = "vaultwarden"
title = "Vaultwarden"
desc = "密码自己管"
logo = "/img/icons/vaultwarden.svg"

[[extra.related]]
slug = "memos"
title = "Memos"
desc = "随手记点什么"
logo = "/img/icons/memos.svg"
+++

很多人已经搭好了邮件服务器（或者用上了 Cloud Mail 这类服务），但缺一个**顺手的网页端**：命令行看邮件太痛苦，第三方客户端又要配置一堆 IMAP 参数。

**Mailez 是个轻量 Webmail 客户端**，接上已有的邮件服务器就能用。界面简洁、加载快、支持键盘快捷键，移动端也能正常阅读和回复。它不重复造邮件服务，而是专注把"读信写信"这件事做好。
