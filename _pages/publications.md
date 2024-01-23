---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My area of research encompasses mathematical quantum field theory, microlocal analysis and stochastic partial differential equations. I study how these topics talk to each other at the interface of analysis, probability and algebra.

# Papers
* **On the stochastic Sine-Gordon model: an interacting field theory approach**
  prova prova

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
