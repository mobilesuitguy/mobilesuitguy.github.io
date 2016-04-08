---
layout: page
show_meta: false
title: "Conventions"
subheadline: "Tales from my convention travels!"
header: no
permalink: "/conventions/"
---
<ul>
    {% for post in site.categories.Conventions %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
