---
layout: archive
title: "Publications"
permalink: /publications.md
author_profile: true
---

Reutterer, T., March, N,. Hornik, K. & Gruber, K. (2016). A Data Mining Framework for Targeted Category Promotions. <em>Journal of Business Economics</em>, 87 (3), 337-358.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
