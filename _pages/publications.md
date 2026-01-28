---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

## Journal Articles
{% assign journals = site.publications | where: "publication_type", "journal" %}
{% for post in journals reversed %}
  {% include archive-single.html %}
{% endfor %}

## Conference Papers
{% assign conferences = site.publications | where: "publication_type", "conference"  %}
{% for post in conferences reversed %}
  {% include archive-single.html %}
{% endfor %}