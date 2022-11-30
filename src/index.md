---
title: Hello World
layout: "base.html"
---

Hey there world, how are you?

{% for post in collections.posts %}

- [{{ post.data.title }}]({{ post.url }})

{% endfor %}
