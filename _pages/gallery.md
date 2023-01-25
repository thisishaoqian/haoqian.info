---
layout: archive
title: "Gallery"
permalink: /gallery/
author_profile: true
---

{% for talk in site.talks reversed %}
  {% include archive-single.html %}
{% endfor %}
