---
layout: 1.1
subpage: cast/v1/white-rabbit
title: "“White Rabbit”: gallery"
---
Arguably not even the same character as the eighth person in early drawings, but everything's included here anyway. Redesign started around [May 2021]({%include url.html%}/gallery/roundups/2021-05) and slowly took shape over subsequent months; appearance has been more consistent since 2022.

<section id="gallery" class="artwall">{%for tn in site.gallery%}{%if tn.tags contains "wr"%}<a href="{%include url.html%}{%if tn.url contains 'roundup'%}/gallery/roundups/{{tn.slug}}{%else%}{{tn.permalink}}{%endif%}"{%if tn.url contains 'roundup'%} class="rn"{%endif%}><img src="{%include url.html%}/assets/img/gallery/{%if tn.url contains 'roundup'%}roundups/{{tn.slug}}{%else%}{%if tn.img%}{{tn.img}}{%else%}{{tn.date|date:'%Y-%m-%d'}}{%endif%}{%endif%}-tn.png" alt="{{tn.title}}"/></a>{%endif%}{%endfor%}</section>