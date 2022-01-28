---
title: Blog
layout: default
nav: Blog
---

https://github.com/qrohlf/qrohlf.github.io

https://jekyllrb.com/docs/step-by-step/08-blogging/

## Blog Entries
Special Topics in Data Science Applications in the Natural Resources Sciences

<h2>The Best Tool is {{ page.bestTool }}</h2>



<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>