---
layout: default
---

# Hey!

Turns out I can cook as well, so here are my recipes

{% for post in site.posts %}
[{{ post.title }}]({{ post.url }})
{% endfor %}
