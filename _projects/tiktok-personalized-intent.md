---
layout: page
title: Personalized E-commerce Intent Model Distillation at TikTok
description: Model distillation at production scale for personalized e-commerce intent prediction.
category: Industry experience
year: 2026–present
importance: 1
featured: true
spotlight: true
impact: Millions of examples · AUC 0.52 → 0.83 · 150ms serving
---

<div class="case-study" markdown="1">
<p class="case-study__lede">At TikTok, I build teacher-student learning systems that distill millions of multimodal behavioral examples into fast, personalized e-commerce intent predictions.</p>

<div class="case-study__facts">
  <div><span>Role</span><strong>Machine Learning Engineer Intern</strong></div>
  <div><span>Focus</span><strong>Personalization · distillation · ranking</strong></div>
  <div><span>Scale</span><strong>Millions of examples · 40K labels/day</strong></div>
</div>

## Production learning pipeline

I built an end-to-end teacher-student distillation pipeline spanning millions of multimodal training examples, offline labeling, streaming data infrastructure, and student models optimized for **150ms online serving**. Daily Spark, SQL, and LLM DAGs generate **40K reasoning-annotated labels per day** with **85% human alignment**.

## Modeling

I architected a sparse-ID model combining SENet, DCN, LHUC personalized gating, and DIN sequence attention across more than 150 sparse, dense, and sequential features. I also trained a 0.6B-parameter embedding-native Qwen3 decoder with feature encoders, Perceiver cross-attention, latent reasoning, and RL post-training, improving **AUC from 0.52 to 0.83** and reaching **79% accuracy**.
</div>
