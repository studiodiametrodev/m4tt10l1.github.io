---
title: m4t home page
layout: default
slug: /
carousel1:
- carousel:
  - title: Titolo carousel Home
  - description: Descrizione del carousel in home page
  - button:
    - link: /posts/post-1.html
    - text: Post 1
---
{{page.carousel1}}
{% assign page_carousel=page.carousel1 %}
{% include carousel.html params=page_carousel %}
<section class="sec-1">
  <div class="container">
    <h1>{{ page.title }}</h1>
  </div>
</section>
