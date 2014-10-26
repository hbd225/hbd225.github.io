---
layout: page
title: code reading
tagline: ""
---
{% include JB/setup %}

## トップ

code を読んで気づいたことなど書いていきます！


## 最近の投稿

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
