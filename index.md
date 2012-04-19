---
layout: page
title: Bay bay posterous
tagline: Kaçtım kurtuldum
---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts[0..10] %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.url }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.


