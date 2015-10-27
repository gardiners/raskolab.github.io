---
layout: page
title: Rasko lab
tagline: Where introns must be retained
---
{% include JB/setup %}

    
## Recent updates 

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
