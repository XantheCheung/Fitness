一周家庭健身计划 - iPhone 离线 PWA

文件：
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png

部署要求：
1. 必须通过 HTTPS 网站访问（例如 GitHub Pages / Cloudflare Pages / Netlify）。
2. iPhone 第一次联网，用 Safari 打开部署后的网址。
3. Safari -> 分享 -> 添加到主屏幕 -> 打开为 Web App。
4. 首次完整打开一次后，核心页面文件会缓存。
5. 此后从主屏幕图标打开，可离线使用训练计划、倒计时和本地完成记录。

注意：
- 完成记录保存在该 iPhone 的 Web App 本地存储中。
- 删除 Web App、清理 Safari 网站数据或重装可能会清除记录。
- 页面中外部动作参考链接需要联网；训练计划本身不依赖它们。
