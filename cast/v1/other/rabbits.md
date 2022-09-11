---
layout: 1.1
subpage: cast/v1/other
title: "“hellrabbits”"
---
The horrid humanoid monsters lurking throughout the setting. Like "[White Rabbit]({%include url.html%}/cast/white-rabbit)," characters may refer to them differently; this page title ≠ an official, universally-used moniker.

## characteristics
- Fully bony, humanoid from the neck down
- "Ears" grow from the back of the skull
- Lower jaw, which resembles cupped hands, may be split down the middle
- Vocalizations resemble a throaty, screaming sob
- Much, *much* larger than any human; can decapitate a person with a single bite
- Transformations vary, but full-rabbit individuals are indistinguishable
- Speculatively drawn to noise, but cause of attacks is unclear; some lunge on sight
- Seemingly vulnerable to the warm liquid substance throughout the setting, which can "melt" them like acid on contact
	- inspired by <a href="https://www.youtube.com/watch?v=GP0YTZmnhns" class="ext">the face-melting scene in <i>Raiders of the Lost Ark</i></a>
- Can also be killed by blunt force trauma

## episode appearances
There's not a single episode without at least one rabbit, lurking in the background or otherwise.<!--1: the fallen, WR / 2: Beacon attack, WR / 3: lurking in the bg mostly / 4: also lurking / 5: underground attack / 6: none :o but maybe in bg or talked about idk / 7: none but WR / 8: WR outing / 9: alliance attack, WR /  10: Addison, WR / 11: only WR-->

## author notes
- The story's had some ~zombie-esque mechanic from early on, but the rabbit motif was (initially) unintentional; the symbol on Sequitur's shirt reminded me of a rabbit, and it spiraled from there.
- Song association: "<a href="https://www.youtube.com/watch?v=WMOd6jz548Y" class="ext">Breezeblocks</a>"

<h2>gallery</h2><!--has to be manual; #gallery negates the wrap-->

<section id="gallery" class="artwall">{%for tn in site.gallery%}{%if tn.tags contains "rabbit"%}<a href="{%include url.html%}{%if tn.url contains 'roundup'%}/gallery/roundups/{{tn.slug}}{%else%}{{tn.permalink}}{%endif%}"{%if tn.url contains 'roundup'%} class="rn"{%endif%}><img src="{%include url.html%}/assets/img/gallery/{%if tn.url contains 'roundup'%}roundups/{{tn.slug}}{%else%}{%if tn.img%}{{tn.img}}{%else%}{{tn.date|date:'%Y-%m-%d'}}{%endif%}{%endif%}-tn.png" alt="{{tn.title}}"/></a>{%endif%}{%endfor%}</section>