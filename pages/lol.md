---
layout: page
permalink: /lol/
title: 英雄联盟外传ーー拯救瓦洛兰
author: 作者:左边牙齿疼
description: 英雄联盟20年后的故事
image: ../images/xiaoshuo/xs1.jpg
---
<div class="posts">
  {% for post in site.categories.lol %}
    <article class="post">
      <p><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a><p>
    </article>
  {% endfor %}
</div>
