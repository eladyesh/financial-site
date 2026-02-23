---
layout: default
title: בית
---

## פוסטים אחרונים

<ul class="post-list">
{% for post in site.posts %}
  <li>
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    <span class="date">
      {{ post.date | date: "%A, %d %B %Y | %H:%M" }}
    </span>
  </li>
{% endfor %}
</ul>
