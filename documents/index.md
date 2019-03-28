---
title: Documentation
---

## General

The EZ-doc for Atlantia A&S documentation can be found here: [EZ-Doc](/assets/documents/basic.pdf)  

Because I come from an engineering background, for the most part my documentation is cited using IEEE style citations. I try to keep research as detailed as possible.
If you'd like to see in more detail how I create the documentation I
use, please look [here](process). 

## Brewing 

Period French Cider Documentation: [Cider](/assets/documents/cider.pdf)
I also have some raspberry mead that I need to add the documentation
for. I have also done a bochet based on a French book from 1390.

## Enameling

Enamel documentation used at Clash with Bacchus: [Bacchus](/assets/documents/enamel_clashwbacchus.pdf)

Enameling notes: [Enamel Notes](/assets/documents/enamel_notes.pdf)

General Enameling Procedure: [Enamel Procedure](/assets/documents/enamel_procedure.pdf)

General References used for enameling: [Enamel References](/assets/documents/enamel_references.pdf)

## Documentation Blog Posts

<ul>
{% for post in site.categories['documentation'] %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
{% endfor %}
</ul>
