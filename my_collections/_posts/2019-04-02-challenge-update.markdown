---
layout: post
title:  "The Challenge"
date:   2019-04-02 10:20:00 +0200
moment: 2nd April
categories: javascript-30
permalink: posts/js-30-challenge
bg: workcreate.jpg
---

So, yes! Let's do this challenge. I was so enthusiastic that I embark a buddy to do the challenge at the same time !!

{% for post in site.days %}
  <ul>
    <li style="list-style-type: none">
      <h3><a href="{{ post.url | relative_url }}">{{ post.name }}</a></h3><p>{{ post.description }}</p>
    </li>
  </ul>
{% endfor %}
