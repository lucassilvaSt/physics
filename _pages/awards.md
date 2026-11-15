---
layout: single
title: "Honors and Awards"
permalink: /awards/
author_profile: true
classes: wide
---

{%- comment -%}
  You don't need to edit this page. Add awards in _data/awards.yml.
  Awards are grouped by their "category" and listed in the order you write them.
{%- endcomment -%}

{% assign groups = site.data.awards | group_by: "category" %}
{% for group in groups %}
{% if group.name != "" %}<h2>{{ group.name }}</h2>{% endif %}
<ul class="awards">
  {% for a in group.items %}
  <li>
    <span>
      {% if a.url %}{% assign first = a.url | slice: 0 %}<a href="{% if first == "/" %}{{ a.url | relative_url }}{% else %}{{ a.url }}{% endif %}">{{ a.title }}</a>{% else %}{{ a.title }}{% endif %}{% if a.result %}, {{ a.result }}{% endif %}
      {% if a.note %}<br><span class="note">{{ a.note }}</span>{% endif %}
    </span>
    <span class="yr">{{ a.year }}</span>
  </li>
  {% endfor %}
</ul>
{% endfor %}
