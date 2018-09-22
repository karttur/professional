---
layout: resume
title: Certificates
excerpt: "Certificates of educations, rewards and jobs etc"
search_omit: true
share: true
---

<ul class="post-list">
{% for post in site.categories.certificate %}
    {% include publication.html post=post %}
{% endfor %}
</ul>
