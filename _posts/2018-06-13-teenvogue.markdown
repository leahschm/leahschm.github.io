---
layout: post
title:  "Teen Vogue"
categories: youngguns16
---
{% for image in site.static_files %}
{% if image.path contains 'images/teenvogue' %}
![image]({{ image.path }})
{% endif %}
{% endfor %}