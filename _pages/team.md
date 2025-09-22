---
layout: page
title: Team
permalink: /team
order: 2
---

## Principal Investigator
<br>
{% for member in site.data.members %}
  {% if member.role == "pi" %}
    {% include member.html %}
  {% endif %}
{% endfor %}

## Postdocs
<br>
{% for member in site.data.members %}
  {% if member.role == "postdoc" %}
    {% include member.html %}
  {% endif %}
{% endfor %}

## Graduate Students
<br>
{% for member in site.data.members %}
  {% if member.role == "grad" %}
    {% include member.html %}
  {% endif %}
{% endfor %}

## Undergraduate Research Assistants
<br>
{% for member in site.data.members %}
  {% if member.role == "undergrad" %}
    {% include member.html %}
  {% endif %}
{% endfor %}

## Alumni
<br>
{% for member in site.data.members %}
  {% if member.role == "alum" %}
    {% include alum.html %}
  {% endif %}
{% endfor %}
