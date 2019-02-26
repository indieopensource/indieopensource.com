---
title: Forms
description: list of forms
layout: default
---

# {{page.title}}

{{site.title}} curates a list of legal forms that you can use as starting points for your business.

{% for form in site.forms %}
- [{{form.title}}]({{form.url}})
{% endfor %}

Unlike typical legal forms, {{site.title}} forms strive to cover all the necessary legal and business details in everyday language that everyone can understand.  {{site.title}} forms are also developed in the open, so everyone's free to contribute improvements.
