---
title: Open Core for Indies
description:
permalink: /open-core/indies
layout: default
---

# {{page.title}}

Open core is a proven business model for developers of open source software.  There are three basic steps:

1.  Divide your project into two parts: an "open core" of core functionality and a "closed shell" of add-ons, plugins, patches, tools, and other related software.

2.  Develop and release your open core as open source software.  Choose either a permissive or a copyleft open source license.

3.  Develop your closed shell in private or as source available software under a restricted public license.

4.  Sell licenses to specific people and companies to use your closed shell.

Open core has worked for companies large and small, young and old.

## Pros

You can make your open core available under a permissive open source software license, like The MIT License or The Apache License, Version 2.0.

Making your open core available for free increases its changes or widespread adoption and feedback.

## Cons

Others can compete with your closed shell, without supporting development of your open core, by offering their own open or closed alternatives.

Maintaining and explaining the allocation of features to open core and closed shell can be difficult.

## Choices to Make

1.  [How do I decide what's open core and what's closed shell?](/open-core/allocation)

2.  [How do I license my closed shell?](/private-licenses)

## Forms

<ul class="forms">
{% for form in site.forms %}
{% if form.business_models contains "open-core" %}
<li><a href="{{form.url}}">{{form.title}}</a></li>
{% endif %}
{% endfor %}
</ul>


## Service Providers

<ul class="services">
{% for service in site.services %}
{% if service.business_models contains "open-core" %}
<li>{% include service.html %}</li>
{% endif %}
{% endfor %}
</ul>

## Other Resources

The concept of "open core" has existed for many years, under many different names.  The coining of "open core" has made it far easier to find resources about it:

- Joseph Jacks' [_Open Core --- Definition, Examples & Tradeoffs_](https://medium.com/open-consensus/e4d0c044da7c)

- Spencer Kimball's [_How We're Building a Business to Last_](https://www.cockroachlabs.com/blog/how-were-building-a-business-to-last/)
