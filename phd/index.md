---
layout: publication
title: "Modelling water and vegetation reciprocity."
excerpt: "An archive of studies forming my PhD thesis."
search_omit: true
share: true
---

My PhD project "Modelling water and vegetation reciprocity -a landscape synthesis in GIS" is based on the results of several studies relating landscape patterns and processes. Some of the studies are explicitly included in the PhD thesis report, whereas others are only used as background material.

### PhD thesis

<ul class="post-list">
{% for post in site.categories.report %}
  {% if post.projectid == "phd" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Journal articles

<ul class="post-list">
{% for post in site.categories.journal %}
  {% if post.phdinclude %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}

{% for post in site.categories.journal %}
  {% if post.projectid == "phd" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Refereed chapters

<ul class="post-list">
{% for post in site.categories.refereechapter %}
  {% if post.phdinclude %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}

{% for post in site.categories.refereechapter %}
  {% if post.projectid == "phd" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Conference proceedings

<ul class="post-list">
{% for post in site.categories.conference %}
  {% if post.phdinclude %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}

{% for post in site.categories.conference %}
  {% if post.projectid == "phd" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Images

Not yet available

<ul class="post-list">
{% for post in site.categories.images %}
  {% if post.projectid == "phd" %}

  {% endif %}
{% endfor %}
</ul>
