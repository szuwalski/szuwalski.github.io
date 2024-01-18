---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

A full list of my publications can be seen in my CV. Here I select and summarize my favorite paper of each year.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
