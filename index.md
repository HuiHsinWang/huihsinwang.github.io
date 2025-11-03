
---
layout: defualt
title: "Hui Hsin's Space"
---

# Welcome to my space This is my own story and life record

## 最新文章
<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y-%m-%d" }}
  </li>
{% endfor %}
</ul>

## Welcome to my own sharing. I am a Taiwanese, a doctoral student site in Japan now, focus on oceanography climate change. Experience in high school teacher in Taiwan, process engineer in TSMC semiconductor company as my career before.
