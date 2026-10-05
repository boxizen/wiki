# Wiki

学习笔记与交互图解。期权内容整理为两个页面。

## 期权卖方实操指南

- [打开实操指南](https://boxizen.github.io/wiki/options/)
- [HTML 源文件](options/index.html)

合并原“小白图解”“视频三步法”“卖 Put · 从观察到记录”的学习内容，保留五章：开仓前、持仓中、算清结局、保护与应对、指标速查。

用现金担保 Put、备兑 Call 与领口比较不同结果；可拖动张数、回购款与到期股价，查看承诺、盈亏和保护代价。基础定义与视频出处折叠备查。视频证据限官方章节和可读取画面，未取得完整口播；数值案例为教学补充，不是实时行情或统一交易规则。

CSS、JavaScript 和 SVG 均内嵌，无依赖、无远程资源，可下载后离线查看。

## Put 决策档案

- [打开决策档案](https://boxizen.github.io/wiki/options/put-decision.html)
- [HTML 源文件](options/put-decision.html)

每次操作前封存当时的行情、事件、现金、退出计划和理由；实际成交另记。支持部分平仓、部分指派和接股后分批卖股；展期新建关联档案。已封存内容不会随草稿修改而覆盖。

可以生成只含某次决定当时已知信息的 AI 分析材料，或完整复盘材料；支持贴回 AI 意见、记录采纳理由及结构化复盘。页面不在后台运行 AI。提供完整 JSON 备份恢复、时间线 CSV、空白 Markdown 模板。

所有记录仅在当前浏览器，不上传 GitHub、不连接券商或行情，也不发送提醒。换设备、浏览器或本地文件与线上页面之间不会自动同步，请定期导出 JSON 备份。现金担保不保证亏损上限；保护、多腿与备兑 Call 需要人工核对完整损益。

## 旧页面与记录

`options/` 只保留 `index.html` 和 `put-decision.html` 两个 HTML。旧 `seller-three-steps.html` 与 `put-checklist.html` 已删除；站点根目录的 `404.html` 精确识别这两个旧地址，在启用 JavaScript 的浏览器中引导到合并页。旧记录锚点 `#journal`、`#panel-3` 引导到决策档案。其他未知地址不会自动跳转。

这是 GitHub Pages 的自定义 404 兼容处理，旧地址初始 HTTP 状态仍为 404，不是服务器端 301。关闭 JavaScript 时可手动点击新入口。

原浏览器的旧“记一笔”存储不会被删除。进入决策档案，点击“读取本浏览器旧‘记一笔’”，或导入旧 JSON 备份，保留原文而不伪造历史决定、时间或成交流水。原有决策档案的存储与计算逻辑保持兼容。

## GitHub Pages

发布源使用 `main` 分支的根目录 `/`。根目录 `.nojekyll` 让 Pages 直接发布静态文件；推送到 `main` 后自动更新。

- [站点首页](https://boxizen.github.io/wiki/)
- [实操指南](https://boxizen.github.io/wiki/options/)
- [决策档案](https://boxizen.github.io/wiki/options/put-decision.html)

图中数字是教学假设。资料来源和计算口径见各页底部。
