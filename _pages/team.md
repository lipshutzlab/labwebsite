---
layout: page
title: Team
permalink: /team
order: 2
---

<br>

<h3>Principal Investigator</h3>

{% for member in site.data.members %}
  {% if member.role == "pi" %}
    {% include member.html %}
  {% endif %}
{% endfor %}

<h3>Postdocs</h3>

{% for member in site.data.members %}
  {% if member.role == "postdoc" %}
    {% include member.html %}
  {% endif %}
{% endfor %}

<h3>Graduate Students</h3>

{% for member in site.data.members %}
  {% if member.role == "grad" %}
    {% include member.html %}
  {% endif %}
{% endfor %}

<h3>Undergraduate Research Assistants</h3>

{% for member in site.data.members %}
  {% if member.role == "undergrad" %}
    {% include member.html %}
  {% endif %}
{% endfor %}

<h3>Alumni</h3>

{% for member in site.data.members %}
  {% if member.role == "alum" %}
    {% include alum.html %}
  {% endif %}
{% endfor %}
