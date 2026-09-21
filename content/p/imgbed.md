+++
title = "Sanyue ImgHub"
template = "page.html"
sort_by = "none"

[extra]
logo = "/img/icons/imgbed.svg"
tagline = "基于 Cloudflare 的无服务器图床 —— 不占服务器资源，上传即用"
back_anchor = "工具"
back_label = "返回首页"
meta = ["Cloudflare", "图床", "无服务器"]
repo = "https://github.com/MarSeventh/CloudFlare-ImgBed"
repo_label = "github.com/MarSeventh/CloudFlare-ImgBed"
docs = "https://cfbed.sanyue.de"
docs_label = "cfbed.sanyue.de"
live = "https://img.unmi.me"

highlights = [
  "上传即用，拖拽 / 粘贴均可",
  "Cloudflare R2 / KV 存储，全球加速",
  "不占用自有服务器资源",
  "支持多文件批量上传",
  "可自定义访问域名",
  "支持 API 与 PicGo 等工具对接",
]

[[extra.scenarios]]
title = "写博客时插图"
desc = "配好 PicGo 后，截图 → 粘贴 → 自动上传 → 剪贴板里已是 Markdown 图片链接，写文章流畅很多。"

[[extra.scenarios]]
title = "存放文章配图与表情包"
desc = "按目录分类管理，支持自定义域名访问，链接永久稳定。"

[[extra.scenarios]]
title = "分享大图给朋友"
desc = "不占用服务器带宽，Cloudflare CDN 全球分发，别人打开速度也快。"

[[extra.scenarios]]
title = "当作个人素材库"
desc = "把常用图标、背景图、设计素材集中放进来，需要时直接取链接。"

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

[[extra.related]]
slug = "vaultwarden"
title = "Vaultwarden"
desc = "密码自己管"
logo = "/img/icons/vaultwarden.svg"
+++

写博客、发文章绕不开插图，而图片放哪里一直是个问题：放服务器占硬盘和带宽、放第三方图床怕跑路、放对象存储又要配置密钥和 CDN。

**Sanyue ImgHub 是跑在 Cloudflare 上的无服务器图床。** 图片存进 R2 / KV，全球 CDN 加速，完全不消耗自己的服务器资源。支持拖拽上传、多图批量、粘贴上传，配合 PicGo 之类的工具能做到截图后一键上传并自动复制链接。
