---
layout: page
title: Schedule
permalink: /schedule/
---

<ul>
  {% for day in site.days %}
    <h3>
      <a href="{{ site.url }}{{ site.baseurl }}{{ day.url }}">{{ day.title }}</a>
    </h3>
  {% endfor %}
</ul>

