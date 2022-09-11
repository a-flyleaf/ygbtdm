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
css: "#cast a:focus~img,#cast a:active~img,#cast a:hover>img{opacity:0;} #cast img{transition:.1s ease-in-out;} #cast a{background-position:center; background-repeat:no-repeat;}
#j{background-image:url(../assets/img/cast/j-cast.png);}/*NOT on hover or there's a weird flash*/ #kl{background-image:url(../assets/img/cast/kl-cast.png);} #a{background-image:url(../assets/img/cast/a-cast.png);} #c{background-image:url(../assets/img/cast/c-cast.png);} #g{background-image:url(../assets/img/cast/g-cast.png);} #d{background-image:url(../assets/img/cast/d-cast.png);} #sq{background-image:url(../assets/img/cast/sq-cast.png);} #wr{background-image:url(../assets/img/cast/wr-cast.png);}
#cast div{display:block;}
@media only screen and (min-width:600px){#cast div{display:inline-block;}}"
---
Visual descriptions & other design notes for the main eight, as they appear by default.

<section class="artwall" id="cast"><div class="four"><div class="two"><a href="{%include url.html%}/cast/designnotes/joce" id="j"><img src="{%include url.html%}/assets/img/cast/j-cast-slh.png" alt="Joce" /></a><a href="{%include url.html%}/cast/designnotes/kay-lin" id="kl"><img src="{%include url.html%}/assets/img/cast/kl-cast-slh.png" alt="Kay Lin" /></a></div><!--/2--><div class="two"><a href="{%include url.html%}/cast/designnotes/addison" id="a"><img src="{%include url.html%}/assets/img/cast/a-cast-slh.png" alt="Addison" /></a><a href="{%include url.html%}/cast/designnotes/caleb" id="c"><img src="{%include url.html%}/assets/img/cast/c-cast-slh.png" alt="Caleb" /></a></div><!--/2--></div><!--/4--><div class="four"><div class="two"><a href="{%include url.html%}/cast/designnotes/gary" id="g"><img src="{%include url.html%}/assets/img/cast/g-cast-slh.png" alt="Gary" /></a><a href="{%include url.html%}/cast/designnotes/the-accountant" id="d"><img src="{%include url.html%}/assets/img/cast/d-cast-slh.png" alt="“The accountant”" /></a></div><!--/2--><div class="two"><a href="{%include url.html%}/cast/designnotes/sequitur" id="sq"><img src="{%include url.html%}/assets/img/cast/sq-cast-slh.png" alt="Sequitur" /></a><a href="{%include url.html%}/cast/designnotes/white-rabbit" id="wr"><img src="{%include url.html%}/assets/img/cast/wr-cast-slh.png" alt="“White Rabbit”" /></a></div><!--/2--></div><!--/4--></section>

<!--
<section class="artwall" id="cast">{%for chr in page.cr%}<a href="{%include url.html%}/cast/designnotes/{%if chr.url%}{{chr.url}}{%else%}{{chr.nm|downcase}}{%endif%}" id="{{chr.id}}"><img src="{%include url.html%}/assets/img/cast/{{chr.id}}-cast-slh.png" alt="{{chr.nm}}"/></a>{%endfor%}</section>
-->