---
layout: 1.1
subpage: cast/kay-lin
title: "Kay Lin: gallery"
---
Bandages in the default design have been tweaked as of [June 2021]({%include url.html%}/gallery/roundups/2021-06).

<section id="gallery" class="artwall">{%for tn in site.gallery%}{%if tn.tags contains "kl"%}<a href="{%include url.html%}{%if tn.url contains 'roundup'%}/gallery/roundups/{{tn.slug}}{%else%}{{tn.permalink}}{%endif%}"{%if tn.url contains 'roundup'%} class="rn"{%endif%}><img src="{%include url.html%}/assets/img/gallery/{%if tn.url contains 'roundup'%}roundups/{{tn.slug}}{%else%}{%if tn.img%}{{tn.img}}{%else%}{{tn.date|date:'%Y-%m-%d'}}{%endif%}{%endif%}-tn.png" alt="{{tn.title}}"/></a>{%endif%}{%endfor%}</section>