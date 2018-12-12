---
layout: "post"
title: "Home"
---

<h4>Posts List</h4>
{% for post in site.posts %}
  <li><a href="/myblog_post/{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}