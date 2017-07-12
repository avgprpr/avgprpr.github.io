---
layout: page
permalink: /about/
---

<div class="posts">
  {% for post in site.categories.myPost %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <img src="{{ site.baseurl }}/images/{{ post.image }}">
    </article>
  {% endfor %}
</div>
