---
layout: default
title: Home
---

# Welcome to Dango Bites
Bite sized info on Japan. It's culture, history, and other topics to enrich your knowledge of this great country.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> ({{ post.date | date: "%B %d, %Y" }})
    </li>
  {% endfor %}
</ul>
