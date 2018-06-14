---
layout: post
title:  "Portraits"
categories: youngguns16
---
{% for image in site.static_files %}
{% if image.path contains 'images/portraits' %}
![image]({{ image.path }})
{% endif %}
{% endfor %}