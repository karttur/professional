---
layout: resume
title: Supplements
excerpt: "An arhcive of supplements."
search_omit: true
share: true

---

Under supplements I have collected bits and pieces that really do not fit under the other headings.


<ul class="post-list">
{% for post in site.categories.supplement %}
  {% include publication.html post=post %}
{% endfor %}
</ul>
