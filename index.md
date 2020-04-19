---
layout: default
---

# Hey!

Turns out I can cook as well, so here are my recipes

{% for post in site.posts %}
{{ post.emoji }} [{{ post.title }}]({{ post.url }})
{% endfor %}
