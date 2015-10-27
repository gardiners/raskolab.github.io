---
layout: page
title: Rasko lab
---
![Testimage1]({{ BASE_PATH }}/images/test.gif)

## Recent updates 

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
