---
title: Hello World
layout: "base.njk"
---

Hey there world, how are ya?

{% for post in collections.posts %}

- [{{ post.data.title }}]({{ post.url }})

{% endfor %}
