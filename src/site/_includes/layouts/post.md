---
layout: layouts/base.njk
pageClass: posts
templateEngineOverride: njk, md
---

<p class="date">
  Kadir Ince <br><time datetime="{{ date }}">{{ date | dateDisplay }}</time>
</p>
<main>
  {{ content | safe }}
  <div class="footnote">
  </div>
</main>