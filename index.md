---
title: The WaveSteward Evolution
description: This is where info about the new releases for WaveSteward are shared.
---
On this page you will find release notes, and what is coming...

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span>{{ post.date | date: "%d %b %Y" }}</span>
    </li>
  {% endfor %}
</ul>

