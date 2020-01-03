---
layout: archive
title: "Talks and Presentations by Professor Gao Zhi"
permalink: /talks/
author_profile: true
---

# Year 2019
content

# Year 2018
content

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
