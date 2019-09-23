---
permalink: /posts/post-3.html
title: Post Title 3
slug: post-3
jumbotron:
  - title: Jumbo Tron
  - description: lorem Ipsum
  - button:
    - link: /
    - text: click
---
{% capture page_slug %}{{ page.slug }}{% endcapture %}
{% include pagebuilder.html slug=page_slug %}
<section class="sec-p-1">
  <div class="container">
    <h2> {{ page.title }} </h2>
  </div>
</section>
