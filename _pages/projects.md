---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

{% assign sorted_projects = site.data.projects | sort: "date" | reverse %}

{% for post in sorted_projects %}
  {% assign post = post %}
  {% include project.html %}
{% endfor %}