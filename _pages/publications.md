---
layout: archive
title: "Publications"
permalink: /publications/
---

{% include base_path %}

Publications
======

<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>
