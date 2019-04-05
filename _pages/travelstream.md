---
layout: archive
title: "Travel Stream"
permalink: /travelstream/
author_profile: true
---
# Publications
---
## 2018
### Predicting the metabolic capabilities of S. elongatus 7942 adapted to different light regimes.
### Metabolic Engineering 2018 Nov 13;52:42-56. doi: 10.1016/j.ymben.2018.11.001.

T Broddrick, **DG Welkie**, D Jallet, SS Golden, G Peers, BO Palsson
In this study we presented an in silico methodology for accurately characterizing photoautotrophic metabolism. These experimentally accessible constraints enable phototrophic genome-scale engineering equivalent to classical heterotrophic in silico design. Additionally, by incorporating photophysiology constraints with engineering design, we assess an existing photomixotrophic engineering strategy of an existing 23BD production strain and provide insight for improvement. Coupling genome-scale modeling-driven in silico design with experimental validation, to include 13C metabolic flux analysis, is a promising strategy to accelerate the iterative bioprocess design of light-driven metabolic engineering strategies.
##### Link to article: [Pubmed](https://www.ncbi.nlm.nih.gov/pubmed/30439494), [DOI](https://doi.org/10.1016/j.ymben.2018.11.001)

---
{% assign custom_category = 'Travel' %}
{% for post in site.posts limit: 5 %}
  {% if post.category == custom_category %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
