---
layout: page
permalink: /projects/
title: Projects
nav: true
nav_order: 3
description: Open-source software projects by Zhuoqiang Cai.
---

<div class="page-intro">
  <p>Independent software built through vibe coding, with an emphasis on thoughtful desktop experiences, local-first design, and robust engineering.</p>
</div>

<div class="projects">
  <div class="row row-cols-1">
    {% assign sorted_projects = site.projects | sort: "importance" %}
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
  </div>
</div>
