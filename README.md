
# 7 repos to actually learn AI in 2026

> not courses. not youtube. github. everything you need is free.

---

## 1. microsoft/generative-ai-for-beginners — GenAI from zero
<img width="271" height="83" alt="Снимок экрана — 2026-05-06 в 17 22 02" src="https://github.com/user-attachments/assets/396b77fe-efc1-4796-a112-11c1446b4982" />


**⭐ 98,000** · [github.com/microsoft/generative-ai-for-beginners](https://github.com/microsoft/generative-ai-for-beginners)

21 structured lessons by Microsoft Cloud Advocates.  
Covers: prompting, embeddings, RAG, agents, fine-tuning, responsible AI.  
Each lesson has video + written content + code assignments.

```
lesson 01 → intro to GenAI & LLMs
lesson 07 → building chat applications
lesson 09 → building image generation apps
lesson 12 → designing UX for AI applications
lesson 18 → fine-tuning LLMs
lesson 21 → building AI agents
```

**Best for:** complete beginners who want structure.

---

## 2. mlabonne/llm-course — full LLM roadmap

**⭐ 35,000** · [github.com/mlabonne/llm-course](https://github.com/mlabonne/llm-course)

Three-part roadmap: LLM Fundamentals → LLM Scientist → LLM Engineer.  
Every section links to Colab notebooks you can run right now.

```
Part 1: Math, Python, NLP fundamentals
Part 2: LLM architecture, training, RLHF, evaluation
Part 3: RAG, inference optimization, deployment, agents
```

**Best for:** people who want a complete roadmap, not just isolated tutorials.

---

## 3. rasbt/LLMs-from-scratch — build ChatGPT in PyTorch

**⭐ 42,000** · [github.com/rasbt/LLMs-from-scratch](https://github.com/rasbt/LLMs-from-scratch)

Step-by-step implementation of a GPT-style LLM from scratch.  
No magic. Every component explained with code.

```python
# what you'll build:
tokenizer        → BPE from scratch
attention        → multi-head self-attention
architecture     → GPT-2 style transformer
pretraining      → train on your own text data
fine-tuning      → instruction-following, classification
```

You don't understand transformers until you've coded one.  
**Best for:** people who want to understand what's actually happening inside the model.

---

## 4. karpathy/nanoGPT — train GPT yourself

**⭐ 57,000** · [github.com/karpathy/nanoGPT](https://github.com/karpathy/nanoGPT)

~300 lines of code. Actually trains. Runs on a single GPU.  
Reproduces GPT-2 (124M). Clean enough to read in one sitting.

```bash
git clone https://github.com/karpathy/nanoGPT
cd nanoGPT
python data/shakespeare/prepare.py
python train.py config/train_shakespeare_char.py
```

Fastest way to understand what's happening inside the model.  
**Best for:** engineers who learn by running code, not reading papers.

---

## 5. openai/openai-cookbook — practical API patterns

**⭐ 67,000** · [github.com/openai/openai-cookbook](https://github.com/openai/openai-cookbook)

Real production patterns, not toy examples.

```
→ RAG with vector databases
→ function calling & tool use
→ structured outputs
→ agent loops
→ evals and benchmarking
→ fine-tuning workflows
→ multimodal (vision, audio, images)
```

**Best for:** developers building products on top of LLMs.

---

## 6. microsoft/ai-agents-for-beginners — agents from scratch

**⭐ 28,000** · [github.com/microsoft/ai-agents-for-beginners](https://github.com/microsoft/ai-agents-for-beginners)

12 lessons. The missing curriculum for building agents properly.

```
lesson 01 → intro to AI agents
lesson 03 → agentic design patterns
lesson 05 → tool use
lesson 07 → planning agents
lesson 09 → multi-agent systems
lesson 11 → safety & responsible agents
```

Covers frameworks: AutoGen, Semantic Kernel, Azure AI Foundry.  
**Best for:** devs who already know LLMs and want to build autonomous systems.

---

## 7. anthropics/anthropic-cookbook — build with Claude

**⭐ 12,000** · [github.com/anthropics/anthropic-cookbook](https://github.com/anthropics/anthropic-cookbook)

Most underrated repo in this list.

```
→ prompt engineering techniques
→ tool use & function calling
→ computer use (Claude controls a browser)
→ multimodal (images, documents, vision)
→ citations & RAG patterns
→ sub-agents & orchestration
```

**Best for:** anyone building on Claude / Anthropic API.

---

## Summary

| # | Repo | Stars | Best for |
|---|------|-------|----------|
| 1 | microsoft/generative-ai-for-beginners | 98k | complete beginners |
| 2 | mlabonne/llm-course | 35k | structured roadmap |
| 3 | rasbt/LLMs-from-scratch | 42k | understanding internals |
| 4 | karpathy/nanoGPT | 57k | hands-on training |
| 5 | openai/openai-cookbook | 67k | building products |
| 6 | microsoft/ai-agents-for-beginners | 28k | agent development |
| 7 | anthropics/anthropic-cookbook | 12k | building with Claude |

---

*Star counts as of May 2026.*
