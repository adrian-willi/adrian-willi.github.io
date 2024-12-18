---
layout: default
---

<div class="wrapper">
  <h1>{{ page.title }}</h1>
  <p><small>Posted on {{ page.date | date_to_long_string }}</small></p>
  <div class="post-content">
    {{ content }}
  </div>
</div>
