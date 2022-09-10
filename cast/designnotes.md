---
layout: 1.1
title: character design notes

dn:
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
/*tried to do a hover thing like the 404 about, but with one (1) background image. It Did Not Work and I cba when this page will probably be wholesale replaced later, SO:*/ #nav{text-align:center; max-width:1793px; margin:0 auto;} #nav ul{list-style-type:none; padding:0; max-width:100%;} #nav li{display:inline-block;} #nav li::before{content:'▪';} #nav li:first-child::before{content:none;} #nav a{display:inline-block; padding:0 .25em; margin:0 .25em;}
	/*eh why not. colors picked at random from silhouettes unless lowercase*/ #j:hover,#j:active,#j:focus{color:#8C8865;} #kl:hover,#kl:active,#kl:focus{color:#936FA4;} #a:hover,#a:active,#a:focus{color:#D69449;} #c:hover,#c:active,#c:focus{color:#e5C6eb;} #g:hover,#g:active,#g:focus{color:#964E3C;} #d:hover,#d:active,#d:focus{color:#5fdae0;} #sq:hover,#sq:active,#sq:focus{color:#5B568F;} #wr:hover,#wr:active,#wr:focus{color:#f2eca5;}
/*eh close enough, cba to calculate widths either*/
@media only screen and (min-width:1200px){#nav a{padding:0 .5em; margin:0 .5em;}}
@media only screen and (min-width:1500px){#nav a{padding:0 1em; margin:0 1em;}}"
---
{%include figure.html img="designnotes" alt="Screenshot of a design note page, scrollbar included. Text has been somewhat obscured."%}

As based on [the 2021 wall of design notes]({%include url.html%}/gallery/designnotes), but separate, updated, and (ideally) vastly more readable.

<blockquote><details markdown="1"><summary><h2>notes on the design notes</h2> (repeated on each)</summary>{%include designnotes.md%}
</details></blockquote><!--fuckin baller https://stackoverflow.com/questions/15917463/embedding-markdown-in-jekyll-html, although the end tag is weird if it's not on its own line-->

Will probably revamp this page with silhouettes or something else fancy later. For now, pardon the redundancy with the cast pages.

<div id="nav">
	<img src="{%include url.html%}/assets/img/cast/lineup-silhouette.png" alt="silhouettes of the main eight"/>
	<ul>{%for dn in page.dn%}<li><a href="{%include url.html%}/cast/{%if dn.url%}{{dn.url}}{%else%}{{dn.nm|downcase}}{%endif%}/designnotes" id="{{dn.id}}">{{dn.nm}}</a></li>{%endfor%}</ul>
</div>

<!--also there is more where these came from but I *really* gotta figure out page organization here... trainwreck moments-->