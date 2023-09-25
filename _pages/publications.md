---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

“Comparing the Conditional Logit Estimates and True Parameters under Preference Heterogeneity: A Simulated Discrete Choice Experiment,” Econometrics, (2023), 11(1), 4; https://doi.org/10.3390/econometrics11010004  (with Maksat Jumamyradov, Benjamin Craig, William Greene)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
