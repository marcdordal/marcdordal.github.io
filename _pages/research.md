---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my articles on <a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.
{% endif %}

{% include base_path %}

<h2>Published Papers</h2>
{% for post in site.published_papers reversed %}
  {% include archive-single-publi.html %}
{% endfor %}

<h2>Policy Papers</h2>
{% for post in site.policy_papers reversed %}
  {% include archive-single-publi.html %}
{% endfor %}

<h2>Working Papers</h2>
{% for post in site.working_papers reversed %}
  {% include archive-single-publi.html %}
{% endfor %}

<h2>In Progress</h2>
{% for post in site.works_in_progress reversed %}
  {% include archive-single-publi.html %}
{% endfor %}

<h2>Resting Work</h2>
{% for post in site.resting_works reversed %}
  {% include archive-single-publi.html %}
{% endfor %}

