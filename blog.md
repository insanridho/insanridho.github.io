---
layout: default
title: Blog
permalink: /blog/
---

# Blog

{% for post in site.posts %}
<article style="margin: 0 0 28px 0;">
  <h2 style="margin: 0 0 6px 0;">
    <a href="{{ post.url }}">{{ post.title }}</a>
  </h2>

  <div style="opacity: .75; font-size: .95rem;">
    {{ post.date | date: "%B %d, %Y" }}
  </div>

  <p style="margin: 10px 0 0 0;">
    {{ post.excerpt | strip_html | truncate: 180 }}
  </p>

  <p style="margin: 8px 0 0 0;">
    <a href="{{ post.url }}">Read more →</a>
  </p>
</article>
{% endfor %}
