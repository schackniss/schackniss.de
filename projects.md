---
layout: page
title: Projects
permalink: /projects/
---

{% for project in site.projects %}
  <h3>
    <a href="{{ project.url }}">
      {{ project.name }}
    </a>
  </h3>
  <p>{{ project.description | markdownify }}</p>
{% endfor %}
