---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

Email: ak3851a [at] american.edu

Recent News 



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
