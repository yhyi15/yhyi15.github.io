---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

  (You can also find my publication list on <u><a href="https://scholar.google.com/citations?hl=en&user=yHRKAt8AAAAJ&view_op=list_works&sortby=pubdate">my Google Scholar</a></u> and <u><a href="https://dblp.org/pid/167/3788.html">DBLP</a></u> profile.)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
