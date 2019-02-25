---
layout: default
---

{{site.title}} publishes {{site.description}}.

<h2 id="showcase">Showcase</h2>

<ul class="indies">
{% for indie in site.indies %}
<li>{% include indie.html %}</li>
{% endfor %}
</ul>
