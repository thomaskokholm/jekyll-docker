---
layout: page
title: Projects
permalink: /projects/
---

Here goes projects.


{% for project in site.data.projects %}
  <p>{{ include.project.name }}</p>
{% endfor %}