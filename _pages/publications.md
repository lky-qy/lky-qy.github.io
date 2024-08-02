---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
{% endif %}
  <div class="wordwrap">You can also find my articles on <a href="https://www.researchgate.net/profile/Liang-Knagyu">my ResearchGate profile</a>.</div>


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
