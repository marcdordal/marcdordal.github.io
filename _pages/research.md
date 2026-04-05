---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
paper_display_mode: compact # "compact" or "default"
---

{% if site.author.googlescholar %}
  You can also find my articles on [my Google Scholar profile]({{ site.author.googlescholar }}){: target="_blank" }.
{% endif %}

{% include base_path %}
{% assign paper_display_mode = page.paper_display_mode | default: "default" %}

<!-- markdownlint-disable MD033 -->
<section style="margin-bottom: 2rem;">
<h2>Published Papers</h2>
<ol style="padding-left: 20px; margin-bottom: 0;">
{% for post in site.published_papers reversed %}
  <li style="padding-left: 5px; margin-bottom: 20px;">
    {% include archive-single-publi.html display_mode=paper_display_mode %}
  </li>
{% endfor %}
</ol>
</section>

<section style="margin-bottom: 2rem;">
<h2>Policy Papers</h2>
<ol style="padding-left: 20px; margin-bottom: 0;">
{% for post in site.policy_papers reversed %}
  <li style="padding-left: 5px; margin-bottom: 20px;">
    {% include archive-single-publi.html display_mode=paper_display_mode %}
  </li>
{% endfor %}
</ol>
</section>

<section style="margin-bottom: 2rem;">
<h2>Working Papers</h2>
<ol style="padding-left: 20px; margin-bottom: 0;">
{% for post in site.working_papers reversed %}
  <li style="padding-left: 5px; margin-bottom: 20px;">
    {% include archive-single-publi.html display_mode=paper_display_mode %}
  </li>
{% endfor %}
</ol>
</section>

<section style="margin-bottom: 2rem;">
<h2>In Progress</h2>
<ol style="padding-left: 20px; margin-bottom: 0;">
{% for post in site.works_in_progress reversed %}
  <li style="padding-left: 5px; margin-bottom: 20px;">
    {% include archive-single-publi.html display_mode=paper_display_mode %}
  </li>
{% endfor %}
</ol>
</section>

<!-- <h2>Resting Work</h2>
<ol style="padding-left: 20px;">
{% for post in site.resting_works reversed %}
  <li style="padding-left: 5px; margin-bottom: 20px;"> 
    {% include archive-single-publi.html %}
  </li>
{% endfor %}
</ol> -->

{% if site.resting_works.size > 0 %}
<section style="margin-bottom: 2rem;">
<h2>Resting Work</h2>
<ol style="padding-left: 20px; margin-bottom: 0;">
  {% for post in site.resting_works reversed %}
    <li style="padding-left: 5px; margin-bottom: 20px;">
      {% include archive-single-publi.html display_mode=paper_display_mode %}
    </li>
  {% endfor %}
</ol>
</section>
{% endif %}
<!-- markdownlint-enable MD033 -->
