---
layout: splash
title: ""
permalink: /
read_time: false
comments: false
share: false
classes: wide
author_profile: false
header:
  image: /assets/images/ocean-header1.jpg

---
## Bio:
As post-doctoral researcher at the Center for Circadian Biology at the University of California in San Diego, I focus on improving our understanding of bacterial metabolism using molecular biology techniques and genome-scale modeling to better enable engineering efforts. I received my PhD from Biological Sciences Department at Purdue University. 

Beyond research, I enjoy running half marathons and going to major league baseball games whenever I can.

**Recent news:** 
{: .notice--info}

<div class="grid__wrapper">
  {% for post in site.posts limit:10 %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
