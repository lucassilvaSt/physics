---
title: "Projects"
layout: single
permalink: /projects/
author_profile: true
classes: wide
---

{%- comment -%}
  You don't need to edit this page. Each project is its own file in the _projects/ folder.
  Projects are listed by their "order" number (1 first).
{%- endcomment -%}

{% assign projects = site.projects | sort: "order", "last" %}
<div class="projects-list">
{% for project in projects %}
  {% include project-card.html project=project %}
{% endfor %}
</div>
