

{% for member in site.members %}
  <h2>{{ member.name }} - {{ member.position }}</h2>
  <p>{{ member.content | markdownify }}</p>
{% endfor %}