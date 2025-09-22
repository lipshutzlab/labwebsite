---
layout: page
title: Team
permalink: /team
order: 2
---

### Current Team Members

#### PI
{% for member in site.data.members %}
  {% if member.role == "pi" %}
    {% include member.html %}
  {% endif %}
{% endfor %}

#### Postdocs
{% for member in site.data.members %}
  {% if member.role == "postdoc" %}
    {% include member.html %}
  {% endif %}
{% endfor %}

#### Graduate Students
{% for member in site.data.members %}
  {% if member.role == "grad" %}
    {% include member.html %}
  {% endif %}
{% endfor %}

#### Undergraduate Research Assistants
{% for member in site.data.members %}
  {% if member.role == "undergrad" %}
    {% include member.html %}
  {% endif %}
{% endfor %}

### Alumni

{% for member in site.data.members %}
  {% if member.role == "alum" %}
    {% include alum.html %}
  {% endif %}
{% endfor %}
