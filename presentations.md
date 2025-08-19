---
layout: page
title: Presentations & Posters
permalink: /presentations/
---

<style>
/* Scoped styles for presentations page */
ul.presentations-list { padding-left: 1.2rem; }
ul.presentations-list li { margin: .75rem 0; }
.award-badge {
  display: inline-block;
  margin-top: .3rem;
  padding: 3px 10px 4px;
  font-size: 0.65rem;
  font-weight: 600;
  letter-spacing: .5px;
  text-transform: uppercase;
  background: #eef5ff;
  color: #0f4573;
  border: 1px solid #c2ddf3;
  border-radius: 999px;
  line-height: 1;
}
</style>

<ul class="presentations-list">
{%- assign sorted = site.data.presentations -%}
{%- comment -%} Data years are numeric; manual sort by year desc {%- endcomment -%}
{%- assign years = sorted | map: 'year' | uniq | sort | reverse -%}
{%- for y in years -%}
  {%- for item in sorted -%}
    {%- if item.year == y -%}
  <li>
    <strong>{{ item.title }}</strong> — {{ item.authors }}. <em>{{ item.event }}</em>, {{ item.year }}.
    {% if item.poster %} <a href="{{ item.poster | relative_url }}">[Poster]</a>{% endif %}
    {% if item.slides %} <a href="{{ item.slides | relative_url }}">[Slides]</a>{% endif %}
    {% if item.award %}<br><span class="award-badge" aria-label="Award received">{{ item.award }}</span>{% endif %}
  </li>
    {%- endif -%}
  {%- endfor -%}
{%- endfor -%}
</ul>
