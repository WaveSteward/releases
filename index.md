---
title: The WaveSteward Evolution
description: This is where info about the new releases for WaveSteward are shared.
---
On this page you will find release notes, and what is coming...

[Latest Release](https://discord.com/channels/590290574192541726/1479193804840898752/1513193756495446207){:target="_blank" rel="noopener noreferrer"}

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span>{{ post.date | date: "%d %b %Y" }}</span>
    </li>
  {% endfor %}
</ul>

