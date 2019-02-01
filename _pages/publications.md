---
layout: archive
title: "My publications (sorted by date)"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for k in (2000:2019) %}
<h2>{{forloop.index}}</h2>
{% for post in site.publications reversed %}
  {% if post.year == k %}
      {% include archive-simple-publication.html %}
  {% endif %}
{% endfor %}
{% endfor %}



