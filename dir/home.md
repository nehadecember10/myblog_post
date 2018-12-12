---
layout: "page"
title: "Home"
---

<h4>Posts List</h4>
<p>{{ site.url }}</p>
{% for post in site.posts %}
  <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}