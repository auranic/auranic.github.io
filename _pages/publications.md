---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<h1>My publications (sorted by date)</h1>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<h2>2019</h2>
{% for post in site.publications reversed %}
  {% if post.year == 2019 %}
      {% include archive-simple-publication.html %}
  {% endif %}
{% endfor %}

<h2>2018</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 2018 %}
      {% include archive-simple-publication.html %}
  {% endif %}
{% endfor %}

