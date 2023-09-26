---
layout: archive
title: "Working Papers"
permalink: /projects/
author_profile: true
---
<br/>

Comleted Working Papers

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
