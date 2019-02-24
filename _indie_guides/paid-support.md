---
title: Paid Support for Indies
description:
permalink: /paid-support/indies
layout: default
---

# {{page.title}}

Paid support is a proven business model for developers of open source software.  There are two basic steps:

1.  Develop and release your open source project as you usually would.

2.  Advertise your availability to provide paid technical support for the project in its documentation and Web presence.

3.  Sign support contracts with paying customers.

Paid support has worked for companies large and small, young and old, especially in combination with other models, like [paid development](/paid-development/indies) and [public-private licensing](/public-private/indies).  [RedHat](https://redhat.com) took paid support to new heights, epitomizing (and outlasting) the first cohort of "open source IPOs".  But many individual developers do well by selling support, too.

## Pros

You can make your open source software available under any open source license.

Support contracts typically provide recurring revenue, rather than one-time payments.

## Cons

Answering support requests takes time from software development.

Selling support creates a disincentive to improve documentation.

Others can compete with you by providing support for your project.

## Form

{{site.title}} publishes a [form support contract](/forms/support).

## Service Providers

{% for service in site.services %}
{% if service.business_models contains "paid-support" %}
- [{{service.title}}]({{service.url}})
{% endif %}
{% endfor %}

<!-- TODO: Other Resources for paid support -->
