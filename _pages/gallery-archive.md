---
layout: archive
title: "Gallery"
permalink: /gallery/
author_profile: true
entries_layout: grid
collection: gallery
classes: wide
---

{% for post in site.gallery reversed %}
  {% include archive-single.html %}
{% endfor %}
