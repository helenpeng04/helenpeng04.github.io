---
layout: page
title: Projects
---

Here you will find my recent projects once I figure out how to do this in github pages lol

## My Projects

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px;">

{% for project in site.projects %}
  <div style="border: 1px solid #ddd; border-radius: 8px; text-align: center; padding: 10px;">
    <a href="{{ project.url }}">
      <img src="{{ project.image }}" alt="{{ project.title }}" style="width: 100%; height: 200px; object-fit: cover;">
      <h3>{{ project.title }}</h3>
    </a>
  </div>
{% endfor %}

</div>
