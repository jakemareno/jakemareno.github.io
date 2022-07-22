---
layout: default
title: Projects
permalink: /projects/
category: project
---
# Projects

<ul>
  {% for post in site.categories.projects %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    </li>
  {% endfor %}
</ul>