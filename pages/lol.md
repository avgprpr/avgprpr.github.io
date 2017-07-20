---
layout: page
permalink: /lol/
---

<div class="posts">
  {% for post in site.categories.lol %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>
    </article>
  {% endfor %}
</div>
