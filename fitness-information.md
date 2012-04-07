---
layout: page
title: "Fitness Information"
description: ""
group: navigation
---
{% include JB/setup %}

## Recommended Articles

I find these items to be very useful, and I think you will to. 

* [Article1](#)
* [Article2](#)
* [Article3](#)

## Posts that I've written

### From my blog...
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>