---
layout: page
permalink: /projects/
title: Projects
nav: true
nav_order: 3
description: Selected research projects by Zhuoqiang Cai.
---

<div class="page-intro">
  <p>Selected research on conversational digital humans, high-fidelity 3D avatars, and long-horizon intelligent agents.</p>
</div>

<div class="projects">
  <div class="row row-cols-1">
    {% assign sorted_projects = site.projects | sort: "importance" %}
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
  </div>
</div>
