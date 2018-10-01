---
layout: resume
title: International PhD studies
excerpt: "International study periods during my PhD"
search_omit: true
share: true
---

International study periods during my PhD.

<ul class="post-list">
{% for post in site.categories.intlstudies %}
    {% include titlelist.html post=post %}
{% endfor %}
</ul>
