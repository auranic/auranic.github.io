---
layout: archive
title: "My publications (sorted by topics)"
permalink: /publications_topics/
author_profile: true
---

You can also find my articles on <a href="https://scholar.google.com/citations?user=r29H9sQAAAAJ&hl=fr">my Google Scholar profile</a>.

{% include base_path %}

<sup>*</sup>, <sup>^</sup> - stands for joint first or senior authorship.

<h2>Topics</h2>
<div>
<a href="#MLN">Machine Learning</a> - <a href="#KNF">Knowledge formalization</a><br>
<a href="#MMN">Modeling biological networks</a> - <a href="#CBO">Computational biology</a><br>
<a href="#REV">Reviews</a>
</div>

<h2><a id="MLN"></a>Machine learning methods and applications</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'MLN' %} 
	{% if post.category == 'journal' %}
	      {% include archive-simple-publication.html %}
	{% endif %} 
  {% endif %}
{% endfor %}
<h3>Peer-reviewed conference papers</h3>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'MLN' %} {% if post.category == 'conference' %}
      {% include archive-simple-publication.html %}
  {% endif %} {% endif %}
{% endfor %}
<h3>Peer-reviewed chapters</h3>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'MLN' %} {% if post.category == 'chapter' %}
      {% include archive-simple-publication.html %}
  {% endif %} {% endif %}
{% endfor %}
<h3>Unpublished preprints</h3>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'MLN' %} {% if post.category == 'preprint' %}
      {% include archive-simple-publication.html %}
  {% endif %} {% endif %}
{% endfor %}


<h2><a id="KNF"></a>Knowledge formalization in biology</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'KNF' %}
      {% include archive-simple-publication.html %}
  {% endif %}
{% endfor %}



<h2><a id="MMN"></a>Mathematical modeling of biological networks</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'MMN' %}
      {% include archive-simple-publication.html %}
  {% endif %}
{% endfor %}
<h3>Peer-reviewed conference papers</h3>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'MMN' %} {% if post.category == 'conference' %}
      {% include archive-simple-publication.html %}
  {% endif %} {% endif %}
{% endfor %}
<h3>Unpublished preprints</h3>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'MMN' %} {% if post.category == 'preprint' %}
      {% include archive-simple-publication.html %}
  {% endif %} {% endif %}
{% endfor %}


<h2><a id="CBO"></a>Computational biology methods and applications</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'CBO' %}
      {% include archive-simple-publication.html %}
  {% endif %}
{% endfor %}

<h2><a id="REV"></a>Reviews</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'REV' %}
      {% include archive-simple-publication.html %}
  {% endif %}
{% endfor %}
