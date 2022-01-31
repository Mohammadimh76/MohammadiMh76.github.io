---
layout: archive
title: "Books"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


Articles
=======

{% for post in site.articles reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
