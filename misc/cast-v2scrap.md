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
css: "#cast a:focus~img,#cast a:active~img,#cast a:hover>img{opacity:0;} #cast img{transition:.1s ease-in-out;}
#j{background-image:url(../assets/img/cast/j-fullbody-default-850.png);}/*NOT on hover or there's a weird flash*/ #kl{background-image:url(../assets/img/cast/kl-fullbody-default-850.png);} #a{background-image:url(../assets/img/cast/a-fullbody-default-850.png);} #c{background-image:url(../assets/img/cast/c-fullbody-default-850.png);} #g{background-image:url(../assets/img/cast/g-fullbody-default-850.png);} #d{background-image:url(../assets/img/cast/d-fullbody-default-850.png);} #sq{background-image:url(../assets/img/cast/sq-fullbody-default-850.png);} #wr{background-image:url(../assets/img/cast/wr-fullbody-default-850.png);}"
---
Visual descriptions & other design notes for the main eight, as they appear by default.
<section class="artwall" id="cast">{%for chr in page.cr%}<a href="{%include url.html%}/cast/designnotes/{%if chr.url%}{{chr.url}}{%else%}{{chr.nm|downcase}}{%endif%}" id="{{chr.id}}"><img src="{%include url.html%}/assets/img/cast/{{chr.id}}-silhouette-850.png" alt="{{chr.nm}}"/>{%endfor%}</section>

<!--asdlkgahsdlksadgjasdghlskdfjslkj this is NOT mobile-friendly... first solution was better ig gdi-->