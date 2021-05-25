---
permalink: /shortstonev2-app-vs-automate.html
---

**(This was a post from my old Wordpress site published on 2/14/21, it may be a bit out of date)**

<h1>ShortStone v2: App vs Automation<h1>
I waffled a lot on this in the initial post but this is going to be a bit more freeform now that it’s not tied to setup documentation. Hopefully you’re in for a little bit of a ramble. :)
<br>
<br>
ShortStone was a weird obsession borne out of both a deep interest in getting familiar with Shortcuts and doing something that’s less annoying to keep track of games with. 2020 was a great year for Hearthstone but no amount of features is going to make me happy to jump in and out of Hearthstone every game.
<br>
<br>
I strongly considered just biting the bullet and learning to make a simple iOS application, but there’s a mix of that being a tall order and simply just that what makes Trackstone clunky are the same mechanisms that any other app is going to run into; Shortcuts doesn’t have free reign by any means, but because it hooks into Apple’s OS you can leverage a lot of built-in functionality to work around UX issues
<br>
<br>
You may also be wondering; why is this v2 when there wasn’t really even a v1? To put it bluntly, my data structure for v1 was awful when it came to scaling and linking data points; you’d be able to associate wins and classes, but you couldn’t easily filter it down by date/season/patch and that felt like a major loss for being able to query how well you’re doing. Building a second version meant adding those fields and leaving room for new fields like deck archetype or game mode, and it’s easy to retroactively apply to existing entries
<br>
<br>
It’s been a lot of fun to make, and there’s quite a lot of features I’m excited to explore! Could something like Charty be used to make live dashboards? Could you take a screenshot of the victory/defeat screen and have ShortStone glean some information from that automatically? Is it possible to port this data into something like HDT to allow mobile to be useful even if most of your games happen on PC
<br>
<br>
There’s no telling where this will go and if Blizzard makes me irrelevant when they go live with things like their profile pages, but I’m excited to see if this can get to something that’s legitimately powerful. Through that process I’ll be trying to document solutions to some of the bigger problems and things like how to use the data in Data Jar alongside Shortcuts to generate things like a monthly digest of your wins and losses per class.
<br>
<br>
It’s going to be a good year. :)