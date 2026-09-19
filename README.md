# Agent For Dummies：AI 应用 / Agent 极速入门笔记

[English](README_EN.md) | [学习路线](#从这里开始) | [补充知识](docs/08-supplementary-notes/00-index.md)

[![Language](https://img.shields.io/badge/language-Chinese-0f766e)](README.md)
[![Format](https://img.shields.io/badge/format-Markdown-334155)](docs/)
[![Audience](https://img.shields.io/badge/for-beginners%20and%20busy%20brains-f97316)](#适合谁看)

> 给想学 AI 应用和 Agent、但不想先把自己训练成术语词典的人。

这是一份从零开始的个人学习笔记汇总，定位是 **AI 应用 / Agent 的极简常用知识**。它不假设你已经会微服务、向量数据库或一长串框架名；先帮你搭起能用的地图，再按需深入细节。

如果一个缩写没有被解释，请把它当成这份笔记的 Bug。

## 适合谁看

- 想从聊天机器人走到“能调用工具、能查资料、能完成任务”的 Agent 初学者。
- 想快速补齐 RAG、MCP、Skills、上下文工程等高频概念的人。
- 注意力容易被长篇铺垫带走的人：每篇先给结论，术语尽量就地解释，主线可以顺读也可以跳读。
- 需要把大模型、计算机基础、后端与检索知识串成一张图的人。

## 你会得到什么

- 一条从 Agent 核心循环到工具、检索、上下文和模型选择的阅读路线。
- 可以在做 AI 应用时随手回查的 RAG、SQL/Elasticsearch、Transformer、Redis、网络等笔记。
- 带图示的概念解释，少一点“背下来”，多一点“知道它在系统里干什么”。

## 从这里开始

不必按目录从头背到尾。先读前四篇，你已经能听懂大多数 Agent 项目在说什么；遇到不会的概念，再跳到后面的基础或补充笔记。

| 顺序 | 读什么 | 读完能回答什么 |
| --- | --- | --- |
| 01 | [Agent 到底是什么](docs/01-agent-essentials.md) | LLM、规划、记忆、工具如何组成 Agent？ReAct、工作流、多 Agent 分别适合什么？ |
| 02 | [工具、MCP 与 Skills](docs/02-tools-mcp-and-skills.md) | Agent 为什么能“做事”？Function Calling、MCP、Skill 不该混为一谈。 |
| 03 | [RAG 与检索](docs/03-rag-and-retrieval.md) | 文档怎样变成可问答知识库？切片、召回、重排、评估怎么串起来？ |
| 04 | [上下文工程与提示词](docs/04-context-engineering-and-prompting.md) | Agent 怎么记住重点，又不把上下文窗口塞爆？ |
| 05 | [模型适配与微调](docs/05-fine-tuning-and-adaptation.md) | 什么时候该微调？LoRA、QLoRA、DPO 分别在解决什么？ |
| 06 | [大模型与 AI 基础](docs/06-llm-and-ai-basics.md) | Token、注意力、采样、向量、模型评估和系统术语到底是什么？ |
| 07 | [模型与多模态](docs/07-models-and-multimodality.md) | BERT、LLaMA、ViT、CLIP、InternVL 等模型有什么差别？ |
| 08 | [其他补充知识](docs/08-supplementary-notes/00-index.md) | 需要 Transformer、SQL、后端、网络或机器学习时去这里按需查。 |

## 三种阅读方式

**二十分钟扫盲**：01 → 02 → 03。先知道 Agent 如何循环、如何调用工具、如何从知识库找答案。

**准备做一个 AI 应用**：01 → 02 → 03 → 04，再根据需要看 05 或 06。

**被术语卡住了**：直接从 [补充知识索引](docs/08-supplementary-notes/00-index.md) 点进去。没有考试，不需要为跳读道歉。

## 仓库结构

```text
.
├── docs/
│   ├── 01-07  主线：Agent 与大模型应用核心知识
│   └── 08-... 补充：NLP、机器学习、检索、后端与计算机基础
├── assets/    笔记中实际使用的图示
├── README.md  中文版
└── README_EN.md English edition
```

## 笔记原则

- **先有地图，再补细节**：先理解组件为什么存在，再看参数和框架。
- **框架中立**：重点是可迁移的概念，而不是某个工具今天的 API 名称。
- **能查就不硬背**：补充笔记是工具箱，不是另一门需要从头修完的课。
- **持续校正**：有错误、过时内容或更好解释，欢迎开 Issue 或 Pull Request。

## 图片与署名

`assets/` 仅保留笔记实际引用的图示，用于学习上下文。其中可能包含原作者享有权利的材料；仓库许可证仅覆盖原创文字，不自动授予第三方图片的再授权。若要公开复用图片，请先确认其授权。

## 许可证

原创文字采用 [CC BY 4.0](LICENSE) 许可证发布。复用或改编时，请保留署名。
