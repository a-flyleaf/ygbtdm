---
layout: 1.1
title: gallery
css: strong{color:#d6d6d6;}
---
Standalone art related to the story or characters in some way, however tenuously. See also [the monthly roundups]({%include url.html%}/gallery/roundups), which contain an assortment of smaller doodles, or [everything in chronological order]({%include url.html%}/gallery/all). **May contain spoilers.**

Images automatically resize to fit onscreen. In wider browser windows (and if the image isn't bigger than your window), click to view larger. Fullsize files may be huge.

<section id="gallery" class="artwall">{%for tn in site.gallery%}<a href="{%include url.html%}{{tn.permalink}}"><img src="{%include url.html%}/assets/img/gallery/{%if tn.img%}{{tn.img}}{%else%}{{tn.date|date:'%Y-%m-%d'}}{%endif%}-tn.png" alt="{{tn.title}}"/></a>{%endfor%}</section>