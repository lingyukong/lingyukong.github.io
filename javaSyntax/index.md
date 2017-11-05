---
layout: archive
title: "Latest Posts"
---

<div class="tiles">
{% for post in site.categories.javaSyntax %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
