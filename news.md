---
layout: default
title: News & seminars 
---
    
{% for post in site.posts %}
    * {{ post.date | date_to_string }} [{{post.title}}]({{ post.url }})
{% endfor %}


	
