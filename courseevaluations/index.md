---
layout: resume
title: Course Evaluations
excerpt: "Various course evaluations from KTH and UU"
search_omit: true
share: true
---

Various course evaluations from KTH and UU. This is not a complete list of courses that I have taught. The list is simply composed of the documents I have been able to retrieve in 2018.

<ul class="post-list">
{% for post in site.categories.courseevaluation %}
    {% include publication.html post=post %}
{% endfor %}
</ul>
