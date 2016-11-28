---
layout: page
title: Blog Posts
---

You can view the sites posts chronologically, or by [tag](/tags/).

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}