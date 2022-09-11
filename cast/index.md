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
#j{background-image:url(../assets/img/cast/j-cast.png);}/*NOT on hover or there's a weird flash*/ #kl{background-image:url(../assets/img/cast/kl-cast.png);} #a{background-image:url(../assets/img/cast/a-cast.png);} #c{background-image:url(../assets/img/cast/c-cast.png);} #g{background-image:url(../assets/img/cast/g-cast.png);} #d{background-image:url(../assets/img/cast/d-cast.png);} #sq{background-image:url(../assets/img/cast/sq-cast.png);} #wr{background-image:url(../assets/img/cast/wr-cast.png);}"
---
Visual descriptions & other design notes for the main eight, as they appear by default.
<section class="artwall" id="cast">{%for chr in page.cr%}<a href="{%include url.html%}/cast/designnotes/{%if chr.url%}{{chr.url}}{%else%}{{chr.nm|downcase}}{%endif%}" id="{{chr.id}}"><img src="{%include url.html%}/assets/img/cast/{{chr.id}}-cast-slh.png" alt="{{chr.nm}}"/>{%endfor%}</section>
