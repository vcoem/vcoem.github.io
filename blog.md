---
layout: page
title: Blog
---

<ul class="post-list">
 {% for post in paginator.posts %} 
  <li>
   <article>
    <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
   </article>
  </li>
 {% endfor %}
</ul>