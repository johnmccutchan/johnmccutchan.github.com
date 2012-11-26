---
layout: page
title: johnmccutchan.com
tagline: John McCutchan
---
{% include JB/setup %}

For now: [johnmccutchan.com](http://johnmccutchan.com)

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
