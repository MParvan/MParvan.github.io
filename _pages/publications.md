---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
description: "Publications and research outputs by Milad Parvan."
---

You can also find my research on [Google Scholar](https://scholar.google.com/citations?user=HWHGAnUAAAAJ&hl=en).

{% include base_path %}

{% assign sorted_publications = site.publications | sort: "display_order" | reverse %}
{% for post in sorted_publications %}
  {% include archive-single.html %}
{% endfor %}
