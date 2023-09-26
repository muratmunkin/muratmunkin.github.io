---
layout: archive
title: "Working Papers"
permalink: /projects/
author_profile: true
---
<br/>

Comleted Working Papers

"A Note on Identification in the Multinomial Probit Model in the Presence of Weak Correlation"

An identification problem with the Multinomial Probit Model arises when correlations among choice alternatives are weak. Then even if formal conditions for model identification are satisfied, practical estimation of the unrestricted variance parameters is tenuous. An estimable specification of the model, in which all variance parameters are fixed, resolves the problem. This paper demonstrates the identification problem and presents an MCMC algorithm to estimate this restricted specification of the Multinomial Probit model.

[Download paper here](http://academicpages.github.io/files/MNP.pdf)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
