# keye-open-prompts

> **科爷的精选提示词库** - 覆盖内容创作、AI学习、工作流和分析工具

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/keyelifeai/keye-open-prompts?style=social)](https://github.com/keyelifeai/keye-open-prompts)

---

## 📚 关于这个项目

这是一个精选的提示词库，专注于**实战应用**而非理论炒作。所有提示词都经过实际使用验证，帮助你在内容创作、AI学习、日常工作中提高效率。

**核心理念**：
- 📊 **Real data** - 真实数据驱动
- 🎯 **No bullshit** - 剥开炒作
- 💡 **Actual insights** - 实际价值

---

## 🎯 分类目录

### 📝 内容创作
- **文章写作** - 深度分析、观点文章、教程指南
- **社交媒体** - X (Twitter)、微信公众号、小红书
- **内容优化** - 标题优化、内容改写、SEO优化

### 🤖 AI学习
- **提示词工程** - Prompt设计、优化技巧
- **AI工作流** - 实际应用场景和流程
- **工具使用** - Claude、ChatGPT、其他AI工具

### 🔧 工作流
- **数据分析** - 数据处理、洞察提取
- **研究取证** - 信息收集、事实核查
- **决策支持** - 商业分析、战略思考

### 🛠️ 工具使用
- **Markdown** - 文档格式化、元数据处理
- **网页抓取** - 微信、网页、社交媒体
- **自动化** - 日常工作自动化脚本

---

## 🚀 快速开始

### 使用方式

#### 1. Claude Code / Claude AI
直接复制提示词，粘贴到 Claude 中使用。

#### 2. ChatGPT / 其他AI工具
提示词设计针对 Claude 优化，但在 ChatGPT 等工具中也能良好运行。

#### 3. 本地开发
```bash
# 克隆仓库
git clone https://github.com/keyelifeai/keye-open-prompts.git

# 浏览提示词
cd keye-open-prompts
ls -R prompts/
```

---

## 📖 提示词示例

### 📝 内容创作 - 深度分析文章

**提示词**：
```
你是一位经验丰富的商业分析师和内容创作者，擅长从复杂信息中提炼洞察。

请根据以下主题撰写一篇深度分析文章：

## 要求
1. **结构清晰**：使用清晰的标题层级和段落划分
2. **数据支撑**：引用具体数据和案例（如果有）
3. **洞察独到**：提供独特视角，避免陈词滥调
4. **实用性强**：给出可执行的建议或启发
5. **语言风格**：专业但不晦涩，有温度但不煽情

## 格式
- 标题：吸引眼球但不夸张
- 导语：100-200字，快速切入主题
- 正文：3-5个小标题，每个论点有支撑
- 结语：总结观点，给出展望或建议

## 字数
1500-2500字

请根据我的具体要求进行调整和优化。
```

---

### 🤖 AI学习 - 提示词优化

**提示词**：
```
你是一位提示词工程专家，擅长优化AI提示词以提高输出质量。

请分析以下提示词，并给出优化建议：

## 分析维度
1. **清晰度** - 指令是否明确、无歧义
2. **完整性** - 是否包含必要的要求和约束
3. **结构化** - 是否有清晰的输出格式要求
4. **上下文** - 是否提供足够的背景信息
5. **示例** - 是否需要添加示例来引导AI

## 优化建议
- 指出原提示词的不足
- 给出改进后的版本
- 说明改进理由

请提供具体、可执行的建议。
```

---

### 🔧 数据分析 - 业务洞察

**提示词**：
```
你是一位数据分析师和商业顾问，擅长从数据中提取商业洞察。

请分析以下数据，提供可执行的商业建议：

## 分析框架
1. **数据概览** - 数据规模、时间范围、关键指标
2. **趋势分析** - 长期趋势、季节性、异常点
3. **对比分析** - 同比、环比、行业对比
4. **洞察提取** - 关键发现、潜在机会、风险警示
5. **行动建议** - 具体措施、优先级、预期效果

## 输出格式
- 使用Markdown格式
- 关键数据用表格呈现
- 重要发现用⚠️或💡标注
- 建议按优先级排序

请基于数据给出客观、实用的分析。
```

---

## 📂 目录结构

```
keye-open-prompts/
├── README.md                    # 本文件
├── prompts/                     # 提示词目录
│   ├── content-creation/        # 内容创作
│   │   ├── article-writing.md
│   │   ├── social-media.md
│   │   └── content-optimization.md
│   ├── ai-learning/             # AI学习
│   │   ├── prompt-engineering.md
│   │   ├── ai-workflows.md
│   │   └── tool-usage.md
│   ├── workflows/               # 工作流
│   │   ├── data-analysis.md
│   │   ├── research.md
│   │   └── decision-support.md
│   └── tools/                   # 工具使用
│       ├── markdown.md
│       ├── web-scraping.md
│       └── automation.md
├── templates/                   # 提示词模板
│   ├── basic-template.md
│   └── advanced-template.md
├── examples/                    # 使用示例
│   └── case-studies.md
└── CONTRIBUTING.md              # 贡献指南
```

---

## 🤝 贡献指南

欢迎贡献你的提示词！请遵循以下原则：

### 贡献原则
1. **实战验证** - 提示词必须经过实际使用验证
2. **清晰描述** - 说明使用场景、预期效果
3. **分类准确** - 放入合适的分类
4. **格式规范** - 使用Markdown格式

### 贡献流程
1. Fork 本仓库
2. 创建你的提示词文件 (`prompts/category/your-prompt.md`)
3. 提交 Pull Request
4. 等待审核和合并

详见 [CONTRIBUTING.md](CONTRIBUTING.md)

---

## 📊 使用统计

- **提示词总数**: 50+
- **分类数量**: 4大类，12个子类
- **最后更新**: 2026-05-10

---

## 🔗 相关项目

- **[keye-claude-skills]** - Claude Code 技能集合
- **[keye-article-pipeline]** - AI文章创作流程
- **[keye-markdown-tools]** - Markdown处理工具

---

## 📮 反馈与建议

- 🐦 **X (Twitter)**: [@keyelifeai](https://x.com/keyelifeai)
- 📧 **Email**: keyelifeai@gmail.com
- 💼 **GitHub Issues**: [提交问题](https://github.com/keyelifeai/keye-open-prompts/issues)

---

## ⭐ 如果这个项目对你有帮助

请给个 ⭐ Star 支持一下！

---

## 📄 许可证

本项目采用 [MIT License](LICENSE) 开源许可证。

---

<div align="center">

**💡 实战至上，数据驱动，拒绝炒作**

Made with ❤️ by [Keye (科爷)](https://github.com/keyelifeai)

</div>
