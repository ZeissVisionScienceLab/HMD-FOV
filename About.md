---
layout: default
title: About
nav_order: 8
nav_exclude: false
description: ""
---

# Contributions
<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>

# Support
The Federal Ministry of Education and Research (BMBF) supported the project in the framework of IDeA (project number 16SV8104). Authors also recognize intra-mutual funding of the University of Tübingen through the mini graduate school ‘Integrative Augmented Reality (I-AR)’. The authors acknowledge support by Open Access Publishing Fund of the University of Tübingen. The founders did not have any additional role in the study design, data collection, and analysis, decision to publish, or preparation of the manuscript.

### > [Back to main page](https://zeissvisionsciencelab.github.io/HMD-FOV/)
