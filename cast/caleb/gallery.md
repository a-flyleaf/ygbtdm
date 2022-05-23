---
layout: 1.1
subpage: cast/caleb
title: "Caleb: gallery"
---
Design hasn't changed much since the earliest drawings here. Outfit from the torso down was initially inconsistent, but the simplified version seen in the [design notes]({%include url.html%}/gallery/designnotes) has stuck.

<section id="gallery" class="artwall">{%for art in site.gallery%}{%if art.tags contains "c"%}<a href="{%include url.html%}{{art.permalink}}"><img src="{%include url.html%}/assets/img/gallery/{{art.img}}-tn.png" alt="{{art.title}}"/></a>{%endif%}{%endfor%}</section>