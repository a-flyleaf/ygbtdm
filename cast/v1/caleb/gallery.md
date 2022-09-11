---
layout: 1.1
subpage: cast/v1/caleb
title: "Caleb: gallery"
---
Design hasn't changed much since the earliest drawings here. Outfit from the torso down was initially inconsistent, but the simplified version seen in the [design notes]({%include url.html%}/gallery/designnotes) has stuck.

<section id="gallery" class="artwall">{%for tn in site.gallery%}{%if tn.tags contains "c"%}<a href="{%include url.html%}{%if tn.url contains 'roundup'%}/gallery/roundups/{{tn.slug}}{%else%}{{tn.permalink}}{%endif%}"{%if tn.url contains 'roundup'%} class="rn"{%endif%}><img src="{%include url.html%}/assets/img/gallery/{%if tn.url contains 'roundup'%}roundups/{{tn.slug}}{%else%}{%if tn.img%}{{tn.img}}{%else%}{{tn.date|date:'%Y-%m-%d'}}{%endif%}{%endif%}-tn.png" alt="{{tn.title}}"/></a>{%endif%}{%endfor%}</section>