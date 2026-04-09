# 🔍 Google SEO.skill

> 基于 Google 官方 SEO 文档构建的专业 SEO 诊断和优化技能。支持 OpenClaw / Claude 等 AI 助手，即问即用。

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Reference Docs](https://img.shields.io/badge/Reference%20Docs-207%20Google%20Docs-green.svg)](https://developers.google.com/search/docs)

---

## 📖 项目介绍

Google SEO.skill 是一个 AI Agent 技能（Skill），专门用于 SEO 诊断和优化建议。它基于 **207 份 Google 官方 SEO 文档**，覆盖从入门到高级的所有主题。

### 能做什么？

- 🔍 **SEO 问题诊断** — 输入网站状况，输出具体问题和建议
- 📊 **结构化数据指导** — Product/Article/FAQ 等 Schema 正确实现
- 📈 **排名下降分析** — 诊断流量下降的根本原因
- 🌐 **多语言 SEO** — hreflang 和国际化最佳实践
- 📱 **移动端优化** — Core Web Vitals 和移动优先索引
- 🛠️ **技术 SEO** — robots.txt、sitemap、canonical 等

### 使用方式

直接在支持 OpenClaw Skill 的 AI 助手中使用，例如：

```
请帮我诊断网站SEO问题
如何实施 Product 结构化数据？
我的排名下降了怎么办？
网站需要多语言支持，最佳方案是什么？
```

---

## 📁 项目结构

```
Google SEO.skill/
├── SKILL.md          # 技能入口文件（含使用说明和调用指南）
├── _meta.json        # 元数据
└── docs/             # Google 官方 SEO 文档（207份）
    ├── 01-fundamentals/     # SEO 基础
    ├── 02-crawling-indexing/ # 抓取和索引
    ├── 03-ranking-appearance/ # 排名和呈现
    ├── 04-structured-data/   # 结构化数据
    ├── 05-monitoring-debugging/ # 监控和调试
    └── 06-specialty/         # 特定网站指南
```

---

## 🧠 知识库覆盖

| 分类 | 文档数 | 涵盖主题 |
|------|--------|---------|
| SEO 基础 | 22 | 入门指南、搜索原理、优质内容 |
| 抓取索引 | 51 | Sitemap、Robots、301重定向、Canonical |
| 排名呈现 | 78 | Title、Snippet、富媒体、精选摘要 |
| 结构化数据 | 36 | Product、Article、FAQ、Review |
| 监控调试 | 19 | Search Console、Google Trends |
| 特定指南 | 按需 | 电商、本地商家、教育等 |

---

## ✅ 为什么用这个 Skill？

1. **Google 官方依据** — 所有建议都有文档出处，不是网上随便搜来的 SEO 神话
2. **即问即用** — 不需要自己读几百页文档，问 AI 就够了
3. **持续更新** — 随着 Google 算法更新，Skill 文档库也可以同步更新
4. **可验证** — 每个建议都有原文链接，可以自己去读原始文档确认

---

## 🔧 安装使用

### 方式一：在 OpenClaw 中使用

将本项目放入 `~/.openclaw/workspace/skills/` 目录：

```bash
# 克隆到本地
git clone https://github.com/zlbigger/Google-SEOs.skill.git
mv Google-SEOs.skill ~/.openclaw/workspace/skills/google-seo-expert
```

然后在对话中直接使用，Skill 会自动激活：

```
请帮我看看这个页面应该怎么优化 SEO
```

### 方式二：独立使用文档

`docs/` 目录包含完整的 Google 官方 SEO 文档，可以：
- 用作 SEO 学习教材
- 接入其他 AI 工具（如 Claude、Cotoma）
- 作为团队内部 SEO 参考手册

---

## 📚 文档来源

所有文档均来自 Google 官方：
- [Google Search Central](https://developers.google.com/search)
- [Google SEO 入门指南](https://developers.google.com/search/docs/fundamentals/seo-starter-guide)
- [Google Search Gallery](https://developers.google.com/search/docs/appearance/visual-elements-gallery)

---

## ⚠️ 免责声明

本 Skill 基于 Google 公开文档构建，仅供参考。Google 算法会持续更新，实际效果因网站情况而异。建议结合 [Google Search Console](https://search.google.com/search-console) 做最终验证。

---

## 📄 License

MIT License — 可以自由使用、修改和分发。

---

*Built with ❤️ for the SEO community*
