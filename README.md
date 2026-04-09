# 🔍 Google SEO.skill / Google SEO 技能

> 基于 Google 官方 SEO 文档构建的专业 SEO 诊断和优化技能。支持 OpenClaw / Claude 等 AI 助手，即问即用。
>
> A professional SEO diagnostic and optimization skill built on 207 official Google SEO documents. Works with OpenClaw, Claude, and other AI assistants. Ask and get answers instantly.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Reference Docs](https://img.shields.io/badge/Reference%20Docs-207%20Google%20Docs-green.svg)](https://developers.google.com/search)

---

## 📖 项目介绍 / Project Introduction

### 中文

Google SEO.skill 是一个 AI Agent 技能，专门用于 SEO 诊断和优化建议。基于 **207 份 Google 官方 SEO 文档**，覆盖从入门到高级的所有主题。

### English

Google SEO.skill is an AI Agent skill designed for SEO diagnostics and optimization advice. Built on **207 official Google SEO documents**, covering everything from beginner to advanced topics.

---

## ✨ 功能 / Features

| 功能 | Feature |
|------|---------|
| SEO 问题诊断 | SEO Problem Diagnosis |
| 结构化数据指导 | Structured Data Guidance |
| 排名下降分析 | Ranking Drop Analysis |
| 多语言 SEO | Multilingual SEO |
| 移动端优化 | Mobile Optimization |
| 技术 SEO | Technical SEO |
| Core Web Vitals | Core Web Vitals |

---

## 📁 项目结构 / Project Structure

```
Google SEO.skill/
├── SKILL.md              # 技能入口 / Skill entry point
├── _meta.json            # 元数据 / Metadata
├── README.md             # 本文件 / This file
├── README.en.md          # English version
├── references/            # Google 官方文档 / Official Google docs
│   ├── 01-fundamentals/       # SEO 基础 / SEO Fundamentals
│   ├── 02-crawling-indexing/  # 抓取和索引 / Crawling & Indexing
│   ├── 03-ranking-appearance/  # 排名和呈现 / Ranking & Appearance
│   ├── 04-structured-data/    # 结构化数据 / Structured Data
│   ├── 05-monitoring-debugging/ # 监控和调试 / Monitoring & Debugging
│   ├── 06-specialty/           # 特定网站指南 / Specialty Guides
│   └── 07-patterns/            # 常见问题诊断 / Common Issues
└── scripts/              # 工具脚本 / Utility Scripts
    ├── search_kb.py           # 知识库搜索 / Knowledge base search
    ├── organize_files.py      # 文件整理 / File organizer
    └── deduplicate_specialty.py # 去重 / Deduplication
```

---

## 🧠 知识库覆盖 / Knowledge Base Coverage

| 分类 | Category | 文档数 |
|------|---------|--------|
| SEO 基础 | Fundamentals | 22 |
| 抓取索引 | Crawling & Indexing | 51 |
| 排名呈现 | Ranking & Appearance | 78 |
| 结构化数据 | Structured Data | 36 |
| 监控调试 | Monitoring & Debugging | 19 |
| 特定指南 | Specialty | - |

---

## 🚀 快速开始 / Quick Start

### 中文

```bash
# 克隆到本地
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

```bash
# Clone to local
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

1. **Google 官方依据** — 所有建议都有文档出处
2. **即问即用** — 不需要读几百页文档，问 AI 就够了
3. **可验证** — 每个建议都有原文链接

### English

1. **Official Google Source** — Every recommendation has a citation
2. **Ask & Get** — No need to read hundreds of pages yourself
3. **Verifiable** — Every recommendation links to the original document

---

## 📚 文档来源 / Sources

- [Google Search Central](https://developers.google.com/search)
- [Google SEO Starter Guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide)
- [Google Search Gallery](https://developers.google.com/search/docs/appearance/visual-elements-gallery)

---

## ⚠️ 免责声明 / Disclaimer

本 Skill 基于 Google 公开文档构建，仅供参考。Google 算法会持续更新，实际效果因网站情况而异。

This skill is for reference only. Google's algorithm evolves continuously, and actual results vary by website.

---

## 📄 License

MIT License — 自由使用、修改和分发。 / Free to use, modify, and distribute.

---

*Built with ❤️ for the SEO community / 为 SEO 社区而生*
