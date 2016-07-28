---
layout: post
title:  "Our top 5 software Design principles"
date:   2016-07-28 11:00:00 +0530
categories: architecture
---

So true, "*Simplicity is the soul of efficiency. —Austin Freeman (in The Eye of Osiris)*"

Firstly we totally believe architecture should be simple for long term sustenance. However architecture and design of any system is something that evolves and not necessarily get to desired state from start, key is keep the basics right and think both forward as well as what's done in the past.

Secondly, we as an industry pushing forward, reinventing the way that we build software and striving for craftsmanship at every turn. However sometime continually forgetting the good of the past, and teams are still failing on an alarmingly regular basis.

Apart from core principles like separation of concerns, single responsibility, principles of least knowledge, avoid repeats, avoid heavy upfront designing, etc.

We believe *architecture and design have to  be user centric* and not just how systems should be built. Here are some of the key software design goal and principles that we follow or aim to follow;

**Design for users**

We believe in making our lives difficult in designing user and system interfaces so we can make it as much easier for users of the system. And it is not just UI or UX but more holistic look at all the needs both online (all different interface including all or as much human senses possible) and offline.

[User-Centered Design](http://www.usabilityfirst.com/about-usability/introduction-to-user-centered-design/)

**Keep things simple and uncluttered**

Mantra of all time, however it is very true. And we believe this is very key. Keep it the way it should be follow patterns and re-usability principles, refactor as much to get to a state where one don't have to explain within the team on how the system works. Design by iteration, nothing new but people expects things to be spelt out upfront, well no one can predict if a piece of code will perform for thousands or for millions, so PoC, trying-n-testing can only prove things.

"*… with proper design, the features come cheaply. This approach is arduous, but continues to succeed.
—Dennis Ritchie*"

And when *Dennis* says proper design, it has to be progressive, iterative, thinking simple and keep resolving cluster or spaghettis.

[Keep it simple](https://www.interaction-design.org/literature/article/kiss-keep-it-simple-stupid-a-design-principle)

**Play to your strength**

Being techie we like playing with new and most of the time better way of doing things. But this may come with a cost of time and money. So play to your strength and start-off or base your architecture with software tools and frameworks that you know already, technology can be replaced with better and efficient ones as long as design is clear.

**Design expert sub-system & not master of none**

Design and build focused sub-system components and not with overlapping responsibility (not master of none) following the principles of single responsibility and don't repeat yourself.

Every component should own one specific and distinguished feature. It helps in defining the responsibilities clearly, helps the user to understand the system easily and also help in integration of component with other components.  And hence the piece of code should be implemented in one component only. It should not be repeated across the components.

**Asynchronous messaging interfaces**

Asych interfaces not only provide reliability but scalability and assurance. Abstraction among the layers is very important. Layers should be abstract from each other and this can be achieved by defining the interfaces for each layer to interact with each other and where possible Asynchronous interface so it helps in multiple aspects.

"*The ideal engineer is a composite … he is not a scientist, he is not a mathematician, he is not a sociologist, or a writer; but he may use the knowledge and techniques of any or all of these disciplines in solving engineering problems.
—N. W. Dougherty*"
