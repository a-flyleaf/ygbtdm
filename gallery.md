---
layout: 1.1
title: gallery
---
Currently in the process of copying over smaller scribbles, many of which are scattered throughout monthly roundups. For now, here's the big/standalone stuff.

<section id="gallery"><ul>{%for paeg in site.gallery%}
	<li><a href="{{paeg.url}}">{{paeg.title}} - {{paeg.desc}}</a></li>
{%endfor%}</ul></section>