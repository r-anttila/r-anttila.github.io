---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on my <a href="{{"https://scholar.google.com/citations?user=LrtrSKIAAAAJ&hl=fi&oi=ao"}}">Google Scholar</a> or <a href="{{"https://www.researchgate.net/profile/Roope-Anttila"}}">ResearchGate</a> profiles.

{% if site.preprints.size > 0 %}
## Preprints
{% for post in site.preprints reversed %} {% include archive-single-publication.html %} {% endfor %}
{% endif %}

{% if site.accepted.size > 0 %}
## Accepted
{% for post in site.accepted reversed %} {% include archive-single-publication.html %} {% endfor %}
{% endif %}

## Published
{% for post in site.publications reversed %} {% include archive-single-publication.html %} {% endfor %}

## Undergraduate
{% for post in site.undergrad reversed %} {% include archive-single-publication.html %} {% endfor %}