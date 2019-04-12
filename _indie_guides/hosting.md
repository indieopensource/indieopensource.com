---
title: Paid Hosting for Indies
description:
permalink: /hosting/indies
layout: default
---

# {{page.title}}

Hosting is a proven business model for developers of open source web applications and other network services.  There are just two steps:

1. Create and release your open source software as usual.

2. Offer contracts under which you host the software for paying customers.

Hosting has worked for companies large and small, young and old.  [Automattic](https://automattic.com), company home of [WordPress](https://wordpress.org), epitomizes this model.

## Pros

Typical hosting contracts provide recurring revenue.

Adaptable for low-dollar, high-volume and high-dollar, low-volume target markets.

## Cons

Creates a disincentive to automate and document deployment and hosting of the open source project.

Others can freely compete with you by hosting the same open source software.

Time spent hosting, or creating tools to do so, takes time away from project development.

<ul class="forms">
{% for form in site.forms %}
{% if form.business_models contains "hosting" %}
<li><a href="{{form.url}}">{{form.title}}</a></li>
{% endif %}
{% endfor %}
</ul>

[Slipstream](/forms/slipstream)

<!-- TODO: Other Resources for hosting -->
