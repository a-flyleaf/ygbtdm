---
layout: 1.1
title: gallery
---
Some big stuff that, for the most part, isn't buried in monthly roundups. (Smaller scribbles forthcoming, and will be on other pages.)

Fair warning: files may be huge.

<section id="gallery" class="artwall">{%for tn in site.gallery%}<a href="{{tn.url}}"><img src="{%include url.html%}/assets/img/gallery/{{tn.img}}-tn.png" alt="title"/></a>{%endfor%}</section>