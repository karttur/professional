---
layout: resume
title: Course Evaluations
excerpt: "Various course evaluations from KTH and UU"
search_omit: true
share: true
---

Various course evaluations from KTH and UU.

<ul class="post-list">
{% for post in site.categories.courseevaluation %}
    {% include publication.html post=post %}
{% endfor %}
</ul>
