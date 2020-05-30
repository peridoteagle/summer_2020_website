---
layout: archive
title: "The Outdoor Programmer"
date: 2014-05-30T11:39:03-04:00
modified:
excerpt: "Chronicles of Programming + Nature."
tags: []
image:
  feature:
  teaser:
---

<div class="tiles">
{% for post in site.categories.outdoor-programmer %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
