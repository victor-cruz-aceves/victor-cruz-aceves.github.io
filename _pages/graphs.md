---
layout: archive
permalink: /graphs/
title: "Graphs"
---

<p align="middle">
{% for image in site.static_files %}
    {% if image.path contains 'images/old_twitter' %}
<a href="{{ site.baseurl }}{{ image.path }}">
<img src="{{ site.baseurl }}{{ image.path }}" alt="image" width="90" /></a>
    {% endif %}
{% endfor %}
</p>