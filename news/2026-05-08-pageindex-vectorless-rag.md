---
date: 2026-05-08
slug: pageindex-vectorless-rag
title: "PageIndex: RAG without vectors, using tree search and LLM reasoning"
category: ml-engineering
source_name: "GitHub"
source_url: "https://github.com/VectifyAI/PageIndex"
tags: [rag, llm, retrieval, document-intelligence, open-source, python]
top_story: false
---

PageIndex by VectifyAI is an open-source Python library for retrieval-augmented generation that skips the embedding-and-vector-search pipeline entirely. Instead, it builds a hierarchical tree index from document structure, then uses LLM reasoning and tree search — inspired by AlphaGo's approach — to navigate to the most relevant sections as a human expert would. The project hit 29,700 GitHub stars and was in the top 10 trending repositories on May 8, 2026.

The practical advantage over chunk-based vector RAG is traceability and structural awareness: retrieved sections come with page and section references, the retrieval process is auditable, and documents are segmented by natural boundaries rather than arbitrary token windows. On FinanceBench, a demanding benchmark for financial document QA, PageIndex achieves 98.7% accuracy — substantially above what chunk-based vector approaches typically reach.

The library is available as a self-hosted open-source repo, as an MCP server (pageindex-mcp), and as a cloud API. The cookbooks in the repo show a simple RAG setup, vision RAG for PDF pages, and an agentic vectorless RAG demo. For developers building document-heavy applications with LLMs, this is worth benchmarking against your existing pipeline.

Read more at [GitHub](https://github.com/VectifyAI/PageIndex).
