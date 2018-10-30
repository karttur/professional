---
layout: resume
title: International studies and assignments
excerpt: "International studies and assignments during my doctoral studies (before moving to Africa in 1999)."
search_omit: true
share: true
---

International studies and assignments during my doctoral studies (before moving to Africa in 1999)

<ul class="post-list">
  {% for post in site.categories.expedition %}
    <li><article>
    {{ post.title }}

    (<span style="font-weight: bold;"><time datetime="{{ post.date | date_to_xmlschema }}">
    {{ post.date | date: "%Y" }}</time> </span>).
    {% if post.summary %}
      <span style="font-size: 80%; display: block;">{{ post.summary | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}
      </span>
    {% endif %}

    </article></li>
  {% endfor %}
</ul>
