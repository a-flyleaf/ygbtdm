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
---
{%include cast-v1.2.html%}
<!--
<section class="artwall" id="cast">{%for chr in page.cr%}<a href="{%include url.html%}/cast/{%if chr.url%}{{chr.url}}{%else%}{{chr.nm|downcase}}{%endif%}" id="{{chr.id}}"><img src="{%include url.html%}/assets/img/cast/{{chr.id}}-cast-slh.png" alt="{{chr.nm}}"/></a>{%endfor%}</section>
-->