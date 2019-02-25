---
title: Indie Showcase
description: indie developers and small companies
layout: default
---

<ul class="indies">
{% for indie in site.indies %}
<li>{% include indie.html %}</li>
{% endfor %}
</ul>
