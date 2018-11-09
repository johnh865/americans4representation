---
title: News
subtitle: 
layout: layouts/base.njk
---

## News Updates


<ul class="listing">
{%- for page in collections.post|reverse -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay }}</time>
  </li>
{%- endfor -%}
</ul>



