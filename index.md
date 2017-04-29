---
title: Blogging Like a Hacker
---

# Welcome to Piggy House
This is house for my blog. Index....

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
       {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

Thanks.
