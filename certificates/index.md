---
layout: resume
title: Certificates
excerpt: "Certificates of educations, awards and jobs etc"
search_omit: true
share: true
---

Certificates of educations and job positions etc.

<ul class="post-list">
{% for post in site.categories.certificate %}
    {% include publication.html post=post %}
{% endfor %}
</ul>
