---
layout: publication
title: Supplements
excerpt: "An arhcive of supplements."
search_omit: true
share: true

---

Under supplements I have collected bits and pieces that really do not fit under the other headings.


<ul class="post-list">
{% for post in site.categories.supplement %}
  <li><article>
  {% if post.authors %}
    <span style="font-size: 80%; display: block;">{{ post.authors | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }},
  {% if post.source %}
  {% if post.doiurl %}
    <a href="{{ post.doiurl }}">
    {{ post.source }}
    </a>
   {% else %}
   {{ post.source }}
   {% endif %}
  {% endif %}
  (<span style="font-weight: bold;"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%Y" }}</time></span>).
  </span>
  {% endif %}
  <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
  </article></li>
  {% endfor %}
</ul>
