---
layout: resume
title: Rwenzori
excerpt: "An archive of Rwenzori publications"
search_omit: true
share: true
---

In June 2006 I took part in the 100 year anniversary of the first climb to the summit of Mount Rwenzori (The Mountains of the Moon) straddling the border between Uganda and the Democratic Republic of Congo (DRC).

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Presentations</h1>

<ul class="post-list">
{% for post in site.categories.talk %}
  {% if post.projectid == "rwenzori" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Posters</h1>

<ul class="post-list">
{% for post in site.categories.poster %}
  {% if post.projectid == "rwenzori" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Movie</h1>

<ul class="post-list">
{% for post in site.categories.movie %}
  {% if post.projectid == "rwenzori" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Images</h1>

<ul class="post-list">
{% for post in site.categories.images %}
  {% if post.projectid == "rwenzori" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>

<h1 class='foot-description'></h1>
<h1 class='foot-description'>Training</h1>

<ul class="post-list">
{% for post in site.categories.assignment %}
  {% if post.projectid == "rwenzori" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>
