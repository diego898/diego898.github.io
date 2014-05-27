---
layout: page
title: Interesting Articles
---

## Interesting Articles
The following are interesting articles I've come across with some brief commentary.

{% for post in site.posts %}
  {% for tag in post.tags %}
    {% if tag == 'ia' %}
      * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
    {% endif %}
  {% endfor %}
{% endfor %}