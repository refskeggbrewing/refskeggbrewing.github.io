---
title: Presence
---
<ul>
{% for post in site.categories['presence'] %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
{% endfor %}
</ul>
