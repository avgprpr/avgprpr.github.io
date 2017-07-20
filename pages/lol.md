---
layout: page
permalink: /lol/
---
![](../images/xiaoshuo/xs1.jpg )   
<div class="posts">
  {% for post in site.categories.lol %}
    <article class="post">

      <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
    </article>
  {% endfor %}
</div>
