---
layout: post
title:  "Entertainment Weekly"
categories: youngguns16
---
{% for image in site.static_files %}
{% if image.path contains 'images/entertainment-weekly' %}
![image]({{ image.path }})
{% endif %}
{% endfor %}

Credits

Co-designer: Tim Goodman