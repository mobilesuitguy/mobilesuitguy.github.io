---
layout: page
show_meta: false
title: "Announcements"
subheadline: "Big things to come in the future!"
header: no
permalink: "/announcements/"
---
<ul>
    {% for post in site.categories.Announcements %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
