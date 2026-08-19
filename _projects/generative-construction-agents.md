---
layout: page
title: Generative construction agents
description: LLM-backed embodied agents that plan, build, inspect, and repair structures in Minecraft.
category: Embodied AI
year: 2024–present
importance: 2
featured: true
impact: +25% one-shot accuracy · +12% spatial consistency
---

<div class="case-study" markdown="1">
<p class="case-study__lede">How can a language model turn an open-ended visual instruction into a structure, verify its own work, and improve after failure?</p>

<div class="case-study__facts">
  <div><span>Lab</span><strong>Generative Machine Learning Research Group</strong></div>
  <div><span>Advisor</span><strong>Prof. Jiatao Gu</strong></div>
  <div><span>Methods</span><strong>Multimodal agents · SFT · RL</strong></div>
</div>

## Approach

I built a multimodal agent that translates language and image inputs into a structured Blueprint DSL, then executes the plan through a Node.js bridge controlling Minecraft bots. A RAG memory and reflection loop lets the agent reuse experience instead of treating each build as a one-off task.

I later added multi-view visual feedback and world-state block scanning for exact structural diffs and actionable repair plans. This iterative verification improved accuracy by **25%** over one-shot generation. A trajectory-based Qwen3 training pipeline further improved spatial consistency and structural correctness by **12%**.

<a class="button button--primary" href="https://arxiv.org/abs/2411.17255" target="_blank" rel="noopener noreferrer">Read the APT paper <span aria-hidden="true">↗</span></a>
</div>
