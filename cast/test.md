---
layout: 1.1
title: gallery test
---
## specific tag
{%for art in site.gallery%}
{%if art.tags contains "j"%}
- {{art.title}}
{%endif%}
{%endfor%}

## all
{%for art in site.gallery%}
- {{art.title}} {%for tag in art.tags%}#{{tag}} {%endfor%}
{%endfor%}