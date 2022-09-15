---
layout: none

ep:
  - title: Relapse
    sum: start of story
    parts:
      - nm: cold open/intro
        scn:
          - desc: Joce wakes up in the underground.
          - desc: Not 100% sold on there being an intro segment but I think it would be fun, both to establish/foreshadow character dynamics and because it changes as things happen.
      - nm: flashback sequence
        desc: Quick, vague, abstract. Fairytale-esque or wordless?
        scn:
          - desc: As a child, Joce engrossed herself in a franchise starring a hero to escape a tumultuous upbringing. Mixed messages about the roles of aggressor/hero/victim.
          - desc: Joce tried to position herself as a hero among peers, but no one listened. One person was attracted, dubbing her <i>"My hero"</i>. (Necklace bestowed.)
          - desc: But in the end, Joce was left alone.
      - nm: irl
        scn:
          - desc: Nowadays, Joce is an outcast by choice; takes unconventional routes, you never know when disaster will strike. Haunted by existential aimlessness.
          - desc: One rainy day Joce returns to a poster of her childhood hero in the trash. (Sprains her ankle double-taking.)
          - desc: Her housemates are "cleaning" her space as a birthday present, since she usually does stuff around the house unprompted. Joce tries very hard not to snap at them.
          - desc: On the way out, one housemate gives Joce her mail. Two letters, you know the drill. Ends with Joce framed by/looking up to the poster.
      - nm: first impressions
        desc: Parallel cut from Joce framed by the poster to Joce back in the underground, looking out.
        scn:
          - desc: Someone (Addison) is trying to talk to people, Joce included. Joce thinks she's grandstanding and doesn't answer her. But when the speaker calls on someone much smaller (Kay Lin), Joce takes notice.
          - desc: Someone (Sequitur) found food. Joce intimidates them. Very brief; cut abruptly.
          - desc: Joce offers the food to the girl. Basically [the comic](../gallery/firstimpressions); Joce stands around monologuing a bit, is surprised, Kay Lin's a med student, they handshake at the end.
          - desc: “No one has to die, right?” ← voice from the crowd. Cue earthquake.
      - nm: challenge 1
        desc: Follows immediately from previous with no break, exact cutoff not important.
        scn:
          - desc: Underground starts flooding, shrill noise, cue panic, yelling, "Terry" line at some point. Joce tries to stay with Kay Lin, who takes the outer spiral, but it starts collapsing too; Joce grabs Kay Lin and books it for the central structure.
          - desc: "Now climbing far behind the rest, Joce stays close behind Kay Lin. Then someone falls. (Minor detail: wearing a necklace.)"
          - desc: Immediately Joce panics. Kay Lin u-turns to help, incurring a penalty; she loses her grip.
          - desc: Joce catches her. Up they go, Kay Lin on Joce's back.
      - nm: inner Beacon
        scn:
          - desc: As the adrenaline fades, Joce has to admit that was fun. Then notices Kay Lin isn't there to hear it.
          - desc: Kay Lin's walking away; Joce confronts her. "Thanks for saving my life and all, but I wasn't really planning on sticking around."
          - desc: Joce insists Kay Lin won't survive on her own. Kay Lin hesitates, but ultimately follows. (Other people have supplies; as penalty for the u-turn, Joce and Kay Lin have none.)
          - desc: As they leave, a hand bursts from the ground, zombie-style.
      - nm: J+KL talk, rabbit encounter
        desc: Opens on the first good view of the Beacon exterior.
        scn:
          - desc: Joce tries to ask Kay Lin why she's here. Kay Lin wants Joce's motive first. Neither make much progress. Kay Lin asks about shelter; Joce insists they don't need it.
          - desc: Cue crying noise. Joce follows it; Kay Lin is wary, so Joce tells her to stay put and forges ahead alone.
          - desc: "The noise takes Joce to a dark crevice---from which, upon noticing her, bursts a rabbit. (Minor detail: it's being strangled by a necklace.) Brief chase, Joce doesn't stand a chance."
          - nm: <span style='text-transform:uppercase;'>Game Over</span>
            desc: "Two choices: <span style='text-transform:uppercase;'>“Quit”</span> is blank, <span style='text-transform:uppercase;'>“Continue”</span> proceeds to the next page."
          - desc: Joce wakes up and finds the rabbit semi-melted, nearby rocks cracked and oozing ~liquid. It's gross. (Necklace may be more apparent.) Someone's walking away.
          - desc: Joce catches up to Kay Lin and demands answers. First she caves and handwaves her own motive as not having anything better to do. *Then* Kay Lin says she's been here a long time and isn't sure why. (Slow, careful, choosing her words.)
          - desc: Dramatic beat. Then Joce makes a joke about Kay Lin being an NPC, and turns to leave. “Let's go find shelter.”
      - nm: meanwhile at the alliance
        desc: Setting unsure, possibly still at the Beacon & rewinding a bit? It's not dark yet.
        scn:
          - desc: Addison is alliance leader now and Caleb is clingy. Someone asks Addison about plans; cue scream from the crowd.
          - desc: “White Rabbit” steps forward. And doesn't talk, so Addison plays charades; WR wants to join. Addison is hesitant.
          - desc: "WR grabs Addison's bat, swings it, and nukes a rabbit lurking behind the crowd (that no one noticed). Left near-speechless, Addison approves: “Sold. Welcome aboard.”"
---
<!--<!doctype html> <-the markdown page is weird and does not like this-->
<html lang="en">
	<head>
		<title>aaaaaaaa</title>
		<style>
			*{box-sizing:border-box; background:#efefef;}
			section{border:1px solid #808080; max-width:85.25em; margin:1em 0;}
			.synopsis{color:#808080;}
			.part{margin-left:1em;}
			.scenes{display:flex; flex-wrap:wrap; margin:-.75em 0 .5em -.5em;}
			.scn{border:1px dashed #808080; width:20em; margin:.75em .5em; padding:0 1em;}
		</style>
	</head>
	<body>
		<header>
			<h1>story outline 2, the faux-diagrammening: tl;dr edition</h1>
			<p>ok got the giant rambledump out of my system mostly probably maybe, <em>this</em> time gonna try more scene-by-scene with minimal detail. jesus</p>
			<p>start to finish this time</p>
		</header>
		
		<main>
			{%for ep in page.ep%}<section>
				<h2>{{ep.title}}</h2>
				<div class="synopsis">{{ep.sum|markdownify}}</div>
				<div class="parts">
					{%for prt in ep.parts%}<div class="part">
						{%if prt.nm%}<hr><h3>{{prt.nm}}</h3>{%endif%}
						{%if prt.desc%}<div class="synopsis">{{prt.desc|markdownify}}</div>{%endif%}
						<div class="scenes">{%for scn in prt.scn%}<div class="scn">
							{%if scn.nm%}<h4>{{scn.nm}}</h4>{%endif%}
							{{scn.desc|markdownify}}
						</div>{%endfor%}<!--/scn--></div>
					</div>{%endfor%}<!--/prt-->
					{%if ep.note%}<small>{{ep.note|markdownify}}</small>{%endif%}
				</div>
			</section>{%endfor%}
		</main>
	</body>
</html>