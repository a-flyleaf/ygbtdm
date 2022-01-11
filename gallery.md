---
layout: 1.1
title: gallery
---
Currently in the process of copying over smaller scribbles, many of which are scattered throughout monthly roundups. For now, here's the big/standalone stuff.

<section id="gallery">{%for tn in site.gallery%}<a href="{{tn.url}}"><img src="{%include url.html%}/assets/img/gallery/{{tn.img}}-tn.png" alt="title"/></a>{%endfor%}</section>