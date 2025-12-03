---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* 2025: Master MAS - Ecole nationale des ponts et chaussées
* 2021 - 2024: Cycle ingénieur, Ecole polytechnique, Palaiseau
* 2019 - 2021: Classe préparatoire MP, lycée Champollion, Grenoble

{% comment %}
Research experience
======


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
{% endcomment %}