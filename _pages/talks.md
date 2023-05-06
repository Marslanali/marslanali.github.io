---
layout: archive
title: "Recent Projects"
permalink: /talks/
author_profile: true
classes: wide
---

{% for post in site.talks reversed %}
  {% include archive-single.html %}
{% endfor %}
