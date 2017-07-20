---
layout: page
permalink: /lol/
---

<div class="posts">
  ![](../images/xiaoshuo/xs1.jpg )  
  {% for post in site.categories.lol %}
    <article class="post">

      <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
    </article>
  {% endfor %}
</div>
