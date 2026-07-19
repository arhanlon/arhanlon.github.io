---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

I'm currently teaching the following courses:

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
