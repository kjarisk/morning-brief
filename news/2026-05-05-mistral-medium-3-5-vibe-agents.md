---
date: 2026-05-05
slug: mistral-medium-3-5-vibe-agents
title: "Mistral Medium 3.5: 128B open-weight model with remote coding agents"
category: ai-europe
source_name: "Mistral AI"
source_url: "https://mistral.ai/news/vibe-remote-agents-mistral-medium-3-5"
tags: [mistral, open-weights, coding, swe-bench, europe, vibe]
top_story: false
---

Mistral released Medium 3.5, a 128-billion-parameter dense open-weight model that merges instruction-following, reasoning, and coding into a single set of weights. It scores 77.6% on SWE-bench Verified — ahead of Devstral 2 and larger models like Qwen3.5 397B — with a 256k context window. The model is now the default in both Mistral Vibe (the company's coding platform) and Le Chat (its consumer assistant), and is available in public preview. Weights are open, allowing self-hosted deployment.

Alongside the model, Mistral launched remote coding agents inside Vibe: rather than running locally, agents execute in the cloud in parallel, handling long coding tasks autonomously and notifying the user when complete. This brings Vibe closer to the async agent-coding workflows offered by competitors like GitHub Copilot Workspace and OpenAI Codex. The 128B dense architecture is a notable choice — rather than mixture-of-experts, this is a fully activated model, which typically means stronger performance per activated parameter at the cost of higher inference compute.

For European developers and enterprises looking to self-host a strong coding model with competitive SWE-bench scores, Medium 3.5 is the most capable open-weight option from a European lab to date. The remote agents feature makes Vibe a more practical tool for longer, multi-step software tasks that would otherwise require leaving a coding session running overnight. Read more at [Mistral AI](https://mistral.ai/news/vibe-remote-agents-mistral-medium-3-5).
