---
layout: page
title: Publications
permalink: /publications/
---

<ul>
{% assign sorted = site.publications | sort: 'year' | reverse %}
{% for pub in sorted %}
  <li>
    <a href="{{ pub.url | relative_url }}">{{ pub.title }}</a> — {{ pub.authors }}. <em>{{ pub.venue }}</em>, {{ pub.year }}.
    {% if pub.pdf %}<a href="{{ pub.pdf }}">[PDF]</a>{% endif %}
    {% if pub.doi %}<a href="{{ pub.doi }}">[DOI]</a>{% endif %}
  </li>
{% endfor %}
</ul>
