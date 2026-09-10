<div align="center">

<img src="assets/icon.svg" alt="Tech News Daily" width="120" />

### Tech News Daily (日知录): a daily tech news digest

> Learn something new every day, and never forget what you have learned.

For developers who want to keep up with the tech world: automatically aggregates hot lists from multiple sources, builds a static page, and updates on a schedule

[![Visit site](https://img.shields.io/badge/visit-GitHub%20Pages-55e5d5?style=flat)](https://xplore-lab.github.io/tech-news/)
[![daily updates](https://img.shields.io/badge/daily%20updates-08%3A00%20%2F%2021%3A00%20CST-50a6ff?style=flat)](https://github.com/Xplore-LAB/tech-news/actions)

[![GitHub stars](https://img.shields.io/github/stars/Xplore-LAB/tech-news?style=flat&label=stars&color=gold)](https://github.com/Xplore-LAB/tech-news/stargazers)
[![license](https://img.shields.io/badge/license-MIT-1683c4?style=flat)](LICENSE)
[![python](https://img.shields.io/badge/python-3.11-32b643?style=flat)](https://www.python.org/)

[简体中文](README.md) · **English**

</div>

---

## ⚡ Tech News Daily in one minute

It automatically fetches tech news every day. GitHub Actions runs at 08:00 and 21:00 Beijing time, updates the `docs/` directory, and pushes, so the GitHub Pages site stays current.

| What you want to do | What you get |
| --- | --- |
| Skim the tech world's highlights | A daily page aggregating hot lists from multiple sources |
| Get updates on a schedule | GitHub Actions runs automatically at 08:00 and 21:00 Beijing time |
| Run it yourself locally | Two scripts, fetch news and generate the page, standard library only with no extra dependencies |

## ✨ Data sources

- **Hacker News**: top stories from the global tech community
- **GitHub Trending**: daily trending open-source projects
- **V2EX**: a Chinese developer community
- **Product Hunt**: the latest tech products

## 🚀 Run locally

```bash
pip install -r requirements.txt  # no extra dependencies, standard library only
python scripts/fetch_news.py     # fetch the news
python scripts/generate_html.py  # generate the page
```

## ⚙️ Automatic updates

GitHub Actions runs daily at 00:00 UTC (08:00 Beijing time) and 13:00 UTC (21:00 Beijing time), updates the `docs/` directory, and pushes.

## 📄 License

MIT © Xplore-LAB
