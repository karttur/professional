---
layout: resume
title: ICRAF Geoinformatics.
excerpt: "An archive of ICRAF geoinforamtics unit"
search_omit: true
share: true

---
In 2010 I started the process of creating and launching the ICRAF Geoinformatics unit. The unit was launched in 2011, and I led the establishment of the unit, hired staff and created of the first web-map portal. For family reason I left ICRAF (and moved from Africa to my native Sweden) in early 2012.

### Presentations

<ul class="post-list">
{% for post in site.categories.talk %}
  {% if post.projectid == "icrafgeoinfo" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>
