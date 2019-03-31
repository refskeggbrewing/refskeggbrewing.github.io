---
title: Brewing
feature_image: /assets/images/about_brewing.jpg
---

* * *

The one pictured to the left of me in the banner is my good friend
Osric from the Barony of Bhakail in the East Kingdom. He's an excellet
brewer and friend.

## Brewing Blog Posts

* * * 

<ul>
{% for post in site.categories['brewing'] %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
{% endfor %}
</ul>
