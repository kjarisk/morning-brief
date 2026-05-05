---
date: 2026-05-05
slug: tradingagents-llm-trading-github
title: "TradingAgents: multi-agent LLM trading framework hits 67K GitHub stars"
category: ml-engineering
source_name: "GitHub"
source_url: "https://github.com/tauricresearch/tradingagents"
tags: [multi-agent, langgraph, finance, github-trending, python]
top_story: false
---

TradingAgents, a LangGraph-based framework that simulates a professional trading firm using multiple LLM agents, is trending on GitHub with 67,000 stars. The framework assigns specialized roles — fundamental analyst, sentiment analyst, technical analyst, risk manager, and trader — each equipped with domain-specific tools and constraints. It supports all major LLM providers: OpenAI GPT-5.x, Claude 4.x, Grok 4.x, Gemini 3.x, DeepSeek, Qwen, and local models via Ollama.

The practical appeal for ML engineers is the architecture pattern rather than production deployment: TradingAgents demonstrates how to decompose a complex analytical task across a team of specialized agents with different reasoning styles and risk tolerances, using LangGraph's stateful graph primitives to coordinate them. The v0.2.0 release in February 2026 added multi-provider LLM support and a Trading-R1 technical report. A terminal interface is reportedly in development.

As a learning resource and proof-of-concept, TradingAgents is particularly useful for developers building document-analysis pipelines, research assistants, or any multi-agent system where different agents need specialized context windows and tool access. The financial trading framing makes the role decomposition intuitive even for engineers without a finance background. Read more at [GitHub](https://github.com/tauricresearch/tradingagents).
