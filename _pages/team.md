---
layout: page
title: Team
permalink: /team
order: 2
---

<br>

{% for member in site.data.members %}
  {% if member.role == "pi" %}
    {% include member.html %}
  {% endif %}
{% endfor %}

{% for member in site.data.members %}
  {% if member.role == "postdoc" %}
    {% include member.html %}
  {% endif %}
{% endfor %}

{% for member in site.data.members %}
  {% if member.role == "grad" %}
    {% include member.html %}
  {% endif %}
{% endfor %}

{% for member in site.data.members %}
  {% if member.role == "undergrad" %}
    {% include member.html %}
  {% endif %}
{% endfor %}

{% for member in site.data.members %}
  {% if member.role == "alum" %}
    {% include alum.html %}
  {% endif %}
{% endfor %}
