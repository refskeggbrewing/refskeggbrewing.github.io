---
title: Edgar Refskegg
feature_image: "https://picsum.photos/1300/400?image=989"
---


f1rst p0st!
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
