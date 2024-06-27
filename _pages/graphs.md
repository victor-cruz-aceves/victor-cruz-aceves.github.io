---
layout: archive
permalink: /graphs/
title: "Graphs"
---

{% for image in site.static_files %}
    {% if image.path contains 'images/old_twitter' %}
        <img src="{{ site.baseurl }}{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %}