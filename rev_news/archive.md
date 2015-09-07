---
layout: default
title: Git Rev News Archive
---

Here you can see all the previous editions. See [About Git Rev News](/rev_news/rev_news.html) for ways you can subscribe.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
