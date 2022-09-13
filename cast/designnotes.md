---
layout: 1.2
title: about the character design notes

chr:
  - id: j
    nm: Joce
  - id: kl
    nm: Kay Lin
    url: kay-lin
  - id: a
    nm: Addison
  - id: c
    nm: Caleb
  - id: g
    nm: Gary
  - id: d
    nm: “The accountant”
    url: the-accountant
  - id: sq
    nm: Sequitur
  - id: wr
    nm: “White Rabbit”
    url: white-rabbit

css: "figure{max-width:35rem;} blockquote{max-width:35rem; margin:0 auto; background:#efefef; color:#000; padding:1px 1em; font-family:'lucida sans',tahoma,sans-serif; font-size:.75em; line-height:1.65;} blockquote h2,blockquote strong{color:inherit;} blockquote h2{display:inline;} details{border:0; margin:0;} summary{padding-top:.5em;} summary:hover,summary:focus,summary:active{color:inherit; text-decoration-color:#b8b8b8;} hr{display:none;} blockquote ::selection{background:#b8b8b8;}
#cast img{opacity:0;} #cast a:active>img,#cast a:hover>img{opacity:1;}
.ni{color:#808080;}"
---
{%include figure.html img="designnotes" alt="Screenshot of a design note page, scrollbar included. Text has been somewhat obscured."%}

Based on [the 2021 wall of design notes]({%include url.html%}/gallery/designnotes), but separate, updated, and (ideally) vastly more readable.

<blockquote><details markdown="1"><summary><h2>notes on the design notes</h2> (repeated on each)</summary>{%include designnotes.md%}
</details></blockquote><!--fuckin baller https://stackoverflow.com/questions/15917463/embedding-markdown-in-jekyll-html, although the end tag is weird if it's not on its own line-->

This page will probably be revamped eventually. For now have the lineup again; these link directly to the design note pages.

<section class="artwall" id="cast">{%for chr in page.chr%}<a href="{%include url.html%}/cast/designnotes/{%if chr.url%}{{chr.url}}{%else%}{{chr.nm|downcase}}{%endif%}" id="{{chr.id}}"><img src="{%include url.html%}/assets/img/cast/{{chr.id}}-cast-slh.png" alt="{{chr.nm}}"/></a>{%endfor%}</section>