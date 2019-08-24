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
## About:
I'm a post-doctoral researcher at the Center for Circadian Biology at the University of California in San Diego.

**Recent news:**
{: .notice--info}
Click here to [go see all news items](/Blog/){: .btn .btn--primary}
<div class="grid__wrapper">
  {% for post in site.posts limit:8 %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
