---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[Please visit my Google Scholar page for most recten publications][1]  
[1]: https://scholar.google.com/citations?view_op=list_works&hl=en&user=CDXmWz4AAAAJ  
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
