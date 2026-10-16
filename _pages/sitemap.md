---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
sitemap: false
robots: "noindex, follow"
---

Browse Seyed Milad Hatamlee's website. An [XML sitemap]({{ '/sitemap.xml' | relative_url }}) is also available for search engines.

## Main pages

- [Seyed Milad Hatamlee — Home]({{ '/' | relative_url }})
- [Research]({{ '/research/' | relative_url }})
- [Publications]({{ '/publications/' | relative_url }})
- [Curriculum vitae]({{ '/cv/' | relative_url }})
- [Contact]({{ '/contact/' | relative_url }})

## Research projects

<ul>
{% assign research_pages = site.pages | sort: "title" %}
{% for research_page in research_pages %}
  {% if research_page.url contains "/research/" and research_page.url != "/research/" and research_page.sitemap != false %}
  <li><a href="{{ research_page.url | relative_url }}">{{ research_page.title | escape }}</a></li>
  {% endif %}
{% endfor %}
</ul>
