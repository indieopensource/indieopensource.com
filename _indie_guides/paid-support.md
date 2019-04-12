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

Paid support has worked for companies large and small, young and old, especially in combination with other models, like [paid development](/paid-development/indies) and [public-private licensing](/public-private/indies).  [Cygnus](https://en.wikipedia.org/wiki/Cygnus_Solutions), later acquired by [RedHat](https://redhat.com), pioneered the model at scale.  But many individual developers do well by selling support, too.

## Pros

You can make your open source software available under any open source license.

Support contracts typically provide recurring revenue, rather than one-time payments.

## Cons

Answering support requests takes time from software development.

Selling support creates a disincentive to improve documentation.

Others can compete with you by providing support for your project.

## Forms

<ul class="forms">
{% for form in site.forms %}
{% if form.business_models contains "paid-support" %}
<li><a href="{{form.url}}">{{form.title}}</a></li>
{% endif %}
{% endfor %}
</ul>


## Service Providers

<ul class="services">
{% for service in site.services %}
{% if service.business_models contains "paid-support" %}
<li>{% include service.html %}</li>
{% endif %}
{% endfor %}
</ul>

<!-- TODO: Other Resources for paid support -->
