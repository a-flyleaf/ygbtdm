---
layout: 1.2
title: story
css: ".artwall{font-size:inherit;} .artwall img{margin:.25em; max-width:32%;} .artwall img:first-child,.artwall img:last-child{display:block; margin:.25em auto;}"
---
Covers only, for now.<!--still extremely not my favorite but leaving this in the v1 layout messed with navigation links >:T-->

<section class="artwall">{%for ep in site.story-v1%}<img src="{%include url.html%}/assets/img/story/v1/{{ep.num}}-600.png" alt="{{ep.num}}: {{ep.title}}"/>{%endfor%}</section>