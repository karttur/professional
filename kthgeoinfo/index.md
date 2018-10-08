---
layout: resume
title: Senior Lecturer, Geoinformatics (KTH).
excerpt: "An archive of teaching material in Geoinformatics."
search_omit: true
share: true

---
Between August 2005 and April 2009 I held a half time position with the Royal Institute of Technology (KTH) with responsibility for courses in Geographical Information Systems (GIS), spatial data visualisation and geoinformatics web server development. Lecturing and supervision at graduate and post-graduate levels.

### Lectures

#### GIS Grundkurs (In1651) - In Swedish

<ul class="post-list">
{% for post in site.categories.lecture-1n1651 %}
    {% include publication.html post=post %}
{% endfor %}  
</ul>

#### GIS i samhällsbyggnad (In1654) - In Swedish

<ul class="post-list">
{% for post in site.categories.lecture-1n1654 %}
    {% include publication.html post=post %}
{% endfor %}  
</ul>

#### visualization (ag2412) - In English

<ul class="post-list">
{% for post in site.categories.lecture-ag2412 %}
    {% include publication.html post=post %}
{% endfor %}  
</ul>
