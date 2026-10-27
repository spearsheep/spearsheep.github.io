---
layout: page
title: Paper2WRDS · Financial research agent
description: An evidence-grounded research agent that turns finance papers into reviewable Python/SQL notebooks, method comparisons, and study plans.
category: Industry experience
year: 2026–present
importance: 2
featured: true
spotlight: true
impact: ~19.3K finance papers · ~1.3s/page parsing · source-grounded drafts
img: /assets/img/projects/wrds-research-pipeline.svg
img_alt: Paper2WRDS pipeline from financial papers through MinerU parsing, context-aware Qdrant indexing, tool-based retrieval, source grounding, and validated research drafts with a researcher feedback loop.
img_fit: contain
img_width: 1920
img_height: 1080
img_caption: System overview of the paper-ingestion and evidence-grounded research workflows.
---

<div class="case-study" markdown="1">
<p class="case-study__lede">At Wharton Research Data Services, I build AI systems that help financial researchers move from a paper's methodology to a research draft they can inspect, refine, and build on.</p>

<div class="case-study__facts">
  <div><span>Role</span><strong>AI Engineer · Jan 2026–present</strong></div>
  <div><span>Advisor</span><strong>Dr. Rui Dai · WRDS</strong></div>
  <div><span>Stack</span><strong>LangGraph · Qdrant · MinerU · AWS</strong></div>
</div>

## From papers to a searchable evidence base

I developed the retrieval pipeline for approximately **19,300 finance papers**, combining web scraping, multi-GPU document parsing with **MinerU at about 1.3 seconds per page**, and ingestion into **Amazon S3**.

Block-aware indexing preserves the structure of the original research. Text passages, equations with surrounding context, and figure or table captions enter separate **Qdrant** collections, carrying paper identity, page, and section metadata. Retrieval can filter by source and use cross-encoder reranking to select evidence for a question.

## An agent harness for financial research

I built a **LangGraph** financial research agent that turns paper ideas into **Python/SQL notebook drafts** for stock-market analysis, replication, and study design. The harness combines tool orchestration, persistent state, and feedback-driven generation and validation.

Direct questions can follow a retrieval-and-synthesis pipeline. More involved research can use iterative planning, paper search, and targeted reading before synthesis. Researchers can then develop the retrieved passages into a code draft, method comparison, or research plan.

## Keeping the reasoning connected to the source

The research workspace retains source quotations, findings, implementation reasoning, assumptions, and unresolved details alongside the draft. Source checks match quotations and citation identifiers to the supplied evidence; Python cells also receive syntax checks. These checks support review, while numerical correctness and successful replication require independent evaluation.

Saved versions preserve the relationship between a draft and its original evidence. A researcher can ask for a revision in the conversation and continue refining the same work, rather than starting again with disconnected code and citations.

<a class="button button--quiet" href="{{ '/assets/img/projects/wrds-research-pipeline.svg' | relative_url }}" target="_blank" rel="noopener noreferrer">View the full pipeline diagram <span aria-hidden="true">↗</span></a>
<a class="button button--primary" href="https://wrds-www.wharton.upenn.edu/" target="_blank" rel="noopener noreferrer">About WRDS <span aria-hidden="true">↗</span></a>
</div>
