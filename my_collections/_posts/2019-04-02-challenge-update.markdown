---
layout: post
title:  "The Challenge"
date:   2019-04-02 10:20:00 +0200
moment: 2nd April
categories: javascript-30
permalink: /posts/js-30-challenge
bg: workcreate.jpg
---

So, yes! Let's do this challenge. I was so enthusiastic that I embark a buddy to do the challenge at the same time !!

<strong>Day 1.</strong>
So, the first day I played with some classList javascript fun to make a drum that you could see here:

{% for post in site.days limit: 30 %}
  <article class="index-page">
    <h2><a href="{{ days.url | relative_url }}">{{ days.name }}</a></h2>
  </article>
{% endfor %}

<strong>Day 2.</strong>
Tic-Tac.
A clock and I made the tic-tac feature !
(<a href="/_days/_day2/index-START.html">Day 2</a>)


    <h2><a href="{{ "../_days/_day1/index-START.html" | prepend: site.baseurl }}">Day 1</a></h2>
