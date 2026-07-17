---
layout: archive
title: "Articles"
permalink: /articles/
author_profile: true
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% if post.type == "article" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
