---
layout: page
title: Gästebuch
---

Wer war schon alles hier?

<ul>
  {% for post in site.posts %}
    <li>
      <p>{{post.author}}: <a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a></p>
    </li>
  {% endfor %}
</ul>
