---
layout: none

ep:
  - title: Relapse
    sum: start of story
    scn:
      - nm: the first
        desc: |-
          Lorem ipsum **dolor sit** amet. For god's sake *keep it short*.
  - title: near-end-of-thing
    sum: I am going backwards the episode count might change
    scn:
      - nm: The end
        desc: |-
          Joce steps backwards off the Beacon. Kay Lin falls to her knees; a rabbit looms behind her. Cut to black; game over, and Joce slams *quit*.
  - title: end of thing
    sum: the part where it's over
    scn:
      - nm: Joce wakes up again.
        desc: |-
          This time it's the room where she seems to have been physically kept the whole time; no trace of life, maybe surgical instruments around. The exit door is open---but a door opposite that is also cracked open.
      - nm: through the halls
        desc: |-
          Sterile, empty. Implicitly this is Joce's point of view (same aspect ratio?) but she's not shown directly. Follows a noise down to a door ajar; Kay Lin's room is fucked up.
      - nm: Kay Lin wants out
        desc: |-
          Kay Lin gives up; dying doesn't do anything, but she doesn't want to drive anyone else to their end ever again. Magic words are "I want to move on."
      - nm: Joce leaves Kay Lin
        desc: |-
          Kay Lin wakes up, stumbles out, sees something/someone. "Thank you! And... good bye." May or may not show Joce but the scene ends with the exit door closing.
      - nm: "Don't go"
        desc: |-
          Sequitur visits Em, asks if any of this was "worth it." Em insists there was no other choice, she would've never made it (couldn't be trusted?) on her own. Sequitur asks, "You think *I'll* make it?", and starts to walk out. Suddenly a rabbit looms; its teeth read "<em style="text-transform:uppercase;">Don't go</em>."
      - nm: Neighbor + letter
        desc: |-
          Rainy. Joce is outside gardening when the neighbor/housemate returns. Brief exchange like "you're out here in the rain wtf" "it's not that bad." There's another letter from S; implicit agreement that the neighbor tosses it, if they didn't offscreen already. Maybe compost? Might be better to show the Moment of Friendship; full conversation not necessary.
      - nm: Things are better.
        desc: |-
          Not perfect, but better. Specifics not necessary; the poster is gradually crowded by sentimental mementos from new experiences, then taken down entirely. There's still some trace of it, but it's not necessary.
      - nm: Joce lets go.
        desc: |-
          Joce disposes of the letter in some way---drops it off a bridge, composts it? Fade out on the thing dissolving, <i>fin.</i>
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
			.scn{border:1px dashed #808080; width:20em; float:left; margin:1em .5em; padding:0 1em; height:15em;}
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