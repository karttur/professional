---
layout: resume
title: Certificates
excerpt: "Certificates of educations, rewards and jobs etc"
search_omit: true
share: true
---

### Certificates

<ul class="post-list">
{% for post in site.categories.report %}
  {% if post.projectid == "certificate" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>
