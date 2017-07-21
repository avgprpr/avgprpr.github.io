---
layout: page
permalink: /lol/
title: 英雄联盟外传ーー拯救瓦洛兰
description: 作者:左边牙齿疼
image: ../images/xiaoshuo/xs1.jpg
---
<div class="posts">
  {% for post in site.categories.lol %}
    <article class="post">
      <h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3>
    </article>
  {% endfor %}
</div>
