---
title: "Research"
permalink: /research/
author_profile: true
---


{% if site.author.googlescholar %}
  <div class="wordwrap">This is ...
Do we really need this?
</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


