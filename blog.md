---
title: Blog
permalink: "/blog/"
layout: page
---

This is something new which is coming soon.

<div class="content">
<ul>
{% for posts in site.posts %}
<li>{{ post.title }} - {{ post.categories }}</li>
{% endfor %}

</ul>
</div>