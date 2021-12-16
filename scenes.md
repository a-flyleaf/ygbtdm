---
layout: 1
title: scenes
---
Part divisions are subject to change, especially around the middle, but for the sake of scope I would really like to not break 12. That said, lengths vary.

{%for scene in site.scenes%}<article>
	<h2><a href="{{scene.url}}">{{scene.title}}</a></h2>
	{{scene.content}}
</article>{%endfor%}