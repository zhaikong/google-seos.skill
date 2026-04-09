# Google SEO Expert Skill

基于Google官方SEO指南构建的专业SEO诊断和优化技能。

## 技能信息

- **名称**: google-seo-expert
- **版本**: 1.0.0
- **描述**: 专业的Google SEO诊断、优化建议和技术实施指南
- **来源**: 207份Google官方SEO文档

## 触发关键词

当用户提及以下关键词时，激活此技能：

- SEO、搜索优化、搜索引擎优化
- 排名、ranking、排名下降
- 抓取、crawling、索引、indexing
- 结构化数据、structured data、Schema
- 网站收录、收录问题
- 搜索流量、traffic drop
- 站点地图、sitemap、robots
- 移动端优化、mobile-first
- 页面速度、Core Web Vitals
- 富媒体摘要、rich snippet

## 使用方法

### 基本调用

```
请帮我诊断网站SEO问题
我需要优化网站排名
如何实施结构化数据？
```

### 诊断流程

1. **问题识别**: 用户描述网站状况或问题
2. **知识检索**: 基于分类文档检索相关信息
3. **诊断分析**: 根据Google官方指南给出诊断
4. **解决方案**: 提供可执行的优化建议
5. **优先级排序**: 按影响程度和实施难度排序

## 知识库目录结构

```
references/
├── 01-fundamentals/          # SEO基础 (22个文件)
│   ├── seo-starter-guide.md      # SEO入门指南
│   ├── how-search-works.md       # 搜索工作原理
│   ├── creating-helpful-content.md # 创建优质内容
│   ├── do-i-need-seo.md          # 是否需要SEO
│   └── get-on-google.md          # 如何让网站被收录
│
├── 02-crawling-indexing/     # 抓取和索引 (51个文件)
│   ├── sitemaps-overview.md      # 站点地图
│   ├── robots-meta-tag.md        # Robots元标签
│   ├── links-crawlable.md        # 可抓取链接
│   ├── 301-redirects.md          # 301重定向
│   ├── canonical.md              # 规范化URL
│   ├── mobile-sites-*.md         # 移动优先索引
│   ├── amp.md                    # AMP加速页面
│   ├── javascript-seo-basics.md  # JavaScript SEO
│   └── block-indexing.md         # 阻止索引
│
├── 03-ranking-appearance/    # 排名和呈现 (78个文件)
│   ├── title-link.md             # 标题和链接
│   ├── snippet.md                # 搜索结果摘要
│   ├── google-images.md          # 图片搜索
│   ├── video.md                  # 视频搜索
│   ├── favicon-in-search.md      # 搜索图标
│   ├── featured-snippets.md      # 精选摘要
│   ├── site-names.md             # 站点名称
│   ├── sitelinks.md              # 站内链接
│   ├── ai-features.md            # AI搜索功能
│   └── google-discover.md        # Google Discover
│
├── 04-structured-data/       # 结构化数据 (36个文件)
│   ├── intro-structured-data.md  # 结构化数据入门
│   ├── article.md                # 文章类型
│   ├── breadcrumb.md             # 面包屑导航
│   ├── product.md                # 产品类型
│   ├── recipe.md                 # 食谱类型
│   ├── event.md                  # 事件类型
│   ├── faqpage.md                # FAQ页面
│   ├── local-business.md         # 本地商家
│   ├── review-snippet.md         # 评价摘要
│   └── ...                       # 更多Schema类型
│
├── 05-monitoring-debugging/  # 监控和调试 (19个文件)
│   ├── search-operators.md       # 搜索运算符
│   ├── debugging-search-traffic-drops.md # 流量下降诊断
│   ├── google-analytics-search-console.md # GA和GSC
│   ├── trends-start.md           # Google Trends
│   ├── spam-policies.md          # 垃圾内容政策
│   └── technical.md              # 技术SEO
│
└── 06-specialty/             # 特定网站指南 (按需添加)

```

## 输出格式规范

所有SEO诊断和建议遵循以下格式：

### 1. 诊断结论
```
📊 诊断结果: [高/中/低风险]
🎯 核心问题: [一句话概括]
📍 影响范围: [页面/整站/特定板块]
```

### 2. 依据引用
```
📚 Google官方依据:
- [文档名称](文件路径): 相关章节/引文
- [文档名称](文件路径): 相关章节/引文
```

### 3. 解决方案
```
🔧 解决方案:

【方案A - 快速修复】
- 步骤1: ...
- 步骤2: ...
- 预计效果: ...

【方案B - 长期优化】
- 步骤1: ...
- 步骤2: ...
- 预计效果: ...
```

### 4. 优先级排序
```
📋 执行优先级:

P0 (立即执行):
- [ ] 问题1 - 影响: [高] - 工作量: [小]

P1 (本周内):
- [ ] 问题2 - 影响: [中] - 工作量: [中]

P2 (本月内):
- [ ] 问题3 - 影响: [低] - 工作量: [大]
```

## 知识库搜索

使用提供的脚本搜索相关知识：

```bash
python3 scripts/search_kb.py "关键词"
```

示例：
```bash
python3 scripts/search_kb.py "canonical"
python3 scripts/search_kb.py "structured data product"
```

## 常见诊断模式

参考 `references/07-patterns/常见问题诊断.md` 快速识别和处理典型SEO问题。

## 引用规范

- 所有建议必须引用Google官方文档
- 引用格式: `[文档标题](references/分类/文件名.md)`
- 优先引用主文档，而非docs-前缀的重复文档

## 免责声明

本技能基于Google公开的SEO文档构建，建议随Google算法更新而调整。实际效果因网站情况而异。
