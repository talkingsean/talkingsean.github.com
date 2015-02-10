---
layout: page
title: 故事讲讲
tagline: "What makes an interesting story?"
published: true
---

{% include JB/setup %}
  
## 贴子

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>