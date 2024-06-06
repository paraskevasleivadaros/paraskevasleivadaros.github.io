---
permalink: /
title: "About"
excerpt: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Building a better world 🌍 through open-source contributions 💻, one pull request at a time 🚀

## Favorite Tools / Languages
[![Ansible](https://skillicons.dev/icons?i=ansible)](https://ansible.com/)
[![GCP](https://skillicons.dev/icons?i=gcp)](https://cloud.google.com/)
[![Linux](https://skillicons.dev/icons?i=linux)](https://linux.org/)
[![Python](https://skillicons.dev/icons?i=py)](https://python.org/)

## Posts
{% include base_path %}

{% assign sorted = site.posts %}
{% for post in sorted %}
  {% include archive-single.html %}
{% endfor %}
