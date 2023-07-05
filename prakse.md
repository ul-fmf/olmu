---
layout: page
title: Prakse
---

# Prakse

Na Oddelku za matematiko sodelujemo s podjetji tudi preko praks. Spodaj jih je nekaj:

{% for kandidat in site.categories %}
  {% if kandidat[0] == "praksa" %}
    {% for dejanski in kandidat[1] %}
- [{{ dejanski.title}}]({{ site.baseurl }}{{ dejanski.url }})
    {% endfor %}
  {% endif %}
{% endfor %}
