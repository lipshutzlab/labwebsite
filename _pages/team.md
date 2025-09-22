---
layout: page
title: Team
permalink: /team
order: 2
---

### Current Team Members (in chronological order):

{% for member in site.data.members %}
  {% unless member.role == "alum" %}
    {% include member.html %}
  {% endunless %}
{% endfor %}

### Alumni:

{% for member in site.data.members %}
  {% if member.role == "alum" %}
    {% include member.html %}
  {% endif %}
{% endfor %}
