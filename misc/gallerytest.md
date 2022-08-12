---
layout: 1.1
title: mega gallery supreme
css: img{max-width:100px;}
---
[https://shopify.github.io/liquid/basics/operators/](https://shopify.github.io/liquid/basics/operators/)

## roundups only
<section id="gallery" class="artwall">
{%for tn in site.roundups%}<a href="{%include url.html%}{{tn.permalink}}"><img src="{%include url.html%}/assets/img/gallery/roundups/{{tn.slug}}-tn.png" alt="{{tn.title}}"/></a>{%endfor%}
</section>

## all??
<section id="gallery" class="artwall">
{%assign rn = site.roundups%}
{%assign gl = site.gallery%}
{%assign all = rn | concat: gl%}
{%for tn in all%}<a href="{%include url.html%}{{tn.permalink}}"><img src="{%include url.html%}/assets/img/gallery/{%if tn.url contains 'roundup'%}roundups/{{tn.slug}}{%else%}{{tn.img}}{%endif%}-tn.png" alt="{{tn.title}}"/></a>{%endfor%}
</section>