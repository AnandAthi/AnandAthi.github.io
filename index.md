---
layout: home
title: "Howdy ! வணக்கம்! नमस्कारं ! "
---

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    </li>
  {% endfor %}
</ul>
