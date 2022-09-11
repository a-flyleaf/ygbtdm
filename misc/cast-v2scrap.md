---
layout: 1.2
title: cast

cr:
  - id: j
    nm: Joce
  - id: kl
    nm: Kay Lin
    url: kay-lin
  - id: a
    nm: Addison
  - id: c
    nm: Caleb
  - id: g
    nm: Gary
  - id: d
    nm: “The accountant”
    url: the-accountant
  - id: sq
    nm: Sequitur
  - id: wr
    nm: “White Rabbit”
    url: white-rabbit
css: "/*this is so fuckign annoying god bless*/ .artwall{overflow-x:auto;} #cast{width:1841px;}"
---
Visual descriptions & other design notes for the main eight, as they appear by default.
<section class="artwall"><div id="cast">{%for chr in page.cr%}<a href="{%include url.html%}/cast/designnotes/{%if chr.url%}{{chr.url}}{%else%}{{chr.nm|downcase}}{%endif%}" id="{{chr.id}}"><img src="{%include url.html%}/assets/img/cast/{{chr.id}}-silhouette-850.png" alt="{{chr.nm}}"/>{%endfor%}</div></section>