---
layout: default
title: 1965 AMC JZ-R
---

![2020-10-23 09 43 36](https://user-images.githubusercontent.com/1479022/177861378-5978681b-59dd-412d-a1eb-7e582e3ef1d4.jpg)

<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

