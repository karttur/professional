---
layout: resume
title: DVD publications
excerpt: "Archive of DVD publications"
search_omit: true
share: true

---

<ul class="post-list">
  {% for post in site.categories.DVD %}
    <li><article>
    {% if post.authors %}
      <span style="font-size: 80%; display: block;">{{ post.authors | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }},
    {% if post.source %}
     {{ post.source }}
    {% endif %}
    (<span style="font-weight: bold;"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%Y" }}</time></span>).
    </span>
    {% endif %}
    <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
    </article></li>
  {% endfor %}
</ul>
