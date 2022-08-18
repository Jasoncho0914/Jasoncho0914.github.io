<!-- ---
layout: page
title: Projects
permalink: /projects/
nav: true
nav_order: 2
horizontal: true
---

<!-- pages/projects.md -->
<div class="projects">

<!-- Display projects without categories -->
{%- assign sorted_projects = site.projects | sort: "importance" -%}
<!-- Generate cards for each project -->
{% if page.horizontal -%}
<div class="container">
  <div class="row row-cols-1">
  {%- for project in sorted_projects -%}
    {% include projects_horizontal.html %}
  {%- endfor %}
  </div>
</div>
{%- else -%}
<div class="grid">
  {%- for project in sorted_projects -%}
    {% include projects.html %}
  {%- endfor %}
</div>
{%- endif -%}
</div> -->
