---
layout: collection
title: "Gallery"
permalink: /gallery/
entries_layout: grid
classes: wide
author_profile: true
---

{% include base_path %}

{% for gallery in site.gallery reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
