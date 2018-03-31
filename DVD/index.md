---
layout: resume
title: DVD publications
excerpt: "Archive of DVD publications"
search_omit: true
share: true

---

<ul class="post-list">
  {% for post in site.categories.DVD %}
    {% include publication.html post=post %}
  {% endfor %}
</ul>
