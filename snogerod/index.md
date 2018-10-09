---
layout: resume
title: Constructed wetland waste water treatment
excerpt: "An archive of publications on wetlands for waste water treatment"
search_omit: true
share: true
---

The project on constructed wetlands for waste water treatment originated from the consulting company K-Konsult (where I worked 1984 - 1988). I brought this project along when I started my doctoral studies at the Royal Institute of technology (KTH) in 1988. The studies on constructed wetlands formed the basis of my Technical Licentiate degree (in between an MSc and a PhD), presented in 1991.

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Journal articles</h1>

<ul class="post-list">
{% for post in site.categories.journal %}
  {% if post.projectid == "snogerod" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}  
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Book chapters</h1>

<ul class="post-list">
{% for post in site.categories.refereechapter %}
  {% if post.projectid == "snogerod" %}
    {% include publication.html %}
  {% endif %}
{% endfor %}
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Licentiate thesis</h1>

<ul class="post-list">
{% for post in site.categories.report %}
  {% if post.projectid == "snogerod" %}
    {% include publication.html %}
  {% endif %}
{% endfor %}
</ul>
