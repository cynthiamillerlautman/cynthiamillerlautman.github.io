---
layout: page
title: Resources
permalink: /resources/
description: Tools and tips for OT and sensory integration
masonry: true

---
<div class="grid" data-masonry='{ "itemSelector": ".grid-item", "columnWidth": 330 }'>
{% for post in site.categories.resources %}
<div class="card category-card mb-1 grid-item">
<img class="card-img-top" src="{{post.featured_image}}" />
<div class="card-body">
<h4 class="card-title"><a href="{{post.url}}">{{post.title}}</a></h4>
</div>
</div>
{% endfor %}
</div>
