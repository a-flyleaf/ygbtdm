---
layout: 1.2
title: gallery
css: "#gallery{max-width:850px;}"

fav1: teef
fav2: clueless
fav3: hyperpop
fav4: butyou
fav5: menagerie
fav6: helloween
fav7: expressions
fav8: badguys
fav9: designnotes
fav10: greasons
fav11: klstruggletweets
fav12: flowers
fav13: firstimpressions
fav14: sketchdump2
fav15: changes
fav16: annoyingbungame
fav17: spin
---
Standalone art related to the story or characters in some way, however tenuously. Some personal favorites\* below.

{%assign f1=site.gallery|where:"slug",page.fav1%}{%assign f2=site.gallery|where:"slug",page.fav2%}{%assign f3=site.gallery|where:"slug",page.fav3%}{%assign f4=site.gallery|where:"slug",page.fav4%}{%assign f5=site.gallery|where:"slug",page.fav5%}{%assign f6=site.gallery|where:"slug",page.fav6%}{%assign f7=site.gallery|where:"slug",page.fav7%}{%assign f8=site.gallery|where:"slug",page.fav8%}{%assign f9=site.gallery|where:"slug",page.fav9%}{%assign f11=site.gallery|where:"slug",page.fav11%}{%assign f12=site.gallery|where:"slug",page.fav12%}{%assign f13=site.gallery|where:"slug",page.fav13%}{%assign f14=site.gallery|where:"slug",page.fav14%}{%assign f15=site.gallery|where:"slug",page.fav15%}{%assign f16=site.gallery|where:"slug",page.fav16%}{%assign f17=site.gallery|where:"slug",page.fav17%}
<!--marginally less tedious: assign all potential picks upfront, then swap out in THIS assign-->{%assign art = f2|concat:f1|concat:f4|concat:f3|concat:f8|concat:f14|concat:f11|concat:f17%}
<section id="gallery" class="artwall">{%for tn in art%}<a href="{%include url.html%}/gallery/{{tn.slug}}"><img src="{%include url.html%}/assets/img/gallery/{%if tn.img%}{{tn.img}}{%else%}{{tn.date|date:'%Y-%m-%d'}}{%endif%}-tn.png" alt="{{tn.title}}"/></a>{%endfor%}</section>

Images automatically resize to fit onscreen. In wider browser windows (and if the image isn't bigger than your window), click to view larger. Fullsize files may be huge.

{%assign rn = site.roundups%}{%assign gl = site.gallery%}{%assign all = rn | concat: gl%}
\*The full gallery, including [monthly roundups]({%include url.html%}/gallery/roundups), has been punted to [its own page]({%include url.html%}/gallery/all)---on account of loading {{all.size}} thumbnails and counting.