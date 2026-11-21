---
layout: default
title: Projects
permalink: /projects/
---

# Projects

## What we build

- **iPhone and iPad apps.** Simple, private tools that work offline.
- **Android apps.** The same care, for Android phones and tablets.
- **Mac and Windows software.** Pay once, no subscription.
- **Games.** Calm, polished games with realistic physics.
- **Web apps.** Quick tools that run in your browser and keep your data on your device.

## Current projects

{% if site.data.projects and site.data.projects.size > 0 %}
<ul class="projects">
{% for project in site.data.projects %}
  <li>
    <h3>{{ project.name }}</h3>
    <p>{{ project.description }}</p>
    <p><a href="{{ project.url }}">View →</a></p>
  </li>
{% endfor %}
</ul>
{% else %}
Our first projects are in development. They will be listed here as they launch.
{% endif %}
