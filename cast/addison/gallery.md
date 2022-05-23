---
layout: 1.1
subpage: cast/addison
title: "Addison: gallery"
---
Design hasn't changed since the earliest drawings here, except for the first one which is an outlier for most people.

<section id="gallery" class="artwall">{%for art in site.gallery%}{%if art.tags contains "a"%}<a href="{%include url.html%}{{art.permalink}}"><img src="{%include url.html%}/assets/img/gallery/{{art.img}}-tn.png" alt="{{art.title}}"/></a>{%endif%}{%endfor%}</section>