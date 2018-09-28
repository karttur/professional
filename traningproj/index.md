---
layout: resume
title: Training projects
excerpt: "Archive of lectures"
search_omit: true
share: true
---

The training projects were used as pedagogic vehicles in the courses I held both as part of the international MSc programs in Environmental Engineering and Sustainable Infrastructure (EESI) at the Royal Institute of Technology (1994 t0 1998) and then also when I was a senior lecturer at Uppsala University (1998 to 2000).

The projects below were the last generation of projects that I developed for the EESI programs at KTH.

<ul class="post-list">
  {% for post in site.categories.trainingproj %}
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
