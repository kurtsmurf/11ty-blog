---
title: Hello World
layout: "base.html"
---

How the hell are you?

{% for post in collections.posts %}

- [{{ post.data.title }}]({{ post.url }})

{% endfor %}
