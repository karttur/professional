---
layout: resume
title: Land health and climate change in Africa
excerpt: "Land Health Surveillance for Targeting Climate Change and Ecosystem Management Interventions in Africa"
search_omit: true
share: true

---

Land Health Surveillance for Targeting Climate Change and Ecosystem Management Interventions in Africa with Emphasis on Pilot One UN Countries: Mozambique, Tanzania and Rwanda.

Small Scale Funding Agreement between UNEP and ICRAF.


### Technical reports

<ul class="post-list">
{% for post in site.categories.poster %}
  {% if post.projectid == "UNEP_pilot_cc" %}
    {% include publication.html post=post %}
  {% endif %}
{% endfor %}  
</ul>
