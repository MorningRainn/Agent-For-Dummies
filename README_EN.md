# Agent For Dummies: A Fast Introduction to AI Apps and Agents

[简体中文](README.md) | [Learning path](#start-here) | [Supplementary notes](docs/08-supplementary-notes/00-index.md)

[![Language](https://img.shields.io/badge/language-English-2563eb)](README_EN.md)
[![Format](https://img.shields.io/badge/format-Markdown-334155)](docs/)
[![Audience](https://img.shields.io/badge/for-beginners%20and%20busy%20brains-f97316)](#who-this-is-for)

> For people who want to build AI applications and agents without first becoming a walking glossary.

This is a compact, beginner-friendly set of personal notes on AI applications and agents. It starts with the map: how an agent thinks, uses tools, retrieves knowledge, and manages context. Details come later, when they are useful.

If an acronym appears without an explanation, consider it a bug.

## Who This Is For

- Beginners moving from chatbots to agents that can use tools, look up knowledge, and complete tasks.
- Builders who need a fast, practical introduction to RAG, MCP, Skills, and context engineering.
- Readers with limited attention bandwidth: short sections, local explanations, and a main path that supports both linear reading and jumping around.
- Anyone trying to connect LLM concepts with retrieval, backend engineering, and computer-science fundamentals.

## What You Will Get

- A path from the agent loop to tools, retrieval, context, and model selection.
- Reference notes for RAG, SQL/Elasticsearch, Transformers, Redis, networking, and more.
- Diagram-supported explanations focused on what each component does in a real system.

## Start Here

You do not need to memorize the repository in order. Read the first four notes to understand most conversations around agent projects, then use the fundamentals and supplementary notes when a concept blocks you.

| Order | Read this | You will be able to answer |
| --- | --- | --- |
| 01 | [What is an agent?](docs/01-agent-essentials.md) | How do an LLM, planning, memory, and tools become an agent? When should I use ReAct, workflows, or multi-agent systems? |
| 02 | [Tools, MCP, and Skills](docs/02-tools-mcp-and-skills.md) | How does an agent actually do things? Why are Function Calling, MCP, and Skills different? |
| 03 | [RAG and retrieval](docs/03-rag-and-retrieval.md) | How does a document become a searchable knowledge base? How do chunking, retrieval, reranking, and evaluation fit together? |
| 04 | [Context engineering and prompting](docs/04-context-engineering-and-prompting.md) | How can an agent remember the important parts without overflowing its context window? |
| 05 | [Fine-tuning and adaptation](docs/05-fine-tuning-and-adaptation.md) | When should I fine-tune? What are LoRA, QLoRA, and DPO solving? |
| 06 | [LLM and AI basics](docs/06-llm-and-ai-basics.md) | What do tokens, attention, sampling, embeddings, evaluation, and common systems terms mean? |
| 07 | [Models and multimodality](docs/07-models-and-multimodality.md) | How do BERT, LLaMA, ViT, CLIP, and InternVL differ? |
| 08 | [Supplementary notes](docs/08-supplementary-notes/00-index.md) | Where can I look up Transformers, SQL, backend work, networking, or ML algorithms? |

## Pick Your Route

**I have twenty minutes**: 01 → 02 → 03. Learn the loop, the tools, and the knowledge base.

**I want to build an AI application**: 01 → 02 → 03 → 04, then add 05 or 06 as needed.

**I am stuck on a term**: go straight to the [supplementary index](docs/08-supplementary-notes/00-index.md). There is no exam, and skipping ahead is allowed.

## Repository Layout

```text
.
├── docs/
│   ├── 01-07  Core notes for agents and LLM applications
│   └── 08-... Supplementary NLP, ML, retrieval, backend, and CS notes
├── assets/    Diagrams actually used by the notes
├── README.md  Chinese edition
└── README_EN.md English edition
```

## Principles

- **Map before details**: understand why a component exists before memorizing APIs or parameters.
- **Framework-neutral**: the focus is transferable knowledge, not a framework's API of the week.
- **Look it up, do not worship it**: the supplementary notes are a toolbox, not another course to complete linearly.
- **Keep correcting**: issues and pull requests for errors, stale material, or clearer explanations are welcome.

## Images and Attribution

`assets/` contains only diagrams referenced by the notes. Some may belong to their original creators and are kept for learning context. The repository license applies only to original writing; it does not automatically grant rights to third-party images. Verify image rights before redistributing them.

## License

The original written notes are available under [CC BY 4.0](LICENSE). Please retain attribution when you reuse or adapt them.
