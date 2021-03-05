---

layout: page
title: "Blog"
permalink: /blog/

---

Hello, welcome to the blog. 

<ul>
  {% for post in site._posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
