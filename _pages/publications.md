---
layout: archive-no-title
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

<h2 class="page__title">Relevant Peer-Review Papers</h2>
<ol>
    {% assign sorted_publications = site.publications | sort: "path" %}
    {% for post in sorted_publications %}
    <li>{% include archive-single-publication.html %}</li>
    {% endfor %}
</ol>
