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
<ol style="padding-left: 20px;">
{% for post in site.published_papers reversed %}
  <li style="padding-left: 5px; margin-bottom: 20px;"> 
    {% include archive-single-publi.html %}
  </li>
{% endfor %}
</ol>

<h2>Policy Papers</h2>
<ol style="padding-left: 20px;">
{% for post in site.policy_papers reversed %}
  <li style="padding-left: 5px; margin-bottom: 20px;"> 
    {% include archive-single-publi.html %}
  </li>
{% endfor %}
</ol>

<h2>Working Papers</h2>
<ol style="padding-left: 20px;">
{% for post in site.working_papers reversed %}
  <li style="padding-left: 5px; margin-bottom: 20px;"> 
    {% include archive-single-publi.html %}
  </li>
{% endfor %}
</ol>

<h2>In Progress</h2>
<ol style="padding-left: 20px;">
{% for post in site.works_in_progress reversed %}
  <li style="padding-left: 5px; margin-bottom: 20px;"> 
    {% include archive-single-publi.html %} 
  </li>
{% endfor %}
</ol>

<!-- <h2>Resting Work</h2>
<ol style="padding-left: 20px;">
{% for post in site.resting_works reversed %}
  <li style="padding-left: 5px; margin-bottom: 20px;"> 
    {% include archive-single-publi.html %}
  </li>
{% endfor %}
</ol> -->

{% if site.resting_works %}
<h2>Resting Work</h2>
<ol style="padding-left: 20px;">
  {% for post in site.resting_works reversed %}
    <li style="padding-left: 5px; margin-bottom: 20px;"> 
      {% include archive-single-publi.html %}
    </li>
  {% endfor %}
</ol>
{% endif %}
