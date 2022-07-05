---
layout: 1.1
title: gallery
---
Stuff that I thought warranted standalone posting. See also [the monthly roundups]({%include url.html%}/gallery/roundups), which contain an assortment of smaller doodles.

Fair warning: fullsize files are huge. In wide browser windows, images automatically resize to fit onscreen; click to view at higher resolution. (May not appear to do anything if image width exceeds browser size.)

<section id="gallery" class="artwall">{%for tn in site.gallery%}<a href="{%include url.html%}{{tn.permalink}}"><img src="{%include url.html%}/assets/img/gallery/{{tn.img}}-tn.png" alt="{{tn.title}}"/></a>{%endfor%}</section>