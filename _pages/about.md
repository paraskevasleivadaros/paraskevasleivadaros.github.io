---
permalink: /
title: "About"
excerpt: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

☁️ Keeping the cloud up and running

## Favorite Tools
[![GCP](https://skillicons.dev/icons?i=gcp)](https://cloud.google.com/)
[![Linux](https://skillicons.dev/icons?i=linux)](https://linux.org/)
[![Python](https://skillicons.dev/icons?i=py)](https://python.org/)

## Posts
{% include base_path %}

{% assign sorted = site.posts %}
{% for post in sorted %}
  {% include archive-single.html %}
{% endfor %}
