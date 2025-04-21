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
[![Bash](https://skillicons.dev/icons?i=bash)](https://www.gnu.org/software/bash/)
[![Linux](https://skillicons.dev/icons?i=linux)](https://linux.org/)
[![Python](https://skillicons.dev/icons?i=py)](https://python.org/)
[![VSCode](https://skillicons.dev/icons?i=vscode)](https://code.visualstudio.com/)

## Posts
{% include base_path %}

{% assign sorted = site.posts %}
{% for post in sorted %}
  {% include archive-single.html %}
{% endfor %}
