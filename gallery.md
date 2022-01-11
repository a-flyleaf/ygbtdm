---
layout: 1.1
title: gallery
---
Currently copying over smaller scribbles, many of which are scattered throughout monthly roundups. For now, here's some art that got uploaded separately.

Fair warning: files may be huge.

<section id="gallery" class="artwall">{%for tn in site.gallery%}<a href="{{tn.url}}"><img src="{%include url.html%}/assets/img/gallery/{{tn.img}}-tn.png" alt="title"/></a>{%endfor%}</section>