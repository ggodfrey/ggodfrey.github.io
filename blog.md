---
title: Blog
layout: blog-home
---
<img src = "https://ggodfrey.github.io/images/London.PNG">
<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h2><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></h2>
      <div class="entry">
        {{ post.excerpt }}
      </div>
      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>
