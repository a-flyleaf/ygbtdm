---
layout: 1.1
subpage: gallery
title: "gallery: all"
css: .rn img{border-radius:15px;} main h2{font-size:3em; text-align:center; margin:1em auto .5em;}
---
Covers just about everything that isn't a separately-posted colorscript. [Monthly roundups]({%include url.html%}/gallery/roundups) are denoted with rounded corners.

{%assign rn = site.roundups%}{%assign gl = site.gallery%}{%assign all = rn | concat: gl%}{%assign all = rn | concat: gl | sort: "date"%}

## 2021
<section id="gallery" class="artwall">{%for tn in all%}{%assign year = tn.date|date:"%Y"%}{%if year contains '2021'%}<a href="{%include url.html%}{%if tn.url contains 'roundup'%}/gallery/roundups/{{tn.slug}}{%else%}{{tn.permalink}}{%endif%}"{%if tn.url contains 'roundup'%} class="rn"{%endif%}><img src="{%include url.html%}/assets/img/gallery/{%if tn.url contains 'roundup'%}roundups/{{tn.slug}}{%else%}{%if tn.img%}{{tn.img}}{%else%}{{tn.date|date:'%Y-%m-%d'}}{%endif%}{%endif%}-tn.png" alt="{{tn.title}}"/></a>{%endif%}{%endfor%}</section>

## 2022
<section id="gallery" class="artwall">{%for tn in all%}{%assign year = tn.date|date:"%Y"%}{%if year contains '2022'%}<a href="{%include url.html%}{%if tn.url contains 'roundup'%}/gallery/roundups/{{tn.slug}}{%else%}{{tn.permalink}}{%endif%}"{%if tn.url contains 'roundup'%} class="rn"{%endif%}><img src="{%include url.html%}/assets/img/gallery/{%if tn.url contains 'roundup'%}roundups/{{tn.slug}}{%else%}{%if tn.img%}{{tn.img}}{%else%}{{tn.date|date:'%Y-%m-%d'}}{%endif%}{%endif%}-tn.png" alt="{{tn.title}}"/></a>{%endif%}{%endfor%}</section>