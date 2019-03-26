---
title: Edgar Refskegg
feature_image: "https://picsum.photos/1300/400?image=989"
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
