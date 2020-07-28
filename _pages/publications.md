---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Book Chapter
======

[Parallel Optimization Techniques for Machine Learning](https://link.springer.com/chapter/10.1007/978-3-030-43736-7_13)". Springer. 2020