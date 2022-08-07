---
layout: 1.1
title: story outline colorscript-checklist
css: main{font-size:.85em; line-height:1.35;} h1{line-height:1.25;} section h2{font-weight:normal; font-size:1.25em;} section ul{list-style-type:none;} section ul>li{margin:.25em 0;} input{display:inline-block; margin-right:1em;} li p{display:inline;} input:checked + p{text-decoration:line-through; opacity:.5;}

eps:
  - title: "01: Relapse"
    scn:
    - prt: "intro/wakeup: ← wordless?"
      done: y
  - title: "02: Follow me"
  - title: "03: Not her"
  - title: "04: Lie in it"
  - title: "05: Desperately safe"
  - title: "06: So it goes"
  - title: "07: Despite everything"
  - title: "08: No one else"
  - title: "09: But you"
  - title: "10: You can't save her"
  - title: "11: I miss you"
---
This is only a page to make it less jarring on my eyes, and also for fancy list-styling purposes.

## side notes
- "intro/" = "cold open", title sequence after; else, assume title is at the very start (unless otherwise noted)
- scene titles are mainly for URL purposes, may or may not have "chapter" titles. not using numbers in case scenes get shuffled; much easier to relink folders/indexes
- arrows (→) indicate a new webpage

{%for ep in page.eps%}<section><h2>{{ep.title}}</h2><ul>{%for scn in ep.scn%}<li><input type="checkbox" class="task-list-item-checkbox" disabled="disabled"{%if scn.done%} checked="checked"{%endif%}>{{scn.prt|markdownify}}</li>{%endfor%}</ul></section>{%endfor%}

<!--

# 01: Relapse
- [x] <span>intro/wakeup: <-- wordless?</span>
- [ ] **title sequence?**
- [x] static: backstory montage ("My hero~")
- [ ] hollow: irl, fade to underground → callout x2 combo → apple
- [ ] yours: J+Kl first impressions
- [ ] challenge1: "No one has to die, right?" → up, panic ("Terry") → u-turn → escape
- [ ] out: J+KL leave, WR rises
- [ ] wrong-choice: J+KL talk → rabbit, gameover → null → J confronts KL
- [ ] deal1: WR joins the alliance
- [ ] together: J+KL evening

# 02: Follow me
- [ ] intro/deal2: camp → A>WR proposal
- [ ] start-over: J+KR trek, A+alliance? → Beacon meetup → rabbits interrupt → outta there
- [ ] listen: J+KL followup → alliance mockery, speech failure → A underground → monologue, "someone worth saving;" C
- [ ] left-behind: A+C talk → pendant → cave-in
- [ ] challenge2: loud

# 03: Not her
- [ ] challenge2: groups → entire game?
- [ ] scapegoat: interim → round2 → C accusations, G steps in
- [ ] watching: J/KL sendoff → J investigation, trip+fall
- [ ] dinner: C fauxpology → awkward, "Yeah, Kayla" etc. → spill
- [ ] slurry: <-- [ ] all that noise
- [ ] cornered: J+KL outside → J self-justification → C chasedown → C kill → KL has no personal space

# 04: Lie in it
- [ ] error: game/catchup → victory
- [ ] unsolicited: prizes, J "leaves" → G invitation → J crashes
- [ ] stutter: wakeup, bottle → failure to interact → G+KL, panic → J warning/admission
- [ ] found: J+D map talk, enter G → "Don't hurt her--"
- [ ] target: J>KL not-escape → near-fight → G sendoff

# 05: Desperately safe
- [ ] neurosis: J+KL argue/rabbit attack → recognition
- [ ] kindred: success → reconciliation, "Here's to being fucked up." → alas poor rabbit, shelter get
- [ ] too-close: J dissatisfied, sneaks out → quiet underground → G talk → letter → rabbits → cave-in → hand hold

# 06: So it goes
- [ ] intro/trying: despondent exercise
- [ ] haze: flashback x3 combo (meeting, smoke, proposal), scarce KL → KL snaps/returns/?out flashbacks (cheating, initial & montage)
- [ ] locked: flashback (lockout); KL cornered → J finds G → KL K-O'd → J triggers cave-in
	- imagining a tight back-and-forth here, not sure how the page division will go

# 07: Despite everything
- [ ] intro/alone: KL wakeup
- [ ] oddly-threatening: J+Sq → KL still alone
- [ ] liar: D reveal & banter, J crashes in →  KL confessional → "...Yeah. You do."
- [ ] and-yet: J (fake)out, D disappointed → double K-O → escape, monologue/hero sequence (flashback end)
- [ ] exposed: alliance, vulnerable moment

# 08: No one else
- [ ] intro/no: KL+E Beacon flashback → KL wakes up
	- "no" is redundant but idk what else to call this; "nonononono" is silly out of context & annoying to remember
- [ ] promise: J+KL catchup → J returns pendant, "Don't make promises you can't keep." → J leaves, voiceover into J+WR
- [ ] stronger: alliance outing → challenge split, panic → WR complies, celebration
- [ ] jubilant: campfire talk, KL off → KL pendant/rabbit story → J+KL sendoff/J suggestion
- [ ] silence: KL not there → "...Em?"

# 09: But you
- [ ] (no title sequence?)
- [ ] ghost: KL+WR → J confronts, g'night → KL+Sq → "They're gone."
- [ ] suffocating: KL>Sq threat → J+WR trackdown, E's perspective
- [ ] leave-her: KL>Seq frustration, WR break-in → WR+Sq/J+KL, rabbits → u-turn/cave-in (→ cliffhanger?)

# 10: You can't save her
- [ ] intro/again: Sq+WR → J wakes up, trail
- [ ] following: J loses trail, finds alliance → filled in, rabbits → left, pulled back in → D says hello
- [ ] idly: WR out? → D+J motive interrogation--"From what? Herself?"
	- not sure on title; thoughtless, autopilot, something to the effect of "just acting on instinct, not seriously considering the ramifications." not quite *careless* ~~carless lol~~ though, it's more subconscious
- [ ] persist: D+J voiceover/fade, J spiraling up; "Terrance is my deadbeat brother" → A → A pathetic, "You can't give up now" → mistake.jpg → enter WR
- [ ] savior: "I'm here to save you," J refuses → chasedown tango "This place... these *people* change you." → WR nearly kiled, J leaves; rabbit-smash, "Do you think you're a fucking hero?"
- [ ] apex: KL's been waiting → goal reveal (confirmation?), heroism taunting → J doesn't, KL threatens → J assesses → hug
	- kinda eh on the title but "peak" doesn't Sound right, "climax" is too on-the-nose
- [ ] fall: pendant toss, sorry → J leaves

# 11: I miss you
- [ ] (no intro?)
- [ ] awake: J rises, observes room → down the hall → door ajar
	- "rises, observes room" is such dry-ass phrasing but I know what I'm referring to and That's What Matters(TM)
- [ ] release: there she is → as J works, KL wants out → bright, wake up → alone; "Thank you...! And... good bye."
- [ ] choice: Sq+WR, "Was this worth it?", "You think I'll make it?" → "DON'T GO"
- [ ] neighbor: <-- [ ] that scene
- [ ] anew: sendoff montage/letter, fade to black
-->