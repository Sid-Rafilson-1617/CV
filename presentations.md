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
    {% if item.poster %}<a href="{{ item.poster }}">[Poster]</a>{% endif %}
    {% if item.slides %}<a href="{{ item.slides }}">[Slides]</a>{% endif %}
  </li>
{% endfor %}
</ul>
