---
title: Advertising for Indies
description: sell ads in project documentation and websites
permalink: /ads/indies
layout: default
---

# {{page.title}}

Advertising is a business model for developer of open source software.  There are just two steps:

1. Create and release your open source software as usual.

2. Sell advertisements in your `README`, documentation, project websites, and other Web presences.

Advertisements may be traditional ads or ads that a specific company or individual sponsors the project.

## Pros

Paid ads typically provide recurring revenue.

Does not change anything about how you develop, license, or release.

## Cons

Competitive, niche market.

May irk some users, especially those with strong privacy concerns.

## Service Providers

<ul class="services">
{% for service in site.services %}
{% if service.business_models contains "ads" %}
<li>{% include service.html %}</li>
{% endif %}
{% endfor %}
</ul>

<!-- TODO: Other Resources for Paid Development -->
