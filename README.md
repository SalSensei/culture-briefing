# culture-briefing

《全球文化晨报》的独立发布目录，仅包含对外公开的站点文件。

## 公开内容
- `index.html`：首页，永远展示最新一期
- `archive/index.html`：归档目录页（只保留最近 10 期）
- `archive/YYYY-MM-DD.html`：每日历史归档页

## 发布策略
- 从 workspace 的 `reports/global-culture-briefing-YYYY-MM-DD.html` 读取最新正式晨报
- 同步到本目录首页与归档
- 自动清理旧归档，只保留最近 10 期
- 此目录是 GitHub Pages 唯一发布源
