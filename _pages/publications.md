---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[Journal Articles](#journal-articles)\
[Conference Papers](#conference-papers)\
[Patents](#patents)

You can also find my articles on my [Google Scholar profile]({{site.author.googlescholar}}).

{% include base_path %}

## Journal Articles
{% for post in site.publications reversed %}
  {% if post.pubtype == 'journal' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}


## Conference Papers
{% for post in site.publications reversed %}
  {% if post.pubtype == 'conference' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Patents
{% for post in site.publications reversed %}
  {% if post.pubtype == 'patent' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
