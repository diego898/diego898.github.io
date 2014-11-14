---
layout: page
title: Blog Posts
---

The following are posts about publications, updates, and interesting articles I've come across with some brief commentary.

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}