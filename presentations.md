---
layout: page
title: Presentations & Posters
permalink: /presentations/
---

<ul>
{% assign sorted = site.presentations | sort: 'year' | reverse %}
{% for item in sorted %}
  <li>
    <a href="{{ item.url | relative_url }}">{{ item.title }}</a> — {{ item.authors }}. <em>{{ item.event }}</em>, {{ item.year }}.
    {% if item.poster != blank %}<a href="{{ item.poster | relative_url }}">[Poster]</a>{% endif %}
    {% if item.slides != blank %}<a href="{{ item.slides | relative_url }}">[Slides]</a>{% endif %}
  </li>
{% endfor %}
</ul>
