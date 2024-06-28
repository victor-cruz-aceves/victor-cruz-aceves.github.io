---
layout: archive
permalink: /graphs/
title: "Graphs"
---

<p align="middle">
{% for image in site.static_files %}
    {% if image.path contains 'images/old_twitter' %}
<a href="../images/erame/lda-mallet-10.html">
<img src="{{ site.baseurl }}{{ image.path }}" alt="image" width="90" /></a>
    {% endif %}
{% endfor %}
</p>