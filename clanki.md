---
layout: page
title: Interdisciplinarni članki
---

# {{ page.title }}

Nekaj zadnjih zanimivih člankov:

{% for kandidat in site.categories %}
  {% if kandidat[0] == "clanek" %}
    {% for dejanski in kandidat[1] %}
- [{{ dejanski.title}}]({{ site.baseurl }}{{ dejanski.url }})
    {% endfor %}
  {% endif %}
{% endfor %}


