# 🤖 Agent For Dummies：AI应用/Agent/RAG学习20分钟极速入门傻瓜笔记/八股 🚀

<p center>
  <strong>傻瓜都能看懂的20分钟极速入门agent/RAG/AI应用、20分钟面试前AI应用/Agent/后端/计算机基础八股速成</strong>
</p>

[English Edition](README_EN.md) | [🗺️ 极速通关地图](#-极速通关地图) | [📚 补充知识库](docs/08-supplementary-notes/00-index.md)

[![Language](https://img.shields.io/badge/Language-中文-0f766e?style=for-the-badge&logo=github)](README.md)
[![Format](https://img.shields.io/badge/Format-Markdown-334155?style=for-the-badge&logo=markdown)](docs/)
[![Audience](https://img.shields.io/badge/For-Beginners%20%26%20Busy%20Brains-f97316?style=for-the-badge&logo=lightning)](README.md#-适合谁看)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen.style=for-the-badge)](README.md#-贡献与校正)

---
## 🎯 适合谁看？

- 🙋‍♂️ **想动手做 Agent 的初学者**：太专业的教程一下子看不进去？先来看傻瓜教程吧。
- 🤯 **还有20分钟就要面试想要迅速了解内容补充八股知识的速成er**：精炼、短、只挑重点。背就完了
- ⚡ **ADHD / 容易注意力分散的傻瓜**：我就是傻瓜，太难的名词看不懂、太长的文章看不进去，完全傻瓜友好。
- 🧱 **想补齐底层脚手架的全栈/小白**：需要把大模型、计算机网络、后端和向量检索串成一张清晰的知识网。

---

### 💡 为什么有这个仓库？

> *"RAG、MCP、Function Calling、LoRA、Vector DB、Context Window... 救命！现在的 AI 圈子怎么每天都在造新词？！"*

这是一份我在初学的时候给自己的防止遗忘的简洁版笔记：**把看似高大上的 Agent 和大模型技术的基本概念和人话版讲解记录下来** 

这里没有动辄 100 页的干瘪 PPT，也没有长篇大论的数学公式推导。从零开始，先帮你搭建一张**能落地的技术全局地图**，再按需去补细节。

> ⚠️ **严正声明**：如果笔记里出现任何一个未被解释的怪异缩写，请把它当成 Bug 抓出来，欢迎大家一起补充和指正


## 🗺️ 笔记地图

不必像背课本一样从头读到尾！看标题，挑你现在最困惑的点直接戳进去👇

| 序号 | 章节 | 读完能去跟人吹什么牛 / 解决什么问题 |
| :---: | :--- | :--- |
| **01** | 🤖 [Agent 到底是什么](docs/01-agent-essentials.md) | 一文速懂 Agent！ReAct、工作流、多 Agent 架构和框架有什么？ |
| **02** | 🛠️ [工具、MCP 与 Skills](docs/02-tools-mcp-and-skills.md) | 彻底搞懂 Function Calling、MCP 和 Skill 的区别！ |
| **03** | 🔍 [RAG 与检索](docs/03-rag-and-retrieval.md) | RAG 文档切片、向量召回、重排（Rerank）的全链路图文指南。 |
| **04** | 🧠 [上下文工程与提示词](docs/04-context-engineering-and-prompting.md) | Agent实战干货教程/八股 |
| **05** | 🎛️ [模型适配与微调](docs/05-fine-tuning-and-adaptation.md) | 什么时候该微调？LoRA、QLoRA、DPO 到底在调什么？ |
| **06** | ⚡ [大模型与 AI 基础](docs/06-llm-and-ai-basics.md) | Token、Attention、采样参数（Temperature）、向量... 扫盲大模型高频底层概念。 |
| **07** | 👁️ [模型与多模态](docs/07-models-and-multimodality.md) | 常见大模型BERT、LLaMA、ViT、CLIP、InternVL...  |
| **08** | 📚 [其他补充知识索引](docs/08-supplementary-notes/00-index.md) | 需要 Transformer、SQL/ES、Redis、网络知识时随查随用。临近面试八股速背 |

---

## 🍽️ 食用指南

根据你现在的状态，选择最舒服的阅读姿势：

* **⚡agent最重点**
  👉 读 `01` → `02` → `03`。迅速搞懂 Agent 是怎么循环运行、怎么调工具、怎么查知识库的。20分钟背完开面！
* **🚑 想了解后端八股 or 计算机基础八股 or 大模型学习其他内容 **  
  👉  [补充知识索引](docs/08-supplementary-notes/00-index.md) 

---

## 📂 仓库骨架

```text
.
├── 📁 docs/                         # 核心知识库
│   ├── 01-07                        # 🎯 主线：Agent 与 AI 应用核心硬核干货
│   └── 08-supplementary-notes/      # 📚 补充：大模型、后端与计算机基础工具箱
├── 📁 assets/                       # 🎨 笔记插图
├── 📄 README.md                     # 👈 当前页面 (中文版)
└── 📄 README_EN.md                  # 🌐 English Edition
```



## 🤝 贡献与校正

AI 技术迭代比翻书还快，笔记难免有疏漏或过时的地方。如果你发现：

- ❌ 哪里的解释有错或者写得不够明白；
- ⌛ 哪个技术点的 API 或概念已经过时了；
- 💡 有更生动有趣的“人话”解释方式。

**非常欢迎提交 Issue 或 Pull Request！** 让我们一起把这份笔记改成最适合新人小白和 ADHD 脑子的 Agent 第一课！

---

## 🖼️ 图片与署名声明

`assets/` 目录下仅保留了笔记实际引用的示意图，用于辅助上下文理解。部分图片版权可能属于原作者。本仓库的开源许可证仅覆盖作者原创文字内容，不自动授予第三方图片的再授权。若需公开复用相关图片，请先确认原作者授权。

---

## 📜 许可证 (License)

本仓库的原创文字内容采用 [CC BY 4.0 (知识共享署名 4.0 国际许可协议)](LICENSE) 发布。  
只要保留原作者署名，欢迎自由转载、改编和引用！
