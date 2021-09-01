---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


{% include base_path %}


You can also find my articles on <a href="https://scholar.google.com/citations?user=drLbv9gAAAAJ&hl=en">Google Scholar</a>.



{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<br>
