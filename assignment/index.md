---
layout: resume
title: Training assignments
excerpt: "Archive of training exercises"
search_omit: true
share: true
---

Training assignments that I developed. Starting from my period at Uppsala University and for a range of other shorter courses on geoinformatics that I have held for a range of different audiences and stakeholders.

<ul class="post-list">
  {% for post in site.categories.assignment %}
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

### Uppsala University

<ul class="post-list">
{% for post in site.categories.assignment %}
  {% if post.projectid == "uu" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}
</ul>
