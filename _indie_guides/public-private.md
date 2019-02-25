---
title: Public-Private Licensing for Indies
description: a short, practical guide
permalink: /public-private/indies
layout: default
---

# {{page.title}}

Public-private licensing is an proven business model for developers of open source software.  There are just two steps:

1. Create and release your open source software as usual, but choose a copyleft license that does not allow making closed software with your work.

2. Sell license to specific people and companies to make closed software with your work.

Public-private licensing has worked for companies large and small, young and old.  [MySQL AB](https://www.mysql.com/about/legal/licensing/oem/) popularized the model.  But smaller indies like [RavenDB](https://ayende.com/blog/186147-A/making-money-from-open-source-software-how-we-do-it) and [Metafizzy](https://metafizzy.co/) do public-private licensing, too.

## Pros

You do not have to change how you build your software.

You do not have to work on other software or services to charge for.

The better you make your software, the more valuable it becomes, and the more licenses you can sell, for more money.

## Cons

Copyleft licenses can reduce adoption of your software.

You will need to take extra steps to accept contributions from others.

Selling private licenses can itself take time, depending on your software and your customers.

## Choices to Make

There are three big choices for public-private licensing:

1.  [Which public license do I choose for my project?](/public-private/public-licenses)

2.  [What private licenses do I offer?](/private-licenses)

3.  [How do I handle outside contributions?](/public-private/contributors)

## Forms

- [Paid License](/forms/license)
- [CLA](/forms/cla)

## Service Providers

<ul class="services">
{% for service in site.services %}
{% if service.business_models contains "public-private" %}
<li>{% include service.html %}</li>
{% endif %}
{% endfor %}
</ul>

## Other Resources

The public-private licensing business model is also called "dual licensing" and "selling exceptions".  Unfortunately, those terms are also used to mean other things.  But you can still find information about the business model online under those old names.

Here are a few good pieces to start with:

- Richard Stallman's [_Selling Exceptions to the GNU GPL_](https://www.gnu.org/philosophy/selling-exceptions.html)

- Vikko Välimäki's [_Dual Licensing in Open Source Software Industry_](https://web.archive.org/web/20030829144116/http://opensource.mit.edu/papers/valimaki.pdf)
