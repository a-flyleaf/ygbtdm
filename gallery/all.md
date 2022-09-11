---
layout: 1.2
title: full gallery
subpage: gallery
---
[Monthly roundups]({%include url.html%}/gallery/roundups) are denoted with rounded corners and a faint border. If you're looking for art of specific characters, see the [giant character checklist]({%include url.html%}/gallery/cast).

{%assign rn = site.roundups%}{%assign gl = site.gallery%}{%assign all = rn | concat: gl | sort: "date"%}

<section id="gallery" class="artwall">{%for tn in all%}<a href="{%include url.html%}/gallery/{%if tn.url contains 'roundup'%}roundups/{%endif%}{{tn.slug}}"{%if tn.url contains 'roundup'%} class="rn"{%endif%}><img src="{%include url.html%}/assets/img/gallery/{%if tn.url contains 'roundup'%}roundups/{{tn.slug}}{%else%}{%if tn.img%}{{tn.img}}{%else%}{{tn.date|date:'%Y-%m-%d'}}{%endif%}{%endif%}-tn.png" alt="{{tn.title}}" loading="lazy"/></a>{%endfor%}</section>