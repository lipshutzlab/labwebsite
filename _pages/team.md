---
layout: page
title: Team
permalink: /team
order: 2
---

In chronological order:

{% for member in site.data.members %}
    {% include member.html %}
{% endfor %}