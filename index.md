---
layout: home
title: Home
---

Welcome to my website!  
This is my cool new Jekyll-based page using the minima theme.

<h2>Body Goals</h2>
<ul>
  {% for post in site.body %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
