---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

  (You can also find my full publication list on <u><a href="https://scholar.google.com/citations?hl=en&user=yHRKAt8AAAAJ&view_op=list_works&sortby=pubdate">my Google Scholar profile</a></u>.)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
