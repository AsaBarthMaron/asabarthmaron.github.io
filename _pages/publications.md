---
layout: archive
title: "Press"
permalink: /publications/
author_profile: true
---
https://www.simonsfoundation.org/2021/02/25/the-connected-connectome/


Publications
======

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
