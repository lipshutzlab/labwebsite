---
layout: page
title: Team
permalink: /team
order: 2
---

{% for member in site.data.members %}
    {% include member.html %}
{% endfor %}

<h1>Collaborators</h1>

{% for collaborator in site.data.collaborators %}
    {% include member.html %}
{% endfor %}