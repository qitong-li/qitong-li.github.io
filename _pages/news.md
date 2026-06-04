---
permalink: /news/
title: "News"
layout: home-minimal
---

## News

<ul class="news-list">
{% for item in site.data.news %}<li><span class="news-date">{{ item.date }}</span> {% if item.link %}<a href="{{ item.link }}">{{ item.text }}</a>{% else %}{{ item.text }}{% endif %}</li>
{% endfor %}</ul>

<p style="font-size:0.88rem;"><a href="/">← Back home</a></p>
