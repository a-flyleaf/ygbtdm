---
layout: 1.1
title: text ref
subpage: story
css: .desc{background:#202020;} hr{border:0; height:1px; background:#5e5e5e; max-width:20rem; margin:2rem auto 1.65rem;} .spoiler{background:0; cursor:initial;}
---
just rendering all titles, summaries, and teaser info on one page, for my own proofreading reference

----

{%for ep in site.story-v1%}<h2><a href="{%include url.html%}/story/v1/{{ep.num}}">{{ep.title}}</a></h2>{%if ep.quote%}<p><i>“{{ep.quote}}”</i></p>{%endif%}<p>{{ep.summary}}</p><div class="desc wrap">{{ep.content|markdownify}}</div>{%endfor%}

----

<span class="small">\*Last part doesn't have a quote; this is intentional.</span>