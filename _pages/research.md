---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<h2>Published Papers</h2>
{% for post in site.published_papers reversed %}
  {% include archive-single.html %}
{% endfor %}

<h2>Policy Papers</h2>

<h2>Working Papers</h2>

<h2>Work in Progress</h2>

<h2>Resting Work</h2>


