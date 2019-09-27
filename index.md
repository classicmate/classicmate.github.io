---
layout: archive
permalink: /
title: "Welcome to Classic Mate"
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
