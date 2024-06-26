---
permalink: /graphs/
title: "Graphs"
---

{% for image in site.images %}
    {% if image.path contains 'old_twitter' %}
        <img src="{{ site.baseurl }}{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %}