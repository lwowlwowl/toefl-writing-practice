# TOEFL iBT Writing Practice

> 新托福写作系统练习仓库 — **Write an Email** & **Writing for an Academic Discussion**，配合 AI 多维度分析反馈。

## 关于

本仓库是 2026 年 1 月改革后新托福 iBT 写作部分两个题型的结构化练习空间。每次练习不只是写一篇作文——每篇提交都会通过 AI 进行多维度分析，包括语法纠错、逐句优化、词汇分析、评分对标等，并生成基于原文的改进版本。

## 仓库结构

```
toefl-writing-practice/
├── README.md
├── email/                              # Write an Email（≈80 题）
│   ├── README.md                       # 题型介绍与备考策略
│   ├── 001-example-campus-housing/
│   │   ├── 01-topic-and-answer.md      # 题目 + 我的作文
│   │   └── 02-analysis.md              # AI 分析反馈
│   └── ...
├── academic-discussion/                # Academic Discussion（≈70 题）
│   ├── README.md                       # 题型介绍与备考策略
│   ├── 001-example-technology-education/
│   │   ├── 01-topic-and-answer.md      # 题目 + 我的作文
│   │   └── 02-analysis.md              # AI 分析反馈
│   └── ...
├── prompts/                            # AI 分析提示词
│   ├── email-analysis-prompt.md        # Email 分析用提示词
│   └── discussion-analysis-prompt.md   # Discussion 分析用提示词
├── rubrics/                            # 评分标准
│   ├── email-rubric.md                 # Email 评分标准（0-5 分）
│   └── discussion-rubric.md            # Discussion 评分标准（0-5 分）
└── progress.md                         # 练习进度追踪
```

## 使用流程

1. **选题** — 从 `email/` 或 `academic-discussion/` 中选一个未做的题目。
2. **限时作答** — 打开 `01-topic-and-answer.md`，阅读题目后在同一文件中写作（Email: 7 分钟；Academic Discussion: 10 分钟），记录实际用时。
3. **AI 分析** — 让 AI 读取 `prompts/` 中的提示词，分析你的作文，结果写入 `02-analysis.md`。
4. **复盘** — 重点看语法纠错、逐句优化建议和改进版全文，记录进度。

## AI 分析重点

每篇作文的 AI 分析以三个核心板块为重点（⭐ 标记）：

| 板块 | 说明 |
|------|------|
| **语法错误详析 ⭐** | 逐条列出每个错误，解释背后的语法规则 |
| **逐句优化建议 ⭐** | 挑出语法正确但可以写得更好的句子，给出优化版和原因 |
| **改进版全文 ⭐** | 在原文基础上改进，每处改动标注原因 |

其他分析维度（沟通目标完成度、语气、原创性等）作为辅助参考一并提供。

## 评分标准

两个题型均使用 **0-5 分制**，详见 `rubrics/` 目录下的评分标准文档。

## 进度追踪

详见 [`progress.md`](progress.md)。

## License

本仓库用于个人学习。
