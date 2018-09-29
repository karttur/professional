---
layout: resume
title: Student course projects
excerpt: "Various student course project reports from KTH"
search_omit: true
share: true
---

Student course project reports from KTH.

<ul class="post-list">
{% for post in site.categories.courseproject %}
    {% include publication.html post=post %}
{% endfor %}
</ul>
