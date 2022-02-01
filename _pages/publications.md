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

  <ul>{% for post in site.articles reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
