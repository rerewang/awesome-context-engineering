# Awesome Context Engineering 🚀

> Context Engineering 参考资料、框架和最佳实践的精选列表，用于构建生产级 AI 系统。

[English](README.md) | 中文

## 🌟 重点推荐项目：AGENTS.md

**AGENTS.md 是 Context Engineering 的基石** - 一个标准化的、开放格式，用于为 AI 代理提供特定指令。它是使 Context Engineering 真正可扩展和互操作的关键部分。

> **为什么选择 AGENTS.md？** 它是唯一一个能让 AI 代理在不同平台、工具和工作流中一致理解项目上下文的开放标准。

### 🎯 AGENTS.md 核心优势
* **标准化上下文传输** - AI 工具之间的无缝上下文共享
* **跨平台兼容性** - 与 Claude、GPT、Gemini 等平台兼容
* **Monorepo 支持** - 简化嵌套项目结构
* **代理无关性** - 适用于任何 AI 代理实现的通用格式

### 🚀 开始使用 AGENTS.md
* **[官方网站](https://agents.md)** - 完整规范和示例
* **[GitHub 仓库](https://github.com/agents-md/agents-md)** - 源代码和文档
* **[快速开始指南](https://agents.md/#quick-start)** - 几分钟内上手
* **[社区示例](https://agents.md/#examples)** - 实际应用案例

---

## 目录

* [关于概念](#关于概念)
* [为什么选择 Context Engineering 而不是 Vibe Coding？](#为什么选择-context-engineering-而不是-vibe-coding)
* [核心框架](#核心框架)
* [上下文管理工具](#上下文管理工具)
* [企业解决方案](#企业解决方案)
* [研究与论文](#研究与论文)
* [社区与资源](#社区与资源)
* [贡献](#贡献)

## 关于概念

**Context Engineering** 代表了超越传统 prompt engineering 和 vibe coding 的演进，专注于系统化、可扩展的方法来管理 AI 系统上下文。与 vibe coding 的"随波逐流"方法不同，Context Engineering 提供了构建可靠、生产就绪的 AI 应用程序的结构化方法。

> "Context Engineering 不仅仅是编写提示 - 它是关于架构 AI 系统如何理解、维护和发展其在复杂交互和长期操作中的上下文感知能力。" - Context Engineering 社区

## 为什么选择 Context Engineering 而不是 Vibe Coding？

### Vibe Coding 方法
* **理念**："随波逐流"，拥抱指数增长，忘记代码复杂性
* **重点**：快速原型设计，快速迭代，实验性开发
* **局限性**： 
  - 缺乏系统化的上下文管理
  - 难以保持长期一致性
  - 难以扩展到简单应用程序之外
  - 企业采用潜力有限

### Context Engineering 方法
* **理念**：系统化、可扩展、可靠的 AI 系统设计
* **重点**：生产级应用程序，企业解决方案，长期可维护性
* **优势**：
  - 结构化的上下文管理框架
  - 复杂交互中的一致行为
  - 可扩展到企业级应用程序
  - 内置的可靠性和测试能力
  - 专业开发工作流

### 何时选择每种方法

| 使用场景 | Vibe Coding | Context Engineering |
|----------|-------------|-------------------|
| **快速原型设计** | ✅ 优秀 | ⚠️ 过度设计 |
| **生产应用程序** | ❌ 有风险 | ✅ 推荐 |
| **团队协作** | ❌ 困难 | ✅ 优秀 |
| **长期项目** | ❌ 不可持续 | ✅ 必需 |
| **企业使用** | ❌ 不适合 | ✅ 完美匹配 |

## 核心框架

### 🌐 AGENTS.md ⭐ **推荐首选**
**AI 代理上下文管理的标准**
* **核心概念**：开放的、标准化的 AI 代理指令格式，使 AI 代理能够在不同平台中一致理解上下文
* **Context Engineering 优势**： 
  - **通用上下文传输**：在任何 AI 工具或平台之间共享上下文
  - **互操作性**：与 Claude、GPT、Gemini 等主要 AI 平台兼容
  - **可扩展性**：轻松处理复杂的嵌套项目结构
  - **面向未来**：随 AI 生态系统发展的开放标准
* **使用场景**：项目文档、AI 协作、团队知识转移、企业 AI 工作流
* **官方资源**：[网站](https://agents.md) | [GitHub](https://github.com/agents-md/agents-md) | [示例](https://agents.md/#examples)
* **为什么从这里开始**：AGENTS.md 是使所有其他 Context Engineering 框架无缝协作的基础

### 🔥 BMAD-METHOD
**多代理协作的 Context Engineering 框架**
* **核心概念**：协调多个专业代理（PM、PO、架构师、开发人员、QA、UX）来维护项目上下文
* **Context Engineering 优势**：每个代理维护和传递上下文信息，确保整个开发生命周期的一致性
* **使用场景**：复杂项目规划，团队协作，上下文驱动的项目管理
* **官方资源**：[GitHub](https://github.com/bmad-code-org/BMAD-METHOD)
* **完美搭配**：与 AGENTS.md 配合使用，实现标准化代理通信

### 🚀 Claude Code Spec Workflow
**自动化上下文驱动开发框架**
* **核心概念**：规范驱动开发工作流（需求 → 设计 → 任务 → 实现），具有自动化上下文管理
* **Context Engineering 优势**：分层上下文管理策略，消除冗余加载，智能文档处理，减少 60-80% 的 token 消耗
* **主要特性**： 
  - 自动化规范创建和执行
  - Bug 修复工作流（报告 → 分析 → 修复 → 验证）
  - 上下文优化命令，实现高效的文档加载
  - 类型安全的项目处理，95%+ 类型覆盖率
* **使用场景**：新功能开发，Bug 解决，项目上下文管理
* **官方资源**：[GitHub](https://github.com/Pimzino/claude-code-spec-workflow) | [文档](https://github.com/Pimzino/claude-code-spec-workflow#readme)

### ⚡ Kiro Specs
**AI 驱动的规范和上下文管理系统**
* **核心概念**：先进的规范系统，使 AI 代理能够通过结构化规范理解项目上下文
* **Context Engineering 优势**：为 AI 代理提供全面的项目理解，实现上下文感知的开发和决策
* **主要特性**： 
  - AI 可读的项目规范
  - 上下文感知的项目分析
  - AI 代理的结构化信息
  - 增强的 AI 协作能力
* **使用场景**：AI 代理训练，项目上下文文档，增强的 AI 协作
* **官方资源**：[文档](https://kiro.dev/docs/specs/) | [官网](https://kiro.dev)

## 上下文管理工具

### 向量数据库和存储
* **Pinecone** - 用于语义搜索和上下文检索的向量数据库
* **Weaviate** - 具有上下文感知搜索的开源向量数据库
* **Qdrant** - 用于实时上下文管理的高性能向量数据库

### 上下文优化
* **[Agent-Body](https://github.com/1420079678-ctrl/agent-body)** - DeepSeek Harness 的按任务工具定义门控与持久记忆层，提供离线 Node.js 演示及可复现基准；项目处于早期，Windows 优先。
* **RAG（检索增强生成）** - 从外部知识库动态构建上下文
* **Chain-of-Thought** - 保持上下文一致性的结构化推理
* **Tree-of-Thoughts** - 用于复杂上下文管理的分支思维过程

### 开发工具
* **LangChain** - 构建上下文感知的 AI 应用程序
* **LlamaIndex** - 智能数据索引和检索
* **AutoGen** - 多智能体上下文协作

## 企业解决方案

### Context Engineering 平台
* **Contextual AI** - 企业上下文管理平台
* **Portkey.ai** - 高吞吐量场景的上下文编排
* **Forte Group** - 将 Context Engineering 作为 AI 驱动交付的核心学科

### 案例研究
* **JPMorgan 的 COiN 平台** - 具有上下文管理的智能 AI 金融分析
* **EY 的智能 AI 集成** - 具有企业上下文的 Microsoft 365 Copilot
* **企业 RAG 应用程序** - 大规模部署的上下文层

## 研究与论文

### 学术基础
* **[大型语言模型上下文工程调查](https://arxiv.org/abs/2507.13334)** - 涵盖高级上下文操作技术的综合学术调查
* **David Kimai 的上下文工程** - 将 Context Engineering 作为"连续领域"的理论探索

### 行业研究
* **OpenAI 研究** - 上下文管理的官方出版物
* **Anthropic 研究** - 对齐和 LLM 交互技术
* **Google 研究** - 上下文优化和检索方法

## 社区与资源

### 在线社区
* **r/PromptEngineering** - Reddit 上的 prompt engineering 讨论社区
* **AI Engineering Discord** - AI 开发的实时讨论
* **Context Engineering 工作坊** - 专业发展和培训

### 新闻与更新
* **2025 年 Context Engineering 趋势** - 该领域的最新发展
* **企业 AI 上下文管理** - 行业采用和最佳实践
* **Context Engineering vs. Vibe Coding** - 持续的辩论和演进

## 贡献

欢迎贡献！请先阅读[贡献指南](CONTRIBUTING.md)。

我们正在寻找：
* 新的 Context Engineering 框架和工具
* 案例研究和实施示例
* 研究论文和学术资源
* 社区工具和资源
* 翻译和本地化

## 关于

Context Engineering 参考资料、框架和最佳实践的精选列表，用于构建生产级 AI 系统。与 vibe coding 的实验性方法不同，Context Engineering 专注于系统化、可扩展、可靠的 AI 系统开发。

**从 [AGENTS.md](https://agents.md) 开始你的 Context Engineering 之旅 - 互操作 AI 上下文管理的基础。**

### 主题标签

`context-engineering` `ai` `enterprise-ai` `production-ai` `context-management` `ai-systems` `agents-md` `bmad-method` `claude-code-spec-workflow` `kiro-specs` `rag` `vector-databases`

---

**选择 Context Engineering 来构建超越原型的生产级 AI 系统！** 🚀

*最后更新：2025年9月*
