---
layout: 1.1
subpage: cast/kay-lin
title: "Kay Lin: gallery"
---
Bandages in the default design have been tweaked as of [June 2021]({%include url.html%}/gallery/roundups/2021-06).

<section id="gallery" class="artwall">{%for art in site.gallery%}{%if art.tags contains "kl"%}<a href="{%include url.html%}{{art.permalink}}"><img src="{%include url.html%}/assets/img/gallery/{{art.img}}-tn.png" alt="{{art.title}}"/></a>{%endif%}{%endfor%}</section>