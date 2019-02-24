---
title: Paid Development for Indies
description:
permalink: /paid-development/indies
layout: default
---

# {{page.title}}

Paid development is a proven business model for developers of open source software.  In a nutshell, paid development means taking pay from clients to write software that you release as open source.  That can take a few different forms:

1.  Contract to write entirely new open source software.

2.  Contract to fix specific bugs in existing open source software.

3.  Contract to add specific features to existing open source software.

4.  Contract to maintain existing open source software over time.

Paid open source development has worked for many independent software developers.

## Pros

Release software under any open source license, with client agreement.

Does not compete for time with open source development.

Depending on contract structure, can produce recurring revenue.

## Cons

With rare exception, developer can only charge one client, one time, for software created.

## Form

[Switchmode](/forms/switchmode)

## Service Providers

{% for service in site.services %}
{% if service.business_models contains "paid-development" %}
- [{{service.title}}]({{service.url}})
{% endif %}
{% endfor %}

<!-- TODO: Other Resources for Paid Development -->
