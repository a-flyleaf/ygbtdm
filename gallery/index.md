---
layout: 1.1
title: gallery
---
Stuff that I thought warranted standalone posting. Also see [the monthly roundups]({%include url.html%}/gallery/roundups), which contain an assortment of smaller doodles.

Fair warning: fullsize files are huge. In wide browser windows, images automatically resize to fit onscreen; click to view at higher resolution. (May not appear to do anything if image width exceeds browser size.)

<section id="gallery" class="artwall">{%for tn in site.gallery%}<a href="{%include url.html%}{{tn.permalink}}"><img src="{%include url.html%}/assets/img/gallery/{%if tn.img%}{{tn.img}}{%else%}{{tn.date|date:'%Y-%m-%d'}}{%endif%}-tn.png" alt="{{tn.title}}"/></a>{%endfor%}</section>