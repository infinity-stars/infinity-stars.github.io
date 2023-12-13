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

 \* denotes equal contributions.

## Preprints
* Accelerated Convergence of Stochastic Heavy Ball Method under Anisotropic Gradient Noise. \
  Rui Pan\*, **Yuxing Liu\***, Xiaoyu Wang, and Tong Zhang. [Under review](https://openreview.net/forum?id=CIqjp9yTDq)
