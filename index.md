---
layout: single
author_profile: true
classes: wide
---

<!-- EDIT THIS: a few friendly sentences about you, in your own voice. -->
Hi! I'm Lucas, a senior at Stuyvesant High School. I love physics, especially quantum physics, gravity and electricity, and I like learning it by building things and running my own experiments.

<!-- EDIT THIS: one or two sentences on what you've worked on or what you want to study next. -->
This site collects my projects, from [what you built or measured] to [another project]. Next year I want to study [physics / engineering / ...].

When I'm not doing physics, you'll find me [hobbies].

## Featured projects

{% assign featured = site.projects | where: "featured", true | sort: "order", "last" %}
<div class="projects-list">
{% for project in featured %}
  {% include project-card.html project=project %}
{% endfor %}
</div>

[See all projects →]({{ '/projects/' | relative_url }})
