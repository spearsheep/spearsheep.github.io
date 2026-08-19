---
layout: page
title: Privacy-preserving synthetic data
description: LLM-generated clinical synopses for stronger depression prediction with less information leakage.
category: Human-centered ML
year: 2024
importance: 5
featured: false
impact: RMSE 4.39 vs 5.01 baseline
---

<div class="case-study" markdown="1">
<p class="case-study__lede">This project asked whether synthetic clinical summaries could improve depression prediction without simply reproducing sensitive patient language.</p>

<div class="case-study__facts">
  <div><span>Venue</span><strong>CogSci 2025</strong></div>
  <div><span>Methods</span><strong>LLaMA 3 · QLoRA · BERT · PCA</strong></div>
  <div><span>Task</span><strong>PHQ-8 depression prediction</strong></div>
</div>

## Findings

We trained a chain-of-thought-style LLaMA 3 QLoRA model to generate privacy-preserving synopses from interview transcripts. A downstream BERT regressor trained with the synthetic data reached **4.39 RMSE**, compared with a **5.01** baseline.

PCA on CLS embeddings showed that the generated data retained clinically useful structure, including severe-depression cases. Embedding-distance analysis also found less information leakage than the baseline generation method.

<a class="button button--primary" href="https://arxiv.org/abs/2411.17672" target="_blank" rel="noopener noreferrer">Read the paper <span aria-hidden="true">↗</span></a>
</div>
