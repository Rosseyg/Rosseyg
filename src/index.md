---
title: Ross Giovanniello
layout: base.njk
---



Homepage for rosseyg on the internet

{% for page in collections.pages %}
- <a href="{{ page.url }}" class="btn btn-secondary btn-outline my-1">{{ page.data.title }}</a>
{%- endfor %}

Music - Code - Design
