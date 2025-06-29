---
layout: page
title: Team
permalink: /team
order: 2
---

In chronological order:

<br>

{% for member in site.data.members %}
    {% include member.html %}
{% endfor %}