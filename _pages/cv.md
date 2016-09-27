---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /wordpress/cv/
---

{% include base_path %}

Education
======
* Masters in Information Management and Systems, UC Berkeley, 2015
* Masters in International Policy Studies, Stanford University, 2011
* Bachelors in Global Economics, UC Santa Cruz, 2007

Work experience
======
* Summer 2015: Research Assistant
  * UC Berkeley
  * Duties included: Rejecting pull requests
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Rejecting pull requests
  * Supervisor: Professor Hub

Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  {% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}

Talks
======
  {% for post in site.talks %}
    {% unless post.talk_type == "Conference proceedings talk" %}
      {% include archive-single-talk-cv.html %}
    {% endunless %}
  {% endfor %}

Teaching
======
  {% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}
