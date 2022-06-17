---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

I'm interested in problems in high energy theory, broadly. For my master's thesis I worked on gravity where we looked at superradiance in a quantum corrected black hole solution. My thesis is linked below. We have a preprint prepared from our results, which you can also find below or on my INSPIRE [page](https://inspirehep.net/authors/2094576). More broadly, I'm interested in QFTs in curved spacetime, holography and the relationship between quantum field theories and gravity theories.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

