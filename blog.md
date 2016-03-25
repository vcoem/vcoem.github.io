---
layout: page
title: Blog
subtitle: Why you'd want to go on a date with me
---

<ul class="post-list">
{% for post in paginator.posts %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></article></li>
{% endfor %}
</ul>