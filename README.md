# Chinese with Joy — 独立站

一页式教师品牌站（纯静态、零依赖、自适应手机），是频道 bio 链接的落脚点：
访客在这里 → 约试课（Preply）/ 下载 App / 留邮箱拿免费短语表。

## 上线步骤（GitHub Pages，免费）

1. GitHub 上新建仓库 `chinese-with-joy`（Public）
2. 把本文件夹里的 `index.html`（以及照片 `joy.jpg`）放进去，push
3. 仓库 Settings → Pages → Source 选 `main` 分支根目录 → Save
4. 几分钟后站点上线：`https://<你的用户名>.github.io/chinese-with-joy/`
5. （可选）买域名 `chinesewithjoy.com`，在 Pages 设置里绑定

## 上线前要做的 4 件事

| 事项 | 做法 |
|---|---|
| 照片 | 把近照存为本文件夹的 `joy.jpg`、街拍存为 `joy-travel.jpg` —— **不用改任何代码**，放进来自动挂载（没放时显示优雅占位） |
| `REPLACE-APP-URL` | App Store 真实链接（两处，搜这个标记） |
| `REPLACE-FORM` | MailerLite 免费账号的嵌入表单代码（1000 订阅内免费） |
| `REPLACE-SOCIAL` | TikTok / YouTube 频道链接（频道开了再填，先留 #） |

> 设计体系：「墨与玉」——九段明暗分区、唯一 jade 强调色、全站唯一一处阴影（手机 mockup）、
> 三个水印汉字（雨/说/勇）讲品牌叙事、一个开场气泡、两枚朱砂印章。改动时请守住这些数字。

## 上线后

- App 的设置页 `TEACHER_URL` 可以从 Preply 换成本站(或保持 Preply,本站放 bio)
- 频道所有平台的 bio 链接指向本站
- "30 条救命短语" PDF 让 Claude 从 data.js 生成,挂到邮件工具的欢迎邮件里
