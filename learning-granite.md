# Learning Granite for the Sprint

This page is the sprint onboarding hub for **Granite**, **Mellea**, and **Docling** project work.

---

## What Is IBM Granite?

IBM Granite models are designed for tasks such as code generation, natural language understanding, summarization, and more. They are available through IBM's [watsonx.ai](https://www.ibm.com/products/watsonx-ai) platform and as open-source models on Hugging Face.

Key properties:
- **Open and transparent** foundation models
- **Enterprise-oriented** safety and governance focus
- **Strong fit for coding and agentic tasks** in this sprint context

---

## Sprint Learning Path (Recommended)

1. **Start with one recipe** from the Granite agent cookbook.
2. **Reproduce it locally** and document what you changed.
3. **Choose your direction**: Granite agent workflow, Mellea generative programming, or Docling document intelligence.
4. **Define an MVP** you can demo by April 18.

---

## Official Documentation & Getting Started

| Resource | Link |
|----------|------|
| IBM Granite product page | <https://www.ibm.com/granite> |
| watsonx.ai platform | <https://www.ibm.com/products/watsonx-ai> |
| IBM Granite on Hugging Face | <https://huggingface.co/ibm-granite> |
| Granite model documentation | <https://www.ibm.com/docs/en/watsonx> |
| IBM Developer — Granite tutorials | <https://developer.ibm.com/components/granite/> |
| Granite Agent Cookbook | <https://github.com/ibm-granite-community/granite-agent-cookbook> |
| Mellea | <https://github.com/generative-computing/mellea> |
| Docling | <https://github.com/docling-project/docling> |

---

## Sprint Project Tracks

### Granite Agents
Build agentic workflows for coding, documentation, or analysis tasks.

---

## Granite Model Families

### Granite Language Models
General-purpose large language models for text tasks (summarization, classification, Q&A, generation).

- [ibm-granite/granite-3.3-8b-instruct](https://huggingface.co/ibm-granite/granite-3.3-8b-instruct) — 8B parameter instruction-tuned model
- [ibm-granite/granite-3.3-2b-instruct](https://huggingface.co/ibm-granite/granite-3.3-2b-instruct) — lightweight 2B parameter model

### Granite Code Models
Specialized models for code generation, explanation, and completion.

- [ibm-granite/granite-3.3-8b-instruct](https://huggingface.co/ibm-granite/granite-3.3-8b-instruct)
- [Granite Code Models overview](https://github.com/ibm-granite/granite-code-models)

### Granite Guardian
A model for safety and trust evaluation.

- [ibm-granite/granite-guardian-3.2-5b](https://huggingface.co/ibm-granite/granite-guardian-3.2-5b)

---

## Hands-On Tutorials & Notebooks

| Tutorial | Link |
|----------|------|
| Getting started with watsonx.ai | <https://developer.ibm.com/tutorials/awb-getting-started-watsonx-ai/> |
| Prompt engineering basics | <https://www.ibm.com/topics/prompt-engineering> |
| Granite code generation notebook | <https://github.com/ibm-granite-community/granite-code-cookbook> |
| Granite language cookbook | <https://github.com/ibm-granite-community/granite-language-cookbook> |
| IBM Granite community GitHub | <https://github.com/ibm-granite-community> |
| Granite agent cookbook | <https://github.com/ibm-granite-community/granite-agent-cookbook> |

---

## Key Concepts to Learn

1. **Prompt Engineering** — How to craft effective prompts to get the best output from a model.
   - [IBM guide to prompt engineering](https://www.ibm.com/topics/prompt-engineering)

2. **Retrieval-Augmented Generation (RAG)** — Combine a language model with your own data.
   - [What is RAG?](https://www.ibm.com/topics/retrieval-augmented-generation)

3. **Fine-tuning** — Adapt a pre-trained model to a specific domain or task.
   - [Fine-tuning overview](https://www.ibm.com/topics/fine-tuning)

4. **LangChain / LlamaIndex with Granite** — Popular frameworks for building LLM applications.
   - [LangChain docs](https://python.langchain.com/docs/introduction/)
   - [LlamaIndex docs](https://docs.llamaindex.ai/)

---

## APIs & SDKs

| Tool | Link |
|------|------|
| watsonx Python SDK (`ibm-watsonx-ai`) | <https://ibm.github.io/watsonx-ai-python-sdk/> |
| IBM Cloud API docs | <https://cloud.ibm.com/apidocs/watsonx-ai> |
| OpenAI-compatible API on watsonx | <https://www.ibm.com/docs/en/watsonx/saas?topic=apis-text-generation> |

---

## Community & Support

- [IBM Granite GitHub organization](https://github.com/ibm-granite)
- [IBM Granite community](https://github.com/ibm-granite-community)
- [IBM Developer community](https://developer.ibm.com/)
- Ask questions during [Office Hours](office-hours.md) with BJ Hargrave from IBM!

---

## Recommended Week Plan

```
Before Kickoff
├── Read the IBM Granite product page
├── Skim Granite agent cookbook recipes
└── Pick a tentative project track (Granite / Mellea / Docling)

Kickoff Day (Sunday, April 12)
├── Attend BJ Hargrave's workshop
├── Confirm tooling setup
└── Form teams and choose scoped goals

Sprint Week (April 13–18)
├── Build MVP and test daily
├── Attend office hours when blocked
├── Prepare one meaningful contribution artifact
└── Finalize slides + demo for closing session
```

---

_Back to [Home](README.md)_
