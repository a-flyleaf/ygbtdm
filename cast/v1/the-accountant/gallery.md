---
layout: 1.1
subpage: cast/the-accountant
title: "“The accountant”: gallery"
---
Design hasn't changed much since the earliest drawings here; gloves got added somewhere along the line.

<section id="gallery" class="artwall">{%for tn in site.gallery%}{%if tn.tags contains "d"%}<a href="{%include url.html%}{%if tn.url contains 'roundup'%}/gallery/roundups/{{tn.slug}}{%else%}{{tn.permalink}}{%endif%}"{%if tn.url contains 'roundup'%} class="rn"{%endif%}><img src="{%include url.html%}/assets/img/gallery/{%if tn.url contains 'roundup'%}roundups/{{tn.slug}}{%else%}{%if tn.img%}{{tn.img}}{%else%}{{tn.date|date:'%Y-%m-%d'}}{%endif%}{%endif%}-tn.png" alt="{{tn.title}}"/></a>{%endif%}{%endfor%}</section>