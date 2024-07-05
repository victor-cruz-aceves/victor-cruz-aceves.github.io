---
layout: archive
permalink: /graphs/
title: "Graphs"
---

<p align="middle">
<a href="../images/rex/stm-visualization/index.html">
    <img src="../images/rex/far_right_viz_lemmatta.png" width="200" /></a>
<a href="../images/rex/cosine_similarity_reich_far_right.png">
    <img src="../images/rex/cosine_similarity_reich_far_right.png" width="170"/> </a>
<a href="../images/erame/lda-mallet-10.html">
    <img src="../images/erame/old_topic_model.jpg" width="180" /></a>
<a href="../images/miscellaneous/emoji_about-ISIS-v-non.html">
    <img src="../images/miscellaneous/emoji_about-ISIS-v-non.jpg" width="180" /></a>
<a href="../images/motra2022/violins_means.jpg">
    <img src="../images/motra2022/violins_means.jpg" width="240" /></a>  
<a href="../images/motra2022/curves.jpg">
    <img src="../images/motra2022/curves.jpg" width="300" /> </a>
<a href="../images/social_connectedness/f3_binscatter.jpeg">
    <img src="../images/social_connectedness/f3_binscatter.jpeg" width="200" /> </a>
<a href="../images/social_connectedness/heinsberg_connectedness.jpeg">
    <img src="../images/social_connectedness/heinsberg_connectedness.jpeg" width="160" /> </a>
<a href="../images/dissertation/5.jpg">
    <img src="../images/dissertation/5.jpg" width="180" /></a> 
<a href="../images/book/26_coefficient_plot.png"> 
    <img src="../images/book/26_coefficient_plot.png" width="160" /> </a> 
<a href="../images/book/27_coefficient_plot.png">
    <img src="../images/book/27_coefficient_plot.png" width="160" /></a>
<a href="../images/book/8_map.png"> 
    <img src="../images/book/8_map.png" width="160" /> </a>
<a href="../images/social_connectedness/covid_germany.jpeg">
    <img src="../images/social_connectedness/covid_germany.jpeg" width="160" />  </a>
<a href="../images/social_connectedness/kiel_freiburg_europe.jpeg">
    <img src="../images/social_connectedness/kiel_freiburg_europe.jpeg" width="160" /> </a>
  <a href="../images/dissertation/2.jpg">
    <img src="../images/dissertation/2.jpg" width="160" /> </a>
<a href="../images/dissertation/3.jpg">
    <img src="../images/dissertation/3.jpg" width="160" /> </a>
<a href="../images/dissertation/4.jpg">
    <img src="../images/dissertation/4.jpg" width="160" /> </a>
<a href="../images/dissertation/5.jpg">
    <img src="../images/dissertation/5.jpg" width="160" /></a>

{% for image in site.static_files %}
    {% if image.path contains 'images/old_twitter' %}
<a href="{{ site.baseurl }}{{ image.path }}">
<img src="{{ site.baseurl }}{{ image.path }}" alt="image" width="180" /></a>
    {% endif %}
{% endfor %}

{% for image in site.static_files %}
    {% if image.path contains 'images/miscellaneous/twitter_xl' %}
<a href="{{ site.baseurl }}{{ image.path }}">
<img src="{{ site.baseurl }}{{ image.path }}" alt="image" width="100" /></a>
    {% endif %}
{% endfor %}
</p>