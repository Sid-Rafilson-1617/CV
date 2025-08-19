---
layout: page
title: Publications
permalink: /publications/
---

<ul>
{% assign sorted = site.data.publications | sort: 'year' | reverse %}
{% for pub in sorted %}
  <li>
<<<<<<< HEAD
    <a href="{{ pub.url | relative_url }}">{{ pub.title }}</a> — {{ pub.authors }}. <em>{{ pub.venue }}</em>, {{ pub.year }}.
    {% if pub.pdf != blank %}<a href="{{ pub.pdf | relative_url }}">[PDF]</a>{% endif %}
    {% if pub.doi != blank %}<a href="{{ pub.doi }}">[DOI]</a>{% endif %}
=======
    <strong>{{ pub.title }}</strong> — {{ pub.authors }}. <em>{{ pub.venue }}</em>, {{ pub.year }}.
    {% if pub.pdf %} <a href="{{ pub.pdf | relative_url }}">[PDF]</a>{% endif %}
    {% if pub.doi %} <a href="{{ pub.doi }}">[Link]</a>{% endif %}
>>>>>>> 990086d (updates)
  </li>
{% endfor %}
</ul>
