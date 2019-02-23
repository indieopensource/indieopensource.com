---
title: Resources for Users
description: guides, forms, and resources
layout: default
---

# {{page.title}}

{{site.title}} hosts a number of explainer pages for various indie open source business models:

{% for guide in site.user_guides %}
- [{{guide.title}}]({{guide.url}})
{% endfor %}
