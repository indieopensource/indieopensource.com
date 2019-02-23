---
title: Resources for Indies
description: guides, forms, and resources
layout: default
---

# {{page.title}}

{{site.title}} maintains a variety of resources for indie open source software developers.

## Business Model Guides

{{site.title}} hosts a number of guides to popular business models for indie developers:

{% for guide in site.indie_guides %}
- [{{guide.title}}]({{guide.url}})
{% endfor %}

## Business Model Explainers

{{site.title}} hosts a number of explainer pages, to help you communicate your business model to users:

{% for guide in site.user_guides %}
- [{{guide.title}}]({{guide.url}})
{% endfor %}

## Explainers for Contributors

{{site.title}} hosts a number of explainer pages to help you communicate your business model to potential contributors to your projects:

{% for guide in site.contributor_guides %}
- [{{guide.title}}]({{guide.url}})
{% endfor %}

## Legal Forms

{{site.title}} maintains a number of legal forms to give you starting points for the legal parts of your business:

{% for form in site.forms %}
- [{{form.title}}]({{form.url}})
{% endfor  %}
