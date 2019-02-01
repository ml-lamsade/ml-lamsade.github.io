---
layout: default
title: Members
---

{% for member in site.members %}
  * {{ member.name }} - {{ member.position }} [ {{ member.website }} ] (website)

  {{ member.content | markdownify }}
  
{% endfor %}