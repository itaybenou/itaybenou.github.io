---
layout: default
title: Home
---

# Welcome to My Academic Portfolio

{% raw %}
{% for post in site.posts %}
## {{ post.title }}

{{ post.excerpt }}

[Read more]({{ post.url }})
{% endfor %}
{% endraw %}
