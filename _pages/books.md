---
layout: archive
title: "Books"
permalink: /books/
author_profile: true
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% if post.type == "book" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
