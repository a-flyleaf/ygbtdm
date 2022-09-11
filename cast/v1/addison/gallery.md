---
layout: 1.1
subpage: cast/addison
title: "Addison: gallery"
---
Design hasn't changed since the earliest drawings here, except for the first one which is an outlier for most people.

<section id="gallery" class="artwall">{%for tn in site.gallery%}{%if tn.tags contains "a"%}<a href="{%include url.html%}{%if tn.url contains 'roundup'%}/gallery/roundups/{{tn.slug}}{%else%}{{tn.permalink}}{%endif%}"{%if tn.url contains 'roundup'%} class="rn"{%endif%}><img src="{%include url.html%}/assets/img/gallery/{%if tn.url contains 'roundup'%}roundups/{{tn.slug}}{%else%}{%if tn.img%}{{tn.img}}{%else%}{{tn.date|date:'%Y-%m-%d'}}{%endif%}{%endif%}-tn.png" alt="{{tn.title}}"/></a>{%endif%}{%endfor%}</section>