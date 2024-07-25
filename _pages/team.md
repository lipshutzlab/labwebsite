---
layout: page
title: Team
permalink: /team
order: 2
---

<br>

{% for member in site.data.members %}
    {% include member.html %}
{% endfor %}