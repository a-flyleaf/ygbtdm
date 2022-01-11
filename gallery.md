---
layout: 1.1
title: gallery
---
Some big stuff that, for the most part, isn't buried in monthly roundups. (Smaller scribbles will be added on other pages.)

Fair warning: fullsize files are huge. In wide browser windows, images automatically resize to fit onscreen; click to view at higher resolution. (May not appear to do anything on horizontal images.)

<section id="gallery" class="artwall">{%for tn in site.gallery%}<a href="{%include url.html%}{{tn.url}}"><img src="{%include url.html%}/assets/img/gallery/{{tn.img}}-tn.png" alt="title"/></a>{%endfor%}</section>