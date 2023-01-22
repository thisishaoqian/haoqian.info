---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


### 2020

<b>[Infnote: A Decentralized Information Sharing Platform Based on Blockchain](#)</b> <br>
<b>Haoqian Zhang</b>, Yaocheng Zhao, Abhishek Paryani, Ke Yi. <u><a href="https://arxiv.org/abs/2002.04533">PDF</a>.</u>