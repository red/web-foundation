---
title: 'So much to say, so little time'
date: 2018-09-18T01:01:17.000Z
author: Gregg Irwin
hero_type: image
hero_src: >-
  https://images.pexels.com/photos/993019/pexels-photo-993019.jpeg?auto=compress&cs=tinysrgb&h=650&w=940
category: update
tags:
  - ''
---
We know everyone is anxious for the 0.6.4 release with garbage collection and it is close. A couple of changes are being wrapped up on the RED wallet and then the final nails will be hammered in on 0.6.4. Thanks to @bitbegin and @qtxie for all their work in those areas.

It's amazing to have @dockimbel walk you through a log analysis and how some debugging was done for GC, inner details of func spec caching, and preview some features in the new GUI console. Even better, he walked me through them in person. That's right, he and @qtxie are here in the U.S. for a deep dive of business and technical work. The days are long, and the coffee is flowing, but we are Red-powered.

Thanks to @lucindamichele for getting the news flowing regularly, and now on to her weekly report.

## Last Week In Red

More of your input and questions go into documentation: this exchange on Gitter <https://gitter.im/red/help?at=5b9813e5728ddf02829371bc> prompted a further fleshing out of ways block elements can be accessed: (1) using slash and a numeric index; (2) treating the block as a key/value store (these in addition to originally defined comparative functions like `=, ==, <>, >, <, >=, &lt;=, =?`).

We also saw a number of fixes to the RED Wallet, making it even more stable and flexible in response to data entries. Transactions that are waiting in the pending pool can be edited with greater clarity and simplicity; the wallet now lets you review the amount and address of your transactions.

In Red's Garbage Collection, following the previous week's fixes, some new tests of object recycling were added.

The community project red.specs-public -- a guide to the syntax and semantics governing the language -- added the option to search the repository by datatype.

In his nimble diagramming tool, user @toomasv continues to expand its interactive capabilities, adding a layer for re-sizing of diagram data and further defining shapes.
