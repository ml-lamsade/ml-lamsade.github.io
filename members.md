---
layout: default
title: Members
---

{% for member in site.members %}
  * {{ member.name }} - {{ member.position }}

  {{ member.content | markdownify }}
  
{% endfor %}