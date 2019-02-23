---
title: Resources for Indies
description: guides, forms, and resources
layout: default
---

# {{page.title}}

{{site.title}} maintains a variety of resources for indie open source software developers.

## Business Model Guides

{{site.title}} hosts a number of guides to popular business models for indie developers:

- [Public-Private Licensing for Indies](/public-private/indies)

- [Open Core for Indies](/open-core/indies)

- [Paid Support for Indies](/paid-support/indies)

- [Paid Development for Indies](/paid-development/indies)

## Business Model Explainers

{{site.title}} hosts a number of explainer pages, to help you communicate your business model to users:

- [What is public-private licensing?](/public-private/users)

- [What is open core?](/open-core/users)

- [What is paid support?](/paid-support/users)

## Explainers for Contributors

{{site.title}} hosts a number of explainer pages to help you communicate your business model to potential contributors to your projects:

- [Contributing to Public-Private Licensing Projects](/public-private/contributors)

- [Contributing to Open Core Projects](/open-core/contributors)

- [Contributing to Projects with Paid Support](/paid-support/contributors)

- [Contributing to Paid Development Projects](/paid-development/contributors)

## Legal Forms

{{site.title}} maintains a number of legal forms to give you starting points for the legal parts of your business:

{% for form in site.forms %}
- [{{form.title}}]({{form.url}})
{% endfor  %}
