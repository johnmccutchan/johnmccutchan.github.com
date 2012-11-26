---
layout: page
title: johnmccutchan.com
tagline: John McCutchan
---
{% include JB/setup %}

# Dart libraries:


* [vector_math](http://github.com/johnmccutchan/DartVectorMath)
* [simple_audio](http://github.com/johnmccutchan/simple_audio)
* [spectre](http://github.com/johnmccutchan/spectre)
* [javelin](http://github.com/johnmccutchan/javelin)
* [markerprof](http://github.com/johnmccutchan/markerprof)


# C++ libraries:


* [pal](http://github.com/johnmccutchan/pal)
* [optics](http://github.com/johnmccutchan/optics)
* [em](http://github.com/johnmccutchan/em)


# Native Client:


* [NaCl Acceleration Modules](http://github.com/johnmccutchan/NaClAMBase)

# Blogs:


* [johnmccutchan.com](http://www.johnmccutchan.com)
* [dartgamedevs.org](http://www.dartgamedevs.org)

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
