---
layout: archive-no-title
permalink: /programming/
title: "Programming"
author_profile: true
---
{% include base_path %}
<h2 class="page__title">Programming projects</h2>
Below are some open-source packages and codes that I developed for my research projects. They are used for numerical simulation of various physical processes allowing to obtain quantitative signal estimates and for help in the experiment. I really like open-source but, unfortunately, not all my projects are publicly available at the moment.

{% for post in site.programming %}
  {% include archive-single-programming.html %}
{% endfor %}
