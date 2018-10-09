---
layout: resume
title: IMPACT
excerpt: "An archive of biomass estimation for remote sensing (IMPACT) publications"
search_omit: true
share: true
---

The International Model for Policy Analysis of Agricultural Commodities and Trade (IMPACT) is part of the Consultative Group of International Agricultural Research (CGIAR) Centers Research Program (CRP) on Policies, Institutions and Markets (PIM). I participated in IMPACT by developing methods and training for for estimating biomass from optical remote sensing.

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Journal articles</h1>

<ul class="post-list">
{% for post in site.categories.journal %}
  {% if post.projectid == "impact" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}  
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Posters</h1>

<ul class="post-list">
{% for post in site.categories.poster %}
  {% if post.projectid == "impact" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}  
</ul>
