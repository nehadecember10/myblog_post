---
layout: "page"
title: "Home"
---
<h4>Posts List</h4>
{% for post in site.posts %}
  <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}