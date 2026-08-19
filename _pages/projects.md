---
layout: page
permalink: /projects/
title: Selected work
description: Research and products spanning agentic systems, reinforcement learning, natural language processing, and human-centered machine learning.
nav: true
nav_order: 3
---

<div class="project-page-intro">
  <p>I build machine learning systems across production, research, and product environments. The work here ranges from large-scale personalization and model distillation to agentic systems, reinforcement learning, and human-centered AI.</p>
</div>

<div class="project-grid project-grid--archive">
  {% assign sorted_projects = site.projects | sort: 'importance' %}
  {% for project in sorted_projects %}{% include projects.liquid heading_level='h2' %}{% endfor %}
</div>
