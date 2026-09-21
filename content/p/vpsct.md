+++
title = "VpsCT"
template = "page.html"
sort_by = "none"

[extra]
logo = "/img/icons/vpsct.svg"
tagline = "多台服务器统一管理 —— 一个面板管住所有节点"
back_anchor = "自建"
back_label = "返回首页"
meta = ["Go", "服务器管理", "自托管"]
repo = "https://github.com/YongshengWin/VpsCT"
repo_label = "github.com/YongshengWin/VpsCT"
live = "https://vpsct.unmi.me"

highlights = [
  "多机统一接入管理",
  "实时状态与资源监控",
  "批量命令下发",
  "服务配置集中维护",
  "Go 编写，部署为单二进制",
  "适合个人与小团队",
]

[[extra.scenarios]]
title = "统一查看所有节点状态"
desc = "一个界面看到每台服务器的在线状态、CPU 内存、流量消耗，不用逐台登录。"

[[extra.scenarios]]
title = "批量下发命令"
desc = "需要对多台机器做同样的操作时，不用一台台 SSH 过去。"

[[extra.scenarios]]
title = "管理服务配置"
desc = "集中维护各节点上跑的服务，交代清楚每台机器在做什么。"

[[extra.scenarios]]
title = "资源分享与协作"
desc = "支持配置与资源分享，方便把节点信息同步给协作的人。"

[[extra.related]]
slug = "cfsm"
title = "CF-Server-Monitor"
desc = "服务器监控探针"
logo = "/img/icons/cfsm.svg"

[[extra.related]]
slug = "oneip"
title = "One IP"
desc = "网络工具箱"
logo = "/img/icons/oneip.svg"

[[extra.related]]
slug = "vaultwarden"
title = "Vaultwarden"
desc = "密码自己管"
logo = "/img/icons/vaultwarden.svg"
+++

服务器一旦超过两台，管理就开始变得麻烦：每台都要单独 SSH、单独看监控、单独更新配置。时间长了很容易出现"某台机器跑着什么我自己都忘了"的情况。

**VpsCT 是一个自托管的服务器管理面板**，把多台 VPS 统一接进来管理。可以集中查看状态、流量、资源占用，也能下发命令、管理服务配置。适合个人或小团队维护多机环境。
