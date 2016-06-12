---
layout: page
show_meta: false
title: "Anime"
subheadline: "Blog entries about Anime!"
header: no
permalink: "/anime/"
---
<ul>
    {% for post in site.categories.Anime %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
