---
title: Blog
layout: default
nav: Blog
---

https://github.com/qrohlf/qrohlf.github.io

https://jekyllrb.com/docs/step-by-step/08-blogging/

https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/jekyll-install-windows-example-blog-tutorial

## Blog Entries
Special Topics in Data Science Applications in the Natural Resources Sciences





<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>