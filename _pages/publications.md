---
layout: archive
title: "My publications (sorted by date)"
permalink: /publications/
author_profile: true
---

You can also find my articles on <a href="{{ author.googlescholar }}">my Google Scholar profile</a>.

{% include base_path %}


<h2>2019</h2>
{% for post in site.publications reversed %}
  {% if post.year == 2019 %}
      {% include archive-simple-publication.html %}
  {% endif %}
{% endfor %}


<h2>2018</h2>
{% for post in site.publications reversed %}
  {% if post.year == 2018 %}
      {% include archive-simple-publication.html %}
  {% endif %}
{% endfor %}

<h2>2017</h2>
{% for post in site.publications reversed %}
  {% if post.year == 2017 %}
      {% include archive-simple-publication.html %}
  {% endif %}
{% endfor %}

<h2>2016</h2>
{% for post in site.publications reversed %}
  {% if post.year == 2016 %}
      {% include archive-simple-publication.html %}
  {% endif %}
{% endfor %}

<h2>2015</h2>
{% for post in site.publications reversed %}
  {% if post.year == 2015 %}
      {% include archive-simple-publication.html %}
  {% endif %}
{% endfor %}

<h2>2014</h2>
{% for post in site.publications reversed %}
  {% if post.year == 2014 %}
      {% include archive-simple-publication.html %}
  {% endif %}
{% endfor %}

<h2>2013</h2>
{% for post in site.publications reversed %}
  {% if post.year == 2013 %}
      {% include archive-simple-publication.html %}
  {% endif %}
{% endfor %}

<h2>2012</h2>
{% for post in site.publications reversed %}
  {% if post.year == 2012 %}
      {% include archive-simple-publication.html %}
  {% endif %}
{% endfor %}

<h2>2011</h2>
{% for post in site.publications reversed %}
  {% if post.year == 2011 %}
      {% include archive-simple-publication.html %}
  {% endif %}
{% endfor %}

<h2>2010</h2>
{% for post in site.publications reversed %}
  {% if post.year == 2010 %}
      {% include archive-simple-publication.html %}
  {% endif %}
{% endfor %}

<h2>2009</h2>
{% for post in site.publications reversed %}
  {% if post.year == 2009 %}
      {% include archive-simple-publication.html %}
  {% endif %}
{% endfor %}

<h2>2008</h2>
{% for post in site.publications reversed %}
  {% if post.year == 2008 %}
      {% include archive-simple-publication.html %}
  {% endif %}
{% endfor %}

<h2>2007</h2>
{% for post in site.publications reversed %}
  {% if post.year == 2007 %}
      {% include archive-simple-publication.html %}
  {% endif %}
{% endfor %}

<h2>Earlier publications</h2>
{% for post in site.publications reversed %}
  {% if post.year < 2007 %}
      {% include archive-simple-publication.html %}
  {% endif %}
{% endfor %}

