---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

{% for post in site.data.projects reversed %}
  {% assign post = post %}
  {% include project.html %}
{% endfor %}