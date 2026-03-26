---
layout: page
title: "Researching"
---

{% for post in site.categories.researching %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
{% endfor %}