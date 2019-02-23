{% include before.html %}
<main>
  <h1>{{page.title}}</h1>
  <p class="description">{{page.description}}</p>
  <p><a href="{{page.repository}}/releases/latest">Latest Release</a></p>
  <p><a href="{{page.repository}}">Project Repository</a></p>
  {{ content }}
  {% if page.business_models %}
    <h2>Business Models</h2>
    <ul>
    {% for model in page.business_models %}
      <li>
        {% include business-model.html %}
      </li>
    {% endfor %}
    </ul>
  {% endif %}
</main>
{% include after.html %}
