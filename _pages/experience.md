---
layout: archive
title: "Experience"
permalink: /experience/
author_profile: true
---

{% include base_path %}

{% assign sorted_experience = site.experience | sort: 'start_date' | reverse %}
{% for post in sorted_experience %}
  {% include archive-single.html %}
{% endfor %}
