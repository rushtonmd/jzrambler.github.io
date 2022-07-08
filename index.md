---
layout: default
title: 1965 AMC JZ-Rambler
---

![2020-10-23 09 43 36](https://user-images.githubusercontent.com/1479022/177861378-5978681b-59dd-412d-a1eb-7e582e3ef1d4.jpg)

{% if site.data.social-media %}
<div id="social-media">
    {% assign sm = site.data.social-media %}
    {% for entry in sm %}
        {% assign key = entry | first %}
        {% if sm[key].id %}
            <a href="{{ sm[key].href }}{{ sm[key].id }}" title="{{ sm[key].title }}"><i class="fa {{ sm[key].fa-icon }}" style="font-size:48px;"></i></a>
        {% endif %}
    {% endfor %}
</div>
{% endif %}

<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

<link href="//maxcdn.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css" rel="stylesheet">

