---
title: Blog
layout: default
nav: Blog
---

https://jekyllrb.com/docs/step-by-step/08-blogging/

## Blog Entries
Special Topics in Data Science Applications in the Natural Resources Sciences

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>