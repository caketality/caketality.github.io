---
permalink: /shortstonev2-install-setup.html
---
**(This was a post from my old Wordpress site published on 2/14/21, it may be a bit out of date)**
<h1>ShortStone v2: Installation and Setup</h1>
I’ve typed and re-typed this a dozen times today, it’s a little too easy to get bogged down in why this monstrosity exists so I’m going to save that for a second separate post for people who just want to install it and let it rip. Even that’s a bit long winded so bear with me!

<h1>Before Starting</h1>
Anyone who’s been around tech for long enough is probably a little wary of what things are doing in the background, and I wanted to make sure to confirm that ShortStone has a single function that uses internet data; confirming what the current version of Hearthstone is according to the App Store.
<br></br>
Everything else is based on data local to your device, and there’s no plan for that to ever change if it can be helped. Feel free to browse through the actions listed in the Shortcut so see what each is doing, it’s excellent practice with Shortcuts in general and I tried to add brief explanations through comments to make it easier to parse.

<h1>Pre-Requisites</h1>
I tried my hardest to keep this list pretty short, but you’ll need to make sure you have the following before going any farther;
- A device running either iOS or iPadOS 14 or higher (13 might work but I can’t make any promises)
- Data Jar installed from the App Store
- Shortcuts installed from the App Store

<h1>Setting up Data Jar</h1>
In all honesty I should have just automated this by either baking it into the tool or building a separate tool that does all the setup, but in the meantime we just have to do a little manual setup in Data Jar to be able to start tracking wins.
<br></br>

1. Open Data Jar
2. Click Add Value; create a Dictionary with a key of ShortStone
3. Click on ShortStone
4. Click Add Value; create a List with a key of hsClassList
5. Click Add Value; create a Dictionary with a key of recordedGames
6. Click on hsClassList
7. Click Add Value; create a Text item with a value of Demon Hunter. Repeat for the other 9 classes!

<h1>Installing ShortStone</h1>
Shortcuts is a wonderful app but it’s a bit at odds with the security settings in iOS/iPadOS. Fortunately it’s a one time thing! The only unknown part of it is if you need to update manually to newer versions of ShortStone, but we can cross that bridge when we get there.
<br></br>

1. Open Shortcuts
2. Click through any prompts (I believe there are a few)
3. There should be some example Shortcuts, click on one to run it. Doesn’t matter which one, but the next step requires that you’ve run at least one Shortcut.
4. Go to Settings > Shortcuts > Allow Untrusted Shortcuts
5. Grab ShortStone from this link: https://www.icloud.com/shortcuts/9665dbbd32ab4056a819f7bf95a17f09
6. Run ShortStone once to get a feel for the prompts but you’re ready to start tracking games!

<h1>Making ShortStone Convenient</h1>
I’ve found a couple of ways to make it easy to record games, each of them being specific to the device I’m playing on (I play on iPad and iPhone based on whatever is more convenient at the time).
<br></br>
For iPad I just use Slide Over, it’s a little finicky but it’s worked well enough. If you’re not used to multitasking on an iPad, Apple has a KB article going over each one that sums it up well.
<br></br>
For iPhone I found that the back tap settings made it easy to pull up the prompts to enter the information from your game. If you go to Settings > Accessibility > Touch > Back Tap there is a choice between either double or triple tapping the back. From what I can tell it’s easier to activate the Shortcut with double tapping, but triple tapping has produced a lot less accidental activations. If you do start getting prompts pressing anywhere outside the prompt will cancel it without making any bogus entries.
<br></br>
A final, weirder, untested option is to use Siri to activate it. I haven’t found a way to use that one without looking like a complete dork.
<h1>In Closing...</h1>
I sincerely hope that this at least gives you a good springboard into tuning this Shortcut into something that makes it easier to record the data that matters most to you. I’m always happy to answer questions and get feedback on Twitter, and I’ll update this post with the follow up that has the reasoning and roadmap for features I want to add.
<br></br>
Thank you so much for reading and I hope you and yours are keeping safe deep in this pandemic.
