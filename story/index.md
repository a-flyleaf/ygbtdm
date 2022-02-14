---
layout: 1.1
title: story
---
Details and scenes and such, or something of the sort, forthcoming. For now, have synopsis-teaser-things.

<section>{%for ep in site.story%}<h2><a href="{%include url.html%}/story/{{ep.num}}">{{ep.title}}</a></h2><p>{{ep.summary}}</p>{%endfor%}</section>