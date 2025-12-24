---
layout: default
title: Home
---

# Andrew's Blog

I like to write blogs periodically, and need a place for them. They'll probably mostly be about genomics, and all likely about science.

## Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <br>
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
