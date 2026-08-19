---
layout: page
permalink: /projects/
title: Selected work
description: Research and products spanning agentic systems, reinforcement learning, natural language processing, and human-centered machine learning.
nav: true
nav_order: 3
---

<div class="project-page-intro">
  <p>I like work that closes the loop between an ambitious research question and a system that can be tested in the world. These projects range from published research to products used by real people.</p>
</div>

<div class="project-grid project-grid--archive">
  {% assign sorted_projects = site.projects | sort: 'importance' %}
  {% for project in sorted_projects %}{% include projects.liquid heading_level='h2' %}{% endfor %}
</div>
