+++
title = "Cloud Mail"
template = "page.html"
sort_by = "none"

[extra]
logo = "/img/icons/mail.svg"
tagline = "自建邮件服务 —— 用自己域名收发信，摆脱第三方邮箱"
back_anchor = "工具"
back_label = "返回首页"
meta = ["Cloudflare", "邮件服务", "多域名"]
repo = "https://github.com/maillab/cloud-mail"
repo_label = "github.com/maillab/cloud-mail"
docs = "https://github.com/maillab/cloud-mail"
docs_label = "官方 README 与部署文档"
live = "https://mail.unmi.me"

highlights = [
  "支持绑定自有域名收发",
  "多域名 / 多用户管理",
  "附件收发与转发规则",
  "前端界面清爽无广告",
  "基于 Cloudflare 运行",
  "支持 API 与自动化集成",
]

[[extra.scenarios]]
title = "用自己域名收发邮件"
desc = "如 <code>me@yourdomain.com</code>，比免费邮箱更专业，换服务商也不用改邮箱地址。"

[[extra.scenarios]]
title = "管理多域名的邮箱"
desc = "一个面板管理多个域名的收发，适合同时维护个人站、项目域名的场景。"

[[extra.scenarios]]
title = "给家人或团队开账号"
desc = "支持多用户，可以给家人分配独立邮箱，互不影响。"

[[extra.scenarios]]
title = "接收各类验证码与通知"
desc = "把注册服务、订阅通知都收到自己的邮箱，不再散落在各个平台。"

[[extra.related]]
slug = "mailez"
title = "Mailez Webmail"
desc = "轻量 Webmail 客户端"
logo = "/img/icons/mailez.svg"

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

邮箱是最难自建的服务之一，因为要处理 SMTP、IMAP、垃圾邮件过滤、SPF/DKIM/DMARC 一堆协议细节。但它也是最值得自建的 —— 邮箱里承载的验证码、账单、重要通知，几乎是你数字身份的核心。

**Cloud Mail 基于 Cloudflare 的邮件能力实现**，可以用自己的域名收发信，支持多域名、多用户、附件与转发规则。前端界面清爽，不用面对传统邮箱服务商那种广告和推荐流。
