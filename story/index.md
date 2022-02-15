---
layout: 1.1
title: story
---
Synopsis-teaser-things, for now.

<section>{%for ep in site.story%}<h2><a href="{%include url.html%}/story/{{ep.num}}">{{ep.title}}</a></h2><p>{{ep.summary}}</p>{%endfor%}</section>