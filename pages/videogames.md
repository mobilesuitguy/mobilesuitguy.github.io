---
layout: page
show_meta: false
title: "Video Games"
subheadline: "Blog entries about Video Games!"
header: no
permalink: "/videogames/"
---
<ul>
    {% for post in site.categories.['Video Games'] %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
