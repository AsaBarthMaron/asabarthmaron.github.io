---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

News
---
[The Connected Connectome](https://www.simonsfoundation.org/2021/02/25/the-connected-connectome/). Liam Drew, Simons Foundation (February 25, 2021). The most comprehensive wiring map to date of the fruit fly brain has transformed the field of neuroscience, identifying new cell types and reconfiguring circuit models.

Publications
======

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
