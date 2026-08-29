---
layout: page
permalink: /projects/
title: Projects
nav: true
nav_order: 3
description: Research and independent engineering projects by Zhuoqiang Cai.
---

<div class="page-intro">
  <p>Selected work spanning multimodal generative research and independent desktop engineering, with an emphasis on clear problem formulation, local-first design, and verifiable implementation.</p>
</div>

<div class="projects">
  <div class="row row-cols-1">
    {% assign sorted_projects = site.projects | sort: "importance" %}
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
  </div>
</div>
