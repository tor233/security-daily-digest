# security-daily-digest

每日安全漏洞文章聚合存档。由 Cursor Automation 定时抓取、整理并自动提交。

## 数据来源

- [wy876/SecAlerts](https://github.com/wy876/SecAlerts) 每日聚合 JSON
- 上游：[Doonsec](https://www.doonsec.com/) RSS、[mrxn](https://mrxn.net/rss.php)、picker 系列归档

## 目录结构

```
archive/
  index.json        # 日期清单（{date, total}，按日期倒序）
  YYYY-MM-DD.md     # 当天的文章清单（Markdown，按来源分组）
index.html          # GitHub Pages 静态页（时间线浏览 + 搜索）
```

## 网页版

仓库开启 GitHub Pages 后，访问 `https://tor233.github.io/security-daily-digest/` 即可按日期浏览每日清单。
