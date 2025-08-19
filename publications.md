---
layout: page
title: Publications
permalink: /publications/
---

<ul>
{% assign sorted = site.data.publications | sort: 'year' | reverse %}
{% for pub in sorted %}
  <li>
    <strong>{{ pub.title }}</strong> — {{ pub.authors }}. <em>{{ pub.venue }}</em>, {{ pub.year }}.
    {% if pub.pdf %}<a href="{{ pub.pdf | relative_url }}">[PDF]</a>{% endif %}
    {% if pub.doi %}<a href="{{ pub.doi }}">[Link]</a>{% endif %}
  </li>
{% endfor %}
</ul>
