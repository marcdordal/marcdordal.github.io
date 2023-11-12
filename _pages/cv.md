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
* B.S. in GitHub, GitHub University, 2012
* M.S. in Jekyll, GitHub University, 2014
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)

<!-- Work experience
======
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub -->
  
<!-- Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3 -->

Research
======
## Published Papers
  <ul>{% for post in site.published_papers %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Policy Papers
  <ul>{% for post in site.policy_papers %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Working Papers
  <ul>{% for post in site.working_papers %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## In Progress
  <ul>{% for post in site.works_in_progress %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Resting Work
  <ul>{% for post in site.resting_works %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
<!-- Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->

<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
