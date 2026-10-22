# 交易日志（网页）

打开：https://1543839258luofangyue-glitch.github.io/trading-journal-app/

这个仓库只放网页程序，**不放任何交易数据**。

- 记录存在使用者自己的 GitHub 私有仓库（默认 `trading-journal` 的 `3_现在的记录/`），也在当前设备的浏览器里留一份；没网时先存本机，连上后自动上传。
- 第一次打开时，需要粘贴一把只能访问那一个私有仓库的 GitHub 钥匙（fine-grained token，Contents 读写）。钥匙只存在当前设备的浏览器里。
- 不依赖任何一家 AI：识图和点评都是“复制指令 → 发给任何 AI → 粘贴回复”。
- 功能：下单前检查（按规则拦截、自动算仓位）、记一笔（截图 + 开平仓）、持仓中当场记录加仓和改止损、复盘向导、进步对比、周复盘、导出压缩包。

注意：同一个 GitHub 账号下所有 GitHub Pages 网页共用同一个网址根（`1543839258luofangyue-glitch.github.io`），浏览器存储也共用。不要在这个账号的其他 Pages 网页里放来路不明的脚本。

第三方：`vendor/jszip.min.js`（JSZip 3.10.1，MIT）、`vendor/xlsx.full.min.js`（SheetJS 0.18.5，Apache-2.0）。
