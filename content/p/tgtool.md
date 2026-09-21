+++
title = "unmi_TGtool"
template = "page.html"
sort_by = "none"

[extra]
logo = "/img/icons/tgtool.svg"
tagline = "模块化 Telegram 机器人工具箱 —— 可插拔，零依赖"
back_anchor = "自研"
back_label = "返回首页"
meta = ["Python", "Telegram Bot", "自研", "模块化"]
repo = "https://github.com/unmime/unmi_TGtool"
repo_label = "github.com/unmime/unmi_TGtool"

highlights = [
  "模块可插拔，功能互不影响",
  "零第三方依赖，纯标准库",
  "部署简单，复制即用",
  "支持 systemd 常驻",
  "内置自测脚本",
  "MIT 开源，可自由改造",
]

[[extra.scenarios]]
title = "随手算数"
desc = "在 Telegram 里直接发算式就有结果，不用切到计算器 App。"

[[extra.scenarios]]
title = "查汇率"
desc = "实时汇率换算，海淘、跨境付款前先算一下。"

[[extra.scenarios]]
title = "看加密货币行情"
desc = "查币价、涨跌幅，不用专门开行情软件。"

[[extra.scenarios]]
title = "作为开发模板"
desc = "想写自己的 TG 机器人时，可以拿它当骨架，按模块规范加功能。"

[[extra.related]]
slug = "cfsm"
title = "CF-Server-Monitor"
desc = "服务器监控探针"
logo = "/img/icons/cfsm.svg"

[[extra.related]]
slug = "neon-games"
title = "neon-games"
desc = "小游戏合集"
logo = "/img/icons/games.svg"
+++

Telegram 机器人写一个不难，但要维护一堆功能就容易乱：计算器一个文件、汇率一个文件、行情一个文件，彼此耦合，加功能越来越麻烦。

**unmi_TGtool 用模块化的方式解决这个问题。** 核心只负责消息分发，每个功能是一个独立模块，想加功能就写个模块丢进去，不想要就删掉，互不影响。整个项目**零第三方依赖**，纯标准库实现，部署简单到复制过去就能跑。
