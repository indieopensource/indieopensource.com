---
title: Delayed Release for Indies
description:
permalink: /delayed-release/indies
layout: default
---

# {{page.title}}

Delayed release is a proven business model for developers of open source software.  There are three basic steps:

1.  As you work on your project, divide your work into two categories: always-open work that you will release immediately, and delayed-release work that you will hold back, to release later.

2.  Develop and release the always-open parts of your work as normal.  Choose either a permissive or a copyleft open source license.

3.  Distribute your delayed-release work to paying customers only for a period of time.

4.  Once the delayed-release period has passed, release your delayed-release work in the open.

Delayed release of code has a long history, going back at least as far as [Ghostscript](https://ghostscript.com).  It continues today through companies like [MariaDB](https://mariadb.com), via their [Business Source License](https://mariadb.com/bsl11/).

Delayed release of other work, like security advisories, is also widespread.  [hapi.js](/indies/hapi) does this as a [Patreon](/services/patreon) perk.

## Pros

You can make your work available under a permissive open source software license, like The MIT License or The Apache License, Version 2.0.

Making your work available for free increases its changes or widespread adoption and feedback.

## Cons

Maintaining and explaining the allocation of work between always-open and delayed-release.

## Service Providers

<ul class="services">
{% for service in site.services %}
{% if service.business_models contains "delayed-release" %}
<li>{% include service.html %}</li>
{% endif %}
{% endfor %}
</ul>
