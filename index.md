---
title: Posts
---

{% for post in site.posts %}
    [{{ post.title }}]({{ post }})
{% endfor %}
