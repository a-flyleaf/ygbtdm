---
layout: 1.1
title: about
---
A twitchy survivalist-wannabe warily pairs up with a suspiciously-careless girl in a thrilling, destructive hellscape.

{%include figure.html
	img="about-v0"
	alt="Comic panel featuring the two main characters. The smaller one, smiling, offers a handshake; the other is surprised."
%}

Website for a story-project-thing that spawned around early 2021. Rather than being published 100% as a traditional webcomic (see [a blog post from late 2021](https://a-flyleaf.github.io/blog/project-rambling#now-what) for rationale), the story presentation's being winged; between February and June 2022, a >300-image [colorscript]({%include url.html%}/story/colorscript) was completed, and as of August it's being fleshed out for publication proper.

> Content note: **Story contains mature themes.** There is no explicit gore or nudity. Art may feature body horror. Creator has chosen not to use more specific warnings.

For now, a majority of the site consists of [story-related art]({%include url.html%}/gallery). Major updates are noted on the [changelog]({%include url.html%}/changelog).

## on spoilers
If you want to read "blind," jumping right into the 2022 colorscript is the way to go---except it's not done yet.

Note that not every character is introduced within the first part, let alone by name; the cast and gallery pages, however, assume everyone is known. Proceed with however much caution seems appropriate.

That said, if I think something is especially significant, it'll be hidden; text is grayed out <span class="spoiler">like this</span>, and images are obscured like this:

{%include figure.html
	img="carless"
	alt="Should appear indecipherably blurry. Full caption below."
	caption="<p>If the image appears normal to you by default, your browser doesn’t support <a href='https://caniuse.com/css-filters' class='ext'>CSS filters</a>.</p>
		<details class='imgdesc'><summary>image description</summary>
		<p>Snippet from <a href='ygbtdm/gallery/roundups/2021-12'>a monthly art roundup</a>. On the top is a screenshot of an older version of this page, then titled “synopsis.” Continuing the screenshot is the header “in a sentence,” followed by “A twitchy survivalist-wannabe warily teams up with a suspiciously-carless girl in a thrilling, destructive hellscape.” To the side of the screenshot is a handwritten note: “sent this to a friend. made a typo.” and, in a smaller/faded note in all-caps, “<span style='text-transform:uppercase;'>I love writing</span>.”</p>
		<p>A crudely-rendered doodle below enlarges the typo, “suspiciously-carless.” One main character yells from a grocery store kiddie car, “<span style='text-transform:uppercase;'>Get in kiddo, we’re going karting.</span>” The smaller character says, more quietly, “I… have a license…”; declares the first: “<span style='text-transform:uppercase;'>Bullshit</span>”</p></details>"
	spoiler=""
%}

## technical notes
The spoiler functionality owes code nerd thanks to the following resources: <a href="https://stackoverflow.com/a/19075983" class="ext">StackOverflow</a>, <a href="https://www.w3schools.com/jsref/met_document_queryselector.asp" class="ext">w3schools</a>, and <a href="https://bobbyhadz.com/blog/javascript-addeventlistener-queryselectorall" class="ext">Borislav Hadzhiev</a>. Some caveats:

- Unfortunately this is **not keyboard-accessible**. I'm not familiar enough with JavaScript (yet) to change it.
	- In the mean time, you're welcome (and invited!) to lend a hand, if you'd like; <a href="https://github.com/a-flyleaf/ygbtdm" class="ext">the GitHub repository</a> is public, and/or you can <a href="https://a-flyleaf.github.io/about#contact" target="ext">contact me directly</a>.
- Toggling won't work at all if you're not using JavaScript. You can still read spoiler text by selecting or copy-pasting it, and images are perfectly viewable in new tabs.

Image captioning is hit or miss, as is character name consistency within. Most egregiously absent are captions on the roundups (lots of images *and* text throughout) and story pages (no clue what those are doing yet), but I'll figure out how to handle those eventually.

<a href="#header" class="skipto x">back to header</a>