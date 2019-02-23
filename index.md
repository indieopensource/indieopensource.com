---
title: Homepage
layout: default
---

This website provides free resources about business models for independent open source software developers.

<h2 id="showcase">Showcase</h2>

<ul class="indies">
{% for indie in site.indies %}
<li><a href="{{indie.url}}">{{indie.title | escape}}</a></li>
{% endfor %}
</ul>
