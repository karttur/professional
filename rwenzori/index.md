---
layout: resume
title: Rwenzori
excerpt: "An archive of Rwenzori publications"
search_omit: true
share: true
---

In June 2006 I took part in the 100 year anniversary of the first climb to the summit of Mount Rwenzori (The Mountains of the Moon) straddling the border between Uganda and the Democratic Republic of Congo (DRC).

### Presentations

<ul class="post-list">
{% for post in site.categories.talk %}
  {% if post.projectid == "rwenzori" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Posters

<ul class="post-list">
{% for post in site.categories.poster %}
  {% if post.projectid == "rwenzori" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Movie

<ul class="post-list">
{% for post in site.categories.movie %}
  {% if post.projectid == "rwenzori" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Images

<ul class="post-list">
{% for post in site.categories.images %}
  {% if post.projectid == "rwenzori" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Training material

<ul class="post-list">
{% for post in site.categories.assignment %}
  {% if post.projectid == "rwenzori" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

### Climb report

<ul class="post-list">
{% for post in site.categories.report %}
  {% if post.projectid == "rwenzori" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>
