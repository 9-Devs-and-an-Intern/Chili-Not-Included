---
layout: default
title: Home
---

<p class="dev2"> # Welcome to Chili Not Included

This is the collective hopes, dreams, hallucinations, and lunches of the dev team.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
</p>
