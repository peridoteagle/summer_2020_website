---
layout: archive
title: "A Tent Blog"
date: 2014-05-30T11:39:03-04:00
modified:
excerpt: "A programmer's life in a tent during COVID19."
tags: []
image:
  feature:
  teaser:
---

<div class="tiles">
{% for post in site.categories.outdoor_programmer %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
