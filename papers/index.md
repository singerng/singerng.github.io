---
title: Papers
permalink: /papers
layout: default
---

Organized in reverse chronological order.

### Papers

<ul class="paper-list">
{% for paper in site.data.papers %}
{% if paper.type == "research" %}
{% include paper.html paper=paper %}
{% endif %}
{% endfor %}
</ul>

### Course Projects

<ul class="paper-list">
{% for paper in site.data.papers %}
{% if paper.type == "course_project" %}
{% include paper.html paper=paper %}
{% endif %}
{% endfor %}
</ul>

### Miscellaneous

<ul class="paper-list">
{% for paper in site.data.papers %}
{% if paper.type == "misc" %}
{% include paper.html paper=paper %}
{% endif %}
{% endfor %}
</ul>