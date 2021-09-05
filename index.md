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

## Debugging

{%- assign pages_array = '' | split: '' -%}
{%- assign pages_array = pages_array | push: site.html_pages -%}
{%- for pages in pages_array -%}
  {%- for page in pages -%}
        {%- page.title -%}
    {%- endfor -%}
{%- endfor -%}
