---
date: 2026-05-08
slug: openai-gpt-realtime-2-voice-models
title: "OpenAI drops three real-time voice API models with GPT-5-class reasoning"
category: ai-models
source_name: "OpenAI"
source_url: "https://openai.com/index/advancing-voice-intelligence-with-new-models-in-the-api/"
tags: [openai, voice, api, realtime, translation, speech-to-text]
top_story: false
---

OpenAI released three new real-time audio models to its API on May 7, 2026. GPT-Realtime-2 is the first voice model with GPT-5-class reasoning — it handles harder multi-step requests, supports parallel tool calls, has a 128K context window, and recovers more gracefully when a task fails mid-conversation. GPT-Realtime-Translate handles live interpretation across 70+ input languages into 13 output languages, trained on professional interpreter audio so it waits for enough spoken context before producing speech. GPT-Realtime-Whisper adds live streaming transcription.

The practical angle for developers: GPT-Realtime-Translate is purpose-built for customer support, cross-border sales, and creator platforms — it won't stray outside the translation task the way a general model might. The Realtime API itself is now generally available for production, with new features including remote MCP server support, image inputs, phone calling via SIP, and a playground for testing all three models.

For anyone building voice agents or multilingual pipelines, this is a significant step up in capability without requiring developers to manage separate pipelines for reasoning and audio. The models are available immediately via the existing Realtime API endpoint.

Read more at [OpenAI](https://openai.com/index/advancing-voice-intelligence-with-new-models-in-the-api/).
