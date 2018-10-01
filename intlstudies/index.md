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

<ul class="post-list">
  {% for post in site.categories.intlstudies %}

    <li><article>

    {{ post.title }}

    (<span style="font-weight: bold;"><time datetime="{{ post.date | date_to_xmlschema }}">
    {{ post.date | date: "%Y" }}</time> - <time datetime="{{ post.enddate | date_to_xmlschema }}">{{ post.enddate | date: "%Y" }}</time></span>).

    {% if post.summary %}
      <span style="font-size: 80%; display: block;">{{ post.summary | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}
      </span>
    {% endif %}

    </article></li>
  {% endfor %}
</ul>
