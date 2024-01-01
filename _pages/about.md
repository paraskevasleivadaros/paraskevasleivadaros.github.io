---
permalink: /
title: "About"
excerpt: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Building a better world through open-source contributions, one pull request at a time

## Favorite Tools / Languages
[![Ansible](https://skills.thijs.gg/icons?i=ansible)](https://www.ansible.com/)
[![GCP](https://skills.thijs.gg/icons?i=gcp)](https://cloud.google.com/)
[![Linux](https://skills.thijs.gg/icons?i=linux)](https://www.linux.org/)
[![Python](https://skills.thijs.gg/icons?i=py)](https://www.python.org/)

## Posts
{% include base_path %}

{% assign sorted = site.posts %}
{% for post in sorted %}
  {% include archive-single.html %}
{% endfor %}
