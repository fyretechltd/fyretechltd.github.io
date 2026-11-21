---
layout: default
title: Projects
permalink: /projects/
---

# Projects

{% if site.data.projects and site.data.projects.size > 0 %}
<ul class="projects">
{% for project in site.data.projects %}
  <li>
    <h2>{{ project.name }}</h2>
    <p>{{ project.description }}</p>
    <p><a href="{{ project.url }}">View →</a></p>
  </li>
{% endfor %}
</ul>
{% else %}
Our first projects are in development. They will be listed here as they launch.
{% endif %}
