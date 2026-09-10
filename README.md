<div align="center">

<img src="assets/icon.svg" alt="日知录" width="120" />

### 日知录：每日科技新闻聚合

> 日知其所亡，月无忘其所能。

为想快速跟进科技圈动态的开发者而生：自动抓取多源热榜，生成静态页面，每天定时更新

[![在线访问](https://img.shields.io/badge/在线访问-GitHub%20Pages-55e5d5?style=flat)](https://xplore-lab.github.io/tech-news/)
[![每日更新](https://img.shields.io/badge/每日更新-08%3A00%20%2F%2021%3A00-50a6ff?style=flat)](https://github.com/Xplore-LAB/tech-news/actions)

[![GitHub stars](https://img.shields.io/github/stars/Xplore-LAB/tech-news?style=flat&label=stars&color=gold)](https://github.com/Xplore-LAB/tech-news/stargazers)
[![license](https://img.shields.io/badge/license-MIT-1683c4?style=flat)](LICENSE)
[![python](https://img.shields.io/badge/python-3.11-32b643?style=flat)](https://www.python.org/)

**简体中文** · [English](README.en.md)

</div>

---

## ⚡ 一分钟看懂日知录

每日自动抓取科技圈新闻，通过 GitHub Actions 在北京时间每天 08:00 和 21:00 更新，更新 `docs/` 目录并推送，GitHub Pages 即刻可见。

| 你想完成的事 | 交付成果 |
| --- | --- |
| 快速浏览科技圈热点 | 聚合多源热榜的每日页面 |
| 每天定时获取更新 | GitHub Actions 每天 08:00 / 21:00（北京时间）自动运行 |
| 本地自己跑一遍 | 两个脚本：抓取新闻、生成页面，纯标准库无额外依赖 |

## ✨ 数据来源

- **Hacker News**：全球技术社区热帖
- **GitHub Trending**：每日热门开源项目
- **V2EX**：国内开发者社区
- **Product Hunt**：最新科技产品

## 🚀 本地运行

```bash
pip install -r requirements.txt  # 无额外依赖，纯标准库
python scripts/fetch_news.py     # 抓取新闻
python scripts/generate_html.py  # 生成页面
```

## ⚙️ 自动更新

GitHub Actions 每天 UTC 00:00（北京时间 08:00）与 UTC 13:00（北京时间 21:00）自动运行，更新 `docs/` 目录并推送。

## 📄 许可证

MIT © Xplore-LAB
