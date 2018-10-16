---
title: 'A quick note, and recent updates'
date: 2018-09-10T20:02:07.000Z
author: Gregg Irwin
hero_type: image
category: update
---
It's been quiet here for a while, but busy as can be on the development and planning sides. We have new web sites ready to be filled with content, and all this blog content will transfer. On the PR side, Lucinda Knapp is helping us get organized, and get more regular announcements out. They'll be brief, recapping recent work and notes of interest from https://progress.red-lang.org/ as well as Gitter and other community channels.

We have a lot to talk about, and hope to do that soon. If we could just focus on development, things would be much easier. Our focus, as planned, is on the blockchain aspect and C3, but we still need to fill the gaps in the core to support that. And we have to build a business so it's sustainable. The token sale was a huge success but, in spite of that, we are subject/victim to crypto volatility. Do the math. Plans made in January had to be adjusted. Heck, plans made a week ago had to be adjusted. The token sale also came at a huge cost in other obligations. Things we might call distractions. It wasn't just "Here's a bunch of ETH, now go and do what you really want for a year." If only that were true.

There's a solid core team, support from about a dozen people in a semi-official capacity, and we have a great community. As an open source project, we live or die by that community. Otherwise we could just build what we want, and provide dev and consulting services around that. But we want to change the world. We want to help fix what is broken in software development, all while paying our own bills and eating regularly. To do that, we need you. Every little bit helps. While we need a couple more deep, experienced system-level coders (point them to us if you know any), almost anyone can contribute in some way. Reach out. Tell us what your skills are, what you're interested in, how you're using Red, or specific roadblocks you hit with it. "I need Full I/O" is not specific. 😶 Specific is important, because if you are trying to use it for something, that means you have needs and skills in that area. And you're probably not alone.

Our huge thanks to the community leaders, those working on tests and documentation, and experimental projects and research. There is a lot going on, and we're working hard to make things happen that are really worth announcing. 

Happy Reducing!

## Last Week in Red

New and notable in Red development: Numerous fixes in garbage collection, addressing crashes both with the recycling of red-symbol, and on macOS after allocating virtual memory. Quick-test.r saw a change, adding a precall. On the Docs side, the percent! datatype was committed by @gltewalt,
applying percent! to typesets number! and scalar!, and it has been added to SUMMARY.adoc.

And among Red community projects, Gritter, a Red Gitter client, has seen feature updates including the mapping of antecendent post-time periods."Starting to be useful," writes @rebolek. In an update to the README.md of OTP/ssword, @planetsizecpu notes that the otp generator is dependent upon
user selected parameters for its strength, meaning it's on the user to determine how strong that password is.
