---
layout: layouts/base.njk
pageClass: posts
templateEngineOverride: njk, md
---

<!-- <h1>{{ title }}</h1>  -->
<p class="date">
  Posted on <time datetime="{{ date }}">{{ date | dateDisplay }}</time>
</p>
<main>
  {{ content | safe }}
  <div class="footnote">
</main>
