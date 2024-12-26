---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a master student at the College of Computer Science, Nankai University, China. My research interests are reinforcement learning and computer graphics, with a focus on fluid simulation and motion control.


# Publications

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

