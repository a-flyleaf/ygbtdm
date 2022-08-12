---
layout: 1.1
title: mega gallery supreme
css: img{max-width:100px;}
---
[https://shopify.github.io/liquid/basics/operators/](https://shopify.github.io/liquid/basics/operators/)

## roundups only
<section id="gallery" class="artwall">
{%for tn in site.roundups%}<a href="{%include url.html%}/gallery/roundups/{{tn.slug}}"><img src="{%include url.html%}/assets/img/gallery/roundups/{{tn.slug}}-tn.png" alt="{{tn.title}}"/></a>{%endfor%}
</section>

## all??
<section id="gallery" class="artwall">
{%assign rn = site.roundups%}
{%assign gl = site.gallery%}
{%assign all = rn | concat: gl%}
{%for tn in all%}<a href="{%include url.html%}{%if tn.url contains 'roundup'%}/gallery/roundups/{{tn.slug}}{%else%}{{tn.permalink}}{%endif%}"><img src="{%include url.html%}/assets/img/gallery/{%if tn.url contains 'roundup'%}roundups/{{tn.slug}}{%else%}{{tn.img}}{%endif%}-tn.png" alt="{{tn.title}}"/></a>{%endfor%}
</section>

ok so THEORETICALLY i could make a mega "literally Everything" gallery page (and use a class to indicate roundups) with this, but I will also have to go back and assign dates to everything. right now dates are treated more like a string since image urls can vary. it would be tedious as hell but at least dA gives me an objective date for everything, so ¯\\\_(ツ\")_/¯

## multiple tags
<ul>{%for tn in site.gallery%}
{%if tn.tags.size > 1%}
<li>{{tn.title}} {{tn.tags|size}}</li>
{%endif%}
{%endfor%}</ul>
WELP guess I can get rid of the "multi" thing in toyshelf. for this page, 100x100 character-specific thumbnails?