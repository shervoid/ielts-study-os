# IELTS Study OS v2.0

一个零依赖、移动端优先、可离线使用的 IELTS Academic 21 天备考管理网站。

## 已实现

- Dashboard：Top 3、倒计时、连续学习、热力图、AI 教练规则建议、停车纸
- 今日计划：任务增删改查、打勾、计时、拖拽排序、低状态最低任务
- 21 天计划：逐日完成和编辑
- IELTS 知识库：四科中英双语题型、步骤、时间、训练方式、错误、陷阱、资料、个人正确率和弱项
- 错题本：详细字段、到期提醒、1/3/7/14 天复习、连续两次正确自动掌握
- 每日复盘：自动统计学习时间、计时次数、中断数，复制 Markdown / AI Prompt
- 四科训练、词汇复习、资料管理、模考、统计趋势、计时器
- JSON 导入导出、CSV 导出、旧版 localStorage 数据迁移
- PWA manifest、Service Worker 离线缓存、Netlify 路由配置

## 部署到 Netlify

直接将整个文件夹或 ZIP 拖到 Netlify Deploys。根目录已包含 `index.html`、`_redirects` 和 `netlify.toml`。

## 本地运行

```bash
python3 -m http.server 8080
```

打开 http://localhost:8080

## 数据说明

数据保存在当前浏览器 localStorage。更换设备、浏览器、网站域名或清理浏览器数据前，请在设置中导出 JSON。
