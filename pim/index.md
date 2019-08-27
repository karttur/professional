---
layout: resume
title: IMPACT
excerpt: "International Model for Policy Analysis of Agricultural Commodities and Trade"
search_omit: true
share: true

---

The project International Model for Policy Analysis of Agricultural Commodities and Trade (IMPACT), was part of the CGIAR research programme on Policies, Institutions and Markets (PIM). Within the program/project I developed a methods for estimating crop biomass/yields from remote sensing data. I participated as a consultant hired by ICRAF.

As part of the project I developed a stand alone python package for estimating crop and vegetation biomass from any multi--spectral image source.


### Journal articles

<ul class="post-list">
{% for post in site.categories.journal %}
  {% if post.projectid == "pim" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}  
</ul>

### Posters

<ul class="post-list">
{% for post in site.categories.poster %}
  {% if post.projectid == "pim" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}  
</ul>
