---
layout: page
title: Job-resume matching with RL
description: Structured retrieval and recruiter-intent modeling with Qwen, SFT, and GRPO.
category: Reinforcement learning
year: 2025
importance: 3
featured: true
impact: +17% nDCG · +23% recall
---

<div class="case-study" markdown="1">
<p class="case-study__lede">At Columbia DAP Lab, I worked on making job-resume retrieval both more accurate and easier to interpret.</p>

<div class="case-study__facts">
  <div><span>Lab</span><strong>Columbia DAP</strong></div>
  <div><span>Advisor</span><strong>Prof. Zhou Yu</strong></div>
  <div><span>Methods</span><strong>Qwen · SFT · GRPO · distillation</strong></div>
</div>

## Approach

I fine-tuned Qwen2.5 and Qwen3 to generate structured, Elasticsearch-style retrieval fields from resumes and job descriptions. The training system combined scalable synthetic-data generation, SFT with DeepSpeed ZeRO-3, and GRPO in VERL with a custom reward, curriculum, and tolerant parsing strategy.

The resulting system improved nDCG by **17%** over the ConFit-V2 baseline and recall by **23%**. A one-shot self-rationalization stage inferred recruiter-intent keywords, improving interpretability and nDCG by another **10%**.

<a class="button button--quiet" href="https://www.cs.columbia.edu/~zhouyu/" target="_blank" rel="noopener noreferrer">Visit the advisor's page <span aria-hidden="true">↗</span></a>
</div>
