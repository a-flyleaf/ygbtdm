---
layout: 1.1
subpage: cast/white-rabbit
title: "“White Rabbit”: gallery"
---
Arguably not even the same character as the eighth person in early drawings, but everything's included here anyway. Redesign started around [May 2021]({%include url.html%}/gallery/roundups/2021-05) and slowly took shape over subsequent months; appearance has been more consistent since 2022.

<section id="gallery" class="artwall">{%for art in site.gallery%}{%if art.tags contains "wr"%}<a href="{%include url.html%}{{art.permalink}}"><img src="{%include url.html%}/assets/img/gallery/{{art.img}}-tn.png" alt="{{art.title}}"/></a>{%endif%}{%endfor%}</section>