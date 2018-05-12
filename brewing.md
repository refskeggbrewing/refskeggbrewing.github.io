---
title: Edgar's Brewing
---
<ul>
{% for post in site.categories['brewing'] %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
{% endfor %}
</ul>
