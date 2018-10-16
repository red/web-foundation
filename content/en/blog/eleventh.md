---
title: Weekly Recap
date: 2018-09-18T01:01:17.000Z
author: Lucinda Michele
hero_type: image
hero_src: >-
  https://images.pexels.com/photos/993019/pexels-photo-993019.jpeg?auto=compress&cs=tinysrgb&h=650&w=940
category: update
tags:
  - ''
---
A goodly part of our Fellowship of Red Magicians ("rogues" would be more alliterative, but I don't think they qualify) are cloistered in the wilds of Idaho, casting spells and muttering arcana over Red with more far-flung fellows. Right now, @dockimbel, @qxtie, @PeterWAWood and @greggirwin are
working magic on Garbage Collection, which has now been merged into the master branch. Debugging was a big challenge, and writing tests equally so. There are many subtle details that may not be intuitive, like the fact that series values don't shrink when items are removed. As you use the GC version, don't be too hasty to file bug reports. Confirm via community chat that you understand the expected behavior.

In red/docs, we're fleshing out our translations and adding more documentation of datatypes. In red.specs, @meijeru has expanded his discussion of the existing repertoire of errors to include ways the user can define errors for themselves. Meanwhile, @tovim's latest Czech translations have been added. And new descriptions of datatypes from @gltewalt have been placed here.

Your prize for reading down: We'll be at the Ethereum Devcon! See you in Prague, October 30 - November 2! Tickets were hard to come by, each wave selling out in less than a minute. We're excited to talk to core devs and tell them about Red/C3.

Regarding Issues, if you notice reproducible issues, please document them as thoroughly as possible on github. New issue #3541 was handled promptly by @dockimbel. #3536 observed that when 'make hash!' was applied to a value of which there were a very large number of looped interations, Red revs up the CPU usage and grinds away for quite a while before producing a result, so we've reviewed it and added it as a bug. Of interest also is #3530, in which @dsunanda observed some laggy movement when setting a panel as loose.

Answer our questions for the community, before it's too late! Go here. I'll be collating your responses this week. Thanks to everyone who's already added their voice, including @rebolek, @BeardPower, @dander, @codenoid, @ungaretti, a few guys named Alexander, and many more.

If I have missed something you'd like to know more about or if you have questions/concerns, please reach out to me: lucinda_red on twitter, or lucindamichele on most every other platform. Have a great week!
