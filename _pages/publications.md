---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[Journal Articles](#journal-articles)\
[Conference Papers](#conference-papers)\
[White Papers](#white-papers)\
[Academic](#academic)\ 
[Presentations](#presentations)\

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Resources
 * Yuan, S., Hu, J., Liu, X., Duan, J.: Slow manifolds for dynamical systems with non-Gaussian stable L´evy noise. Anal. Appl. 17(03), 477-511
(2019)[DOI](https://shopify.github.io/liquid/tags/control-flow/)


## Journal Articles
{% for post in site.publications reversed %}
  {% if post.pubtype == 'journal' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}


## Conference Papers
{% for post in site.publications reversed %}
  {% if post.pubtype == 'conference' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

## White Papers
{% for post in site.publications reversed %}
  {% if post.pubtype == 'whitepaper' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}


## Academic
{% for post in site.publications reversed %}
  {% if post.pubtype == 'academic' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Presentations
{% for post in site.publications reversed %}
  {% if post.pubtype == 'presentation' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

