---
layout: resume
title: Course Evaluations
excerpt: "Various course compendiums from KTH and UU"
search_omit: true
share: true
---

Both at KTH and UU I created course compendiums. While at KTH these compendiums were printed and handed out as hardcopies. When I started at UU (1998) the hardcopies were replaced by internet distributed soft-copies.

<ul class="post-list">
{% for post in site.categories.coursecompendium %}
    {% include publication.html post=post %}
{% endfor %}
</ul>
