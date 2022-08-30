---
layout: 1.1
title: gallery
css: "#gallery{max-width:850px;}"
---
Standalone art related to the story or characters in some way, however tenuously. Spoiler-free highlights below.

{%assign hl1 = site.gallery | where: "slug","clueless"%}
{%assign hl2 = site.gallery | where:"slug","teef"%}
{%assign hl3 = site.gallery | where:"slug","butyou"%}
{%assign hl4 = site.gallery | where:"slug","hello"%}
{%assign hl5 = site.gallery | where:"slug","badguys"%}
{%assign hl6 = site.gallery | where:"slug","headshots2"%}
{%assign hl7 = site.gallery | where:"slug","annoyingbungame"%}
{%assign hl8 = site.gallery | where:"slug","spin"%}
{%assign art = hl1 | concat: hl2 | concat: hl3 | concat: hl4 | concat: hl5 | concat: hl6 | concat: hl7 | concat: hl8%}
<!--↑ this is unwieldy (surely this can be done with arrays...?) but idk how to simplify yet. /could/ add a tag to highlights but that sounds like more trouble than it's worth-->
<section id="gallery" class="artwall">{%for tn in art%}<a href="{%include url.html%}/gallery/{{tn.slug}}"><img src="{%include url.html%}/assets/img/gallery/{%if tn.img%}{{tn.img}}{%else%}{{tn.date|date:'%Y-%m-%d'}}{%endif%}-tn.png" alt="{{tn.title}}"/></a>{%endfor%}</section>

See also [the monthly roundups]({%include url.html%}/gallery/roundups), which contain an assortment of smaller doodles, or [everything in chronological order]({%include url.html%}/gallery/all). **May contain spoilers.**

Images automatically resize to fit onscreen. In wider browser windows (and if the image isn't bigger than your window), click to view larger. Fullsize files may be huge.