---
layout: shop
title: "Loxima Shop"
date: 2014-05-30T11:39:03-04:00
modified:
excerpt: "Buy beacons and accessories"
tags: []
image:
  feature: phone-w.jpg
  teaser:
---

<div class="tiles">
{% for post in site.categories.shop %}
  {% include shop-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
