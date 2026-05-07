---
date: 2026-05-07
slug: local-deep-research-local-ai-agent
title: "local-deep-research: private research agent hits ~95% on SimpleQA"
category: ml-engineering
source_name: "GitHub"
source_url: "https://github.com/LearningCircuit/local-deep-research"
tags: [research-agent, ollama, local-llm, privacy, python]
top_story: false
---

local-deep-research is a Python research agent that runs entirely on your own hardware and achieves approximately 95% on the SimpleQA benchmark when backed by a model like Qwen3-27B on a consumer GPU. It supports both local LLMs via Ollama and cloud providers including Anthropic, Google, and OpenAI, and searches across more than ten sources including the web, arXiv, PubMed, and your own private document collections.

The project has 5,800 stars and added 530 today, suggesting it's hitting a nerve among developers who want deep research capability without sending their queries to a third-party API. All data remains local and encrypted. The architecture does multi-step agentic research — formulating sub-queries, synthesizing results, and generating cited reports — rather than a single retrieval pass.

For teams working with sensitive internal documents or researchers who want to keep their queries private, this provides a viable alternative to commercial research agents. The practical limitation is that consumer hardware at the 27B parameter tier is significantly slower than a cloud API, so it is best suited to batch research tasks rather than interactive use.

Read more at [GitHub](https://github.com/LearningCircuit/local-deep-research).
