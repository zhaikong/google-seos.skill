# 🔍 Google SEO.skill / Google SEO 技能

> 基于 Google 官方 SEO 文档构建的专业 SEO 诊断和优化技能。支持 OpenClaw / Claude 等 AI 助手，即问即用。
>
> A professional SEO diagnostic and optimization skill built on 207 official Google SEO documents. Works with OpenClaw, Claude, and other AI assistants. Ask and get answers instantly.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Reference Docs](https://img.shields.io/badge/Reference%20Docs-207%20Google%20Docs-green.svg)](https://developers.google.com/search)
[![EN](https://img.shields.io/badge/Lang-English-red.svg)](./README.en.md)

---

## 📖 项目介绍 / Project Introduction

### 中文

Google SEO.skill 是一个 AI Agent 技能，专门用于 SEO 诊断和优化建议。基于 **207 份 Google 官方 SEO 文档**，覆盖从入门到高级的所有主题。

### English

Google SEO.skill is an AI Agent skill designed for SEO diagnostics and optimization advice. Built on **207 official Google SEO documents**, covering everything from beginner to advanced topics.

---

## ✨ 功能 / Features

| 功能 | Feature | 状态 |
|------|---------|------|
| SEO 问题诊断 | SEO Problem Diagnosis | ✅ |
| 结构化数据指导 | Structured Data Guidance | ✅ |
| 排名下降分析 | Ranking Drop Analysis | ✅ |
| 多语言 SEO | Multilingual SEO | ✅ |
| 移动端优化 | Mobile Optimization | ✅ |
| 技术 SEO | Technical SEO | ✅ |
| 链接建设 | Link Building | ✅ |
| Core Web Vitals | Core Web Vitals | ✅ |

---

## 📁 项目结构 / Project Structure

```
Google SEO.skill/
├── SKILL.md              # 技能入口 / Skill entry point
├── _meta.json            # 元数据 / Metadata
├── README.md             # 本文件 / Bilingual introduction
├── README.en.md          # English version
└── docs/                 # Google 官方文档 / Official Google docs
    ├── 01-fundamentals/       # SEO 基础 / SEO Fundamentals
    ├── 02-crawling-indexing/  # 抓取和索引 / Crawling & Indexing
    ├── 03-ranking-appearance/  # 排名和呈现 / Ranking & Appearance
    ├── 04-structured-data/    # 结构化数据 / Structured Data
    ├── 05-monitoring-debugging/# 监控和调试 / Monitoring & Debugging
    └── 06-specialty/           # 特定网站指南 / Specialty Guides
```

---

## 🧠 知识库覆盖 / Knowledge Base Coverage

| 分类 | Category | 文档数 | Docs |
|------|----------|---------|------|
| SEO 基础 | Fundamentals | 22 | 入门指南、搜索原理、优质内容 |
| 抓取索引 | Crawling & Indexing | 51 | Sitemap、Robots、301重定向 |
| 排名呈现 | Ranking & Appearance | 78 | Title、Snippet、富媒体摘要 |
| 结构化数据 | Structured Data | 36 | Product、Article、FAQ、Review |
| 监控调试 | Monitoring & Debugging | 19 | Search Console、Google Trends |
| 特定指南 | Specialty | - | 电商、本地商家、教育等 |

---

## 🚀 快速开始 / Quick Start

### 中文

将本项目放入 OpenClaw 的 skills 目录：

```bash
git clone https://github.com/zlbigger/Google-SEOs.skill.git ~/.openclaw/workspace/skills/google-seo-expert
```

然后在对话中直接使用：

```
请帮我诊断网站SEO问题
如何实施 Product 结构化数据？
我的排名下降了怎么办？
网站需要多语言支持，最佳方案是什么？
```

### English

Clone this repo into your OpenClaw skills folder:

```bash
git clone https://github.com/zlbigger/Google-SEOs.skill.git ~/.openclaw/workspace/skills/google-seo-expert
```

Then use it in your conversations:

```
Help me diagnose my website's SEO issues
How do I implement Product structured data?
My rankings dropped, what should I do?
What's the best approach for multilingual SEO?
```

---

## ✅ 为什么用这个 Skill？/ Why Use This Skill?

### 中文

1. **Google 官方依据** — 所有建议都有文档出处，不是网上随便搜来的 SEO 神话
2. **即问即用** — 不需要自己读几百页文档，问 AI 就够了
3. **持续更新** — 随着 Google 算法更新，Skill 文档库也可以同步更新
4. **可验证** — 每个建议都有原文链接，可以自己去读原始文档确认

### English

1. **Official Google Source** — Every recommendation has a document citation, not random SEO myths from the internet
2. **Ask & Get** — No need to read hundreds of pages yourself, just ask the AI
3. **Keep Updated** — As Google algorithm evolves, the skill docs can be synced accordingly
4. **Verifiable** — Every recommendation links to the original Google document

---

## 📚 文档来源 / Sources

All documents are sourced from Google Official:
- [Google Search Central](https://developers.google.com/search)
- [Google SEO Starter Guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide)
- [Google Search Gallery](https://developers.google.com/search/docs/appearance/visual-elements-gallery)

---

## ⚠️ 免责声明 / Disclaimer

### 中文

本 Skill 基于 Google 公开文档构建，仅供参考。Google 算法会持续更新，实际效果因网站情况而异。建议结合 [Google Search Console](https://search.google.com/search-console) 做最终验证。

### English

This skill is built on Google's public documentation and is for reference only. Google's algorithm evolves continuously, and actual results vary by website. It's recommended to validate with [Google Search Console](https://search.google.com/search-console) for final verification.

---

## 📄 License

MIT License — 自由使用、修改和分发。
MIT License — Free to use, modify, and distribute.

---

*Built with ❤️ for the SEO community / 为 SEO 社区而生*
