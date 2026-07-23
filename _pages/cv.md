---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Profile
======
I am Dr. John Smith, a researcher focused on large language models, contextual reasoning, long-context foundation models, and efficient machine learning systems.

Research interests
======
* Large language models and language modeling
* Contextual reasoning in multi-task environments
* Long-context foundation models
* Efficient and simplified LLM architectures

Scholarly metrics
======
* Total citations: 127
* h-index: 8
* i10-index: 6

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

Service
======
* Reviewer, LCFM 2025

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
