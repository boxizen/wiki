# Wiki

学习笔记与交互图解。

## 期权卖方 · 小白图解

- [网页入口](https://boxizen.github.io/wiki/options/)
- [HTML 源文件](options/index.html)

以六张可切换图解解释：一份承诺、钱的来去、交易六步、基础指标、场景风险和保护策略。CSS、JavaScript 与 SVG 均内嵌，无需安装依赖或构建；下载 HTML 后可以离线打开。

## 期权卖方三步法 · 视频拆解与风险保护

- [打开交互图解](https://boxizen.github.io/wiki/options/seller-three-steps.html)
- [HTML 源文件](options/seller-three-steps.html)

依据 B站视频《期权策略实战｜期权卖方稳赢三步曲》的官方章节和可读取讲义画面，区分视频规则与教程补充。六章解释入场、仓位、风控、观测指标和交易流程，用现金担保 Put、备兑 Call 对比不同场景；拖动到期股价，可以查看保护组合的总损益。

未取得完整口播；证据范围和补充来源见页面底部。“稳赢”不是盈利保证。新页面同样可以下载后离线使用。

## 卖 Put · 从观察到记录

- [打开图解与交易记录](https://boxizen.github.io/wiki/options/put-checklist.html)
- [HTML 源文件](options/put-checklist.html)

四章串起开仓前六项检查、IV与Greeks、持仓情景处理，以及可填写的交易记录。记录区分计划、持仓浮盈亏、平仓、到期作废和指派后的股票损益；支持JSON完整备份/恢复与CSV汇总。

记录仅保存在当前设备的浏览器中，不会上传到GitHub，不连接券商、不提供行情或自动提醒。请定期导出备份。自动计算仅适用于每张100股、同条款单批现金担保Put；部分处理和多腿组合需另行核对。

## Put 决策档案

- [打开决策档案](https://boxizen.github.io/wiki/options/put-decision.html)
- [HTML 源文件](options/put-decision.html)

每次操作前封存当时的行情、事件、现金、退出计划和理由；实际成交另记。支持部分平仓、部分指派和接股后分批卖股；展期新建关联档案。已封存内容不会随草稿修改而覆盖。

可以生成只含某次决定当时已知信息的 AI 分析材料，或完整复盘材料；支持贴回 AI 意见、记录采纳理由及结构化复盘。页面不在后台运行 AI。提供完整 JSON 备份恢复、时间线 CSV、空白 Markdown 模板。旧“记一笔”可导入保留原文，不补造事前时间或成交流水。

所有记录仅在当前浏览器。现金担保不保证亏损上限；保护或多腿调整需要人工核对完整损益。

## GitHub Pages

发布源使用 `main` 分支的根目录 `/`：在仓库 **Settings → Pages → Build and deployment** 中选择 **Deploy from a branch**，分支选择 **main**，目录选择 **/(root)**，保存。

根目录的 `.nojekyll` 让 Pages 直接发布静态文件。此后推送到 `main` 会自动更新站点。

- 站点首页：<https://boxizen.github.io/wiki/>
- 期权图解：<https://boxizen.github.io/wiki/options/>

图中数字是教学假设，不是实时行情。资料来源和计算口径见网页底部。
