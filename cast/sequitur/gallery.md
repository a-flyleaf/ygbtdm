---
layout: 1.1
subpage: cast/sequitur
title: "Sequitur: gallery"
---
Design got a major overhaul in [June 2021]({%include url.html%}/gallery/roundups/2021-06) and hasn't changed much since.

<section id="gallery" class="artwall">{%for art in site.gallery%}{%if art.tags contains "sq"%}<a href="{%include url.html%}{{art.permalink}}"><img src="{%include url.html%}/assets/img/gallery/{{art.img}}-tn.png" alt="{{art.title}}"/></a>{%endif%}{%endfor%}</section>