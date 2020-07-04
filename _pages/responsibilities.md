---
layout: archive
title: "Positions of Responsibility"
permalink: /responsibilities/
author_profile: true
---

{% include base_path %}

{% for post in site.responsibilities reversed %}
  {% include archive-single.html %}
{% endfor %}
