---
layout: 1.1
title: monthly roundups
subpage: gallery
permalink: /gallery/roundups
---
Because posting everything individually was devouring my storage alive, whoops. Each of these pages has multiple drawings; thumbnail is just limited to one to keep me sane.

As with the [gallery]({%include url.html%}/gallery), fullsize files are huge, and (in wide browser windows) can be clicked to view at full resolution. Besides cropping and/or fading non-story-related content, these are unedited from the versions posted <a href="https://www.deviantart.com/a-flyleaf/gallery/81345929/compilation-stuff" target="_blank">on deviantArt</a>.

<section id="gallery" class="artwall roundup">{%for rd in site.roundups%}<a href="{%include url.html%}{{rd.permalink}}"><img src="{%include url.html%}/assets/img/gallery/{{rd.img}}-tn.png" alt="{{rd.title}}"/></a>{%endfor%}</section>