---
title: Enameling 
feature_image: /assets/images/about_enameling.jpg
---

* * * 

## Supplies

Certainly supplies are important. Please check out the [Supplies](suppliers) page for purchasing information! 
In the mean time, the main places where I obtain my enameling materials
are:
* Rio Grande
    * Really good for general metalworking and a good place online to
      buy copper
* Contenti
    * Good general jewelry making supplies
* Thompson Enamel
    * As the name implies, enamel resources: enamel, kiln supplies, etc.

## Enameling Pictures

Click here to [enameling pictures](pictures)! 

* * * 

## Enameling Blog Posts

<ul>
{% for post in site.categories['enameling'] %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
{% endfor %}
</ul>
