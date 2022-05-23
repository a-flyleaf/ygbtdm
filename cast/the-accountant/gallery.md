---
layout: 1.1
subpage: cast/the-accountant
title: "“The accountant”: gallery"
---
Design hasn't changed much since the earliest drawings here; gloves got added somewhere along the line.

<section id="gallery" class="artwall">{%for art in site.gallery%}{%if art.tags contains "d"%}<a href="{%include url.html%}{{art.permalink}}"><img src="{%include url.html%}/assets/img/gallery/{{art.img}}-tn.png" alt="{{art.title}}"/></a>{%endif%}{%endfor%}</section>