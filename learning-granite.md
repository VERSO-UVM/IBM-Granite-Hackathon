# Learning IBM Granite

IBM Granite is a family of open, enterprise-grade AI foundation models built for business use cases. This page collects the key resources you need to get started quickly.

---

## What Is IBM Granite?

IBM Granite models are designed for tasks such as code generation, natural language understanding, summarization, and more. They are available through IBM's [watsonx.ai](https://www.ibm.com/products/watsonx-ai) platform and as open-source models on Hugging Face.

Key properties:
- **Open & transparent** — model weights and training details are publicly available
- **Enterprise-ready** — built with safety, trust, and governance in mind
- **Versatile** — covers code, language, and time-series tasks

---

## Official Documentation & Getting Started

| Resource | Link |
|----------|------|
| IBM Granite product page | <https://www.ibm.com/granite> |
| watsonx.ai platform | <https://www.ibm.com/products/watsonx-ai> |
| IBM Granite on Hugging Face | <https://huggingface.co/ibm-granite> |
| Granite model documentation | <https://www.ibm.com/docs/en/watsonx> |
| IBM Developer — Granite tutorials | <https://developer.ibm.com/components/granite/> |

---

## Model Families

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

## Recommended Learning Path

```
Week Before Hackathon
├── Read the IBM Granite product page
├── Skim the Hugging Face model cards
└── Try a notebook from the Granite cookbook

Kickoff Day (April 12)
├── Attend BJ Hargrave's presentation
└── Set up your watsonx.ai environment

During the Hackathon (April 12–18)
├── Pick an idea from the Ideas page
├── Prototype with the Python SDK or REST API
├── Attend office hours if you get stuck
└── Iterate!
```

---

_Back to [Home](README.md)_
