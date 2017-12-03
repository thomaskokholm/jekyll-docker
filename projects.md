---
layout: page
title: Projects
permalink: /projects/
---

Here goes projects.


{% for project in site._projects.data %}
  <p>{{ include.project.name }}</p>
{% endfor %}