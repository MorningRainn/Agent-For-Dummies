# 🤖 Agent For Dummies: a 20-Minute, No-Nonsense Introduction to AI Apps, Agents, RAG, and Interview Essentials 🚀

<p align="center">
  <strong>A fast, plain-English guide to agents, RAG, AI applications, and the backend or CS interview essentials that tend to show up twenty minutes before the interview.</strong>
</p>

[简体中文](README.md) | [🗺️ Fast-Track Map](#-the-note-map) | [📚 Supplementary Notes](docs/08-supplementary-notes/00-index.md)

[![Language](https://img.shields.io/badge/Language-English-0f766e?style=for-the-badge&logo=github)](README_EN.md)
[![Format](https://img.shields.io/badge/Format-Markdown-334155?style=for-the-badge&logo=markdown)](docs/)
[![Audience](https://img.shields.io/badge/For-Beginners%20%26%20Busy%20Brains-f97316?style=for-the-badge&logo=lightning)](#-who-is-this-for)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge)](#-contribute-and-correct)

---

## 🎯 Who Is This For?

- 🙋 **Agent beginners**: the heavyweight tutorials make your eyes glaze over? Start with the dummy-friendly version.
- 🤯 **Last-minute crammers**: an interview is twenty minutes away and you need the useful vocabulary, fast. This is concise, selective, and built for review.
- ⚡ **ADHD / easily distracted readers**: dense terminology and long articles are exhausting. These notes aim to explain the terms in place and keep the route short.
- 🧱 **Full-stack learners filling in the scaffolding**: connect LLMs, networking, backend services, and vector retrieval into one useful mental model.

---

### 💡 Why Does This Repository Exist?

> *"RAG, MCP, Function Calling, LoRA, Vector DB, Context Window... why does the AI world mint a new acronym every morning?"*

These are the concise notes I wish I had while learning: the basic concepts behind agents and LLM applications, explained in ordinary language before the jargon takes over.

There are no hundred-page slide decks or obligatory math detours. Start by building a **usable map of the system**, then open the details only when you need them.

> ⚠️ **Bug-report policy**: if an unexplained acronym sneaks into a note, please treat it as a bug. Issues and corrections are welcome.

## 🗺️ The Note Map

Do not read this like a textbook from cover to cover. Pick the question that is bothering you today and jump in.

| No. | Topic | What you can explain afterwards |
| :---: | :--- | :--- |
| **01** | 🤖 [What Is an Agent?](docs/01-agent-essentials.md) | How do an LLM, memory, planning, and tools combine into an agent? When should you use ReAct, a workflow, or multi-agent systems? |
| **02** | 🛠️ [Tools, MCP, and Skills](docs/02-tools-mcp-and-skills.md) | Why can AI send email or edit a spreadsheet? What is the actual difference among Function Calling, MCP, and Skills? |
| **03** | 🔍 [RAG and Retrieval](docs/03-rag-and-retrieval.md) | How do you give an LLM an external knowledge base? Learn the whole path from chunks and vector search to reranking. |
| **04** | 🧠 [Context Engineering and Prompting](docs/04-context-engineering-and-prompting.md) | How can an agent retain the important facts without packing its context window past capacity? |
| **05** | 🎛️ [Model Adaptation and Fine-Tuning](docs/05-fine-tuning-and-adaptation.md) | Do not train a giant model by reflex. When is fine-tuning warranted, and what do LoRA, QLoRA, and DPO actually adjust? |
| **06** | ⚡ [LLM and AI Basics](docs/06-llm-and-ai-basics.md) | Tokens, attention, sampling parameters, embeddings, and other high-frequency LLM concepts. |
| **07** | 👁️ [Models and Multimodality](docs/07-models-and-multimodality.md) | What are BERT, LLaMA, ViT, CLIP, and InternVL each good at? |
| **08** | 📚 [Supplementary Notes Index](docs/08-supplementary-notes/00-index.md) | A just-in-time reference for Transformers, SQL/Elasticsearch, Redis, backend work, networking, operating systems, and ML. |

---

## 🍽️ Choose Your Route

Pick the route that matches your current energy level:

- **⚡ I only need the agent essentials**
  Read `01` → `02` → `03`. In about twenty minutes, understand the agent loop, tool use, and knowledge retrieval.
- **🚑 I need backend or computer-science review**
  Open the [Supplementary Notes Index](docs/08-supplementary-notes/00-index.md). It is a toolbox, not a course you must finish in order.

## 📂 Repository Layout

```text
.
├── docs/                         # Core knowledge base
│   ├── 01-07                     # Main route: agents and LLM applications
│   └── 08-supplementary-notes/   # Transformers, ML, backend, and CS essentials
├── assets/                       # Diagrams used by the notes
├── README.md                     # Chinese edition
└── README_EN.md                  # English edition
```

## 🤝 Contribute and Correct

AI changes faster than the bookmarks folder. Please open an Issue or Pull Request when you find:

- an incorrect or unclear explanation;
- an outdated API or concept;
- a more vivid plain-language explanation.

Help make this a better first agent lesson for newcomers and distractible brains alike.

---

## 🖼️ Images and Attribution

`assets/` contains only diagrams referenced by these notes. Some images may belong to their original creators and are retained for learning context. The repository license covers the author's original writing only; it does not automatically grant permission to redistribute third-party images. Please confirm the original license before public reuse.

---

## 📜 License

The original written notes are available under [CC BY 4.0](LICENSE). Reuse, adapt, and share them freely with attribution.
