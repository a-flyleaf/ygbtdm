---
layout: none

ep:
  - title: Relapse
    sum: start of story
    scn:
      - nm: the first
        desc: |-
          Lorem ipsum **dolor sit** amet. For god's sake *keep it short*.
  - title: end of thing
    sum: the part where it's over
    scn:
      - nm: Joce lets go.
        desc: |-
          Lorem ipsum **dolor sit** amet. For god's sake *keep it short*.
---
<!--<!doctype html> <-the markdown page is weird and does not like this-->
<html lang="en">
	<head>
		<title>aaaaaaaa</title>
		<style>
			*{box-sizing:border-box;}
			section{border:1px solid #808080;}
			#synopsis{color:#808080;}
			.scenes{overflow:auto;}
			.scn{border:1px dashed #808080; width:20em; float:left; margin:1em; padding:0 1em;}
		</style>
	</head>
	<body>
		<header>
			<h1>story outline 2, the faux-diagrammening</h1>
			<p>we are leaving this Ugly As Hell just for the sake of getting things down</p>
			<p>deliberately <strong>not</strong> referring to past notes both for the sake of TL;DRing it and to see how much I actually still remember, several story breaks later. (probably still a lot! but the rest, ¯\_(ツ)_/¯)</p>
		</header>
		
		<main>
			{%for ep in page.ep%}<section>
				<h2>{{ep.title}}</h2>
				<p id="synopsis">{{ep.sum}}</p>
				<div class="scenes">
					{%for scn in ep.scn%}<div class="scn">
						<h3>{{scn.nm}}</h3>
						{{scn.desc|markdownify}}
					</div>{%endfor%}
				</div>
			</section>{%endfor%}
		</main>
	</body>
</html>