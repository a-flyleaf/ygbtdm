---
layout: 1.2
title: cast
---
<div id="nav">
	<img src="{%include url.html%}/assets/img/cast/lineup-silhouette.png" alt="silhouettes of the main eight"/>
	<ul>{%for dn in page.dn%}<li><a href="{%include url.html%}/cast/{%if dn.url%}{{dn.url}}{%else%}{{dn.nm|downcase}}{%endif%}/designnotes" id="{{dn.id}}">{{dn.nm}}</a></li>{%endfor%}</ul>
</div>