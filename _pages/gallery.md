---
layout: collection
title: "Gallery"
permalink: /gallery/
author_profile: true
entries_layout: grid
---

{% for post in site.gallery reversed %}
  {% include archive-single.html %}
{% endfor %}
