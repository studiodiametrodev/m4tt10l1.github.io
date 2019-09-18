---
title: m4t home page _site/index.md
layout: default
slug: /
carousel:
    title: Titolo carousel Home
    description: Descrizione del carousel in home page
    button:
        link: /posts/post-1.html
        text: Post 1
---
{% capture page_carousel %}{{page.carousel}}{% endcapture %}

{% include carousel.html params=page.carousel %}
<section class="sec-1">
  <div class="container">
    <h1>{{ page.title }}</h1>
  </div>
</section>
(inside <b>_site</b>)
