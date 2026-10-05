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

## GitHub Pages

发布源使用 `main` 分支的根目录 `/`：在仓库 **Settings → Pages → Build and deployment** 中选择 **Deploy from a branch**，分支选择 **main**，目录选择 **/(root)**，保存。

根目录的 `.nojekyll` 让 Pages 直接发布静态文件。此后推送到 `main` 会自动更新站点。

- 站点首页：<https://boxizen.github.io/wiki/>
- 期权图解：<https://boxizen.github.io/wiki/options/>

图中数字是教学假设，不是实时行情。资料来源和计算口径见网页底部。
