---
layout: 1.1
subpage: cast/joce
title: "Joce: gallery"
---
Design hasn't changed since the earliest drawings here.

<section id="gallery" class="artwall">{%for art in site.gallery%}{%if art.tags contains "j"%}<a href="{%include url.html%}{{art.permalink}}"><img src="{%include url.html%}/assets/img/gallery/{{art.img}}-tn.png" alt="{{art.title}}"/></a>{%endif%}{%endfor%}</section>