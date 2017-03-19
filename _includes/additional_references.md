# [](#additional-references) {{ site.data[page.lang].additional_reference }}
* * *
<ul>
{% for ar in site.data[page.lang].additional_references %}
  <li>
    <a href="{{ ar.link }}" target="_blank">{{ ar.title }}</a>
    {% if ar.description %}
      <p>{{ ar.description }}</p>
    {% endif %}
  </li>
{% endfor %}
</ul>
