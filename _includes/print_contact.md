<ul class="show-print">
  {% if site.contact.website %}
    <li><i class="fa fa-globe fa-2x" aria-hidden="true"></i> {{ site.contact.website }}</li>
  {% endif %}
  {% if site.contact.email %}
    <li><i class="fa fa-envelope fa-2x" aria-hidden="true"></i> {{ site.contact.email }}</li>
  {% endif %}
  {% if site.contact.linkedin %}
    <li><i class="fa fa-linkedin fa-2x" aria-hidden="true"></i> {{ site.contact.linkedin }}</li>
  {% endif %}
  {% if site.contact.github %}
    <li><i class="fa fa-github fa-2x" aria-hidden="true"></i> {{ site.contact.github }}</li>
  {% endif %}
  {% if site.contact.stack_overflow %}
    <li><i class="fa fa-stack-overflow fa-2x" aria-hidden="true"></i> {{ site.contact.stack_overflow }}</li>
  {% endif %}
</ul>

