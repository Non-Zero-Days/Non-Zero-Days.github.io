---
layout: default
title: Home
nav_order: 1
permalink: /
---

# Non-Zero Days

## Posts

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})

*Posted {{ post.date | date: '%B %d, %Y' }}*

{{ post.excerpt }} **[Read More]({{ post.url }})**

{% endfor %}
