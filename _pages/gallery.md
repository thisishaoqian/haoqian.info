---
layout: archive
title: "Gallery"
permalink: /gallery/
author_profile: true
---

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for gallery in site.gallery reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
