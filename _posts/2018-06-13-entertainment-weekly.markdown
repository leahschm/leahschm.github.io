---
layout: post
title:  "Entertainment Weekly"
categories: youngguns16
---
{% for image in site.static_files %}
{% if image.path contains 'images/et' %}
![image]({{ image.path }})
{% endif %}
{% endfor %}

[Jekyll docs][jekyll-docs]

[jekyll-docs]: https://jekyllrb.com/docs/home