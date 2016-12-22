---
title: 'BYOI (Bring Your Own Identity): The Relationship dilemma of the Frictionless IT'
author: Administrator
layout: post
date: 2015-11-20
url: /byoi-bring-your-own-identity-the-relationship-dilemma-of-the-frictionless-it/
categories:
  - BYOD
  - BYOI
  - Cloud
  - COPE
  - docker
  - Identity Management
  - Internet of Things
  - Unicorns
tags:
  - BYOI
  - context
  - idam
  - identity management IRM
  - relationship

---
[<img style="background-image: none; padding-top: 0px; padding-left: 0px; display: inline; padding-right: 0px; border: 0px;" title="ttech_articleblog_may19_644x300" src="http://alfweb.com/bg/wp-content/uploads/2015/11/ttech_articleblog_may19_644x300_thumb.jpg" alt="ttech_articleblog_may19_644x300" width="520" height="240" border="0" />][1]

&nbsp;

> Change means movement. Movement means friction. Only in the frictionless vacuum of a nonexistent abstract world can movement or change occur without that abrasive friction of conflict. &#8211; Saul Alinsky

I’m on a train toward Rome, it’s 6 in the morning few minutes ago an app just reminded me of couch and sear number, I’ve checked once again my calendar to evaluate (once more) the daily list of meetings, I’ve been suggested from the calendar to look a the best route to get to the places where I’ll meet customers.

All I’ve done was use one of the two opposable thumbs who make me so proud of be a “superior” homo sapiens sapiens and member of the club of the “sometimes I feel so dumb to depend on technology so much but hey it save me a lot of time…”.

As said I did all this things in a frictionless sequence of tap on the screen of my mobile, some of my action have already been synced back to my desktop equivalent apps, it’s what we call now “Frictionless IT”. I really love the term and really like the guy who basically invented it @giano (alias Alessandro Perilli). Trust me if you don’t follow the guy on twitter or do not read his blog ([www.alessandroperilli.com][2]) you should.

Now maybe it is ‘cause we’re both Italians, maybe ‘cause I have basically an empty slot in a winter (almost) morning waiting for a train that I went back to read a couple of articles written by him on what is “Frictionless IT”. Guess what? I started to place in context what he wrote. In the context of the digital identities.

The articles I’m referring to in this post may be found [here][3] and [here][4]. Let me quote one of them immediately so I’ll have the excuse to start properly this post.

> Frictionless IT is an enterprise IT that **just works**

First things first: what the hell does that means? Read again the first paragraph of this post and think about it. I had a frictionless UX , not a complete one thought since not all my apps are ready to be integrated one into each other and provide me a sort of holistic view of my day but almost there.

  * No need to think but simply be effective and operative on what I needed
  * Relevant information through the entire flow of actions I took
  * No extra distraction along this path

but wait.

This is not, or not completely my Enterprise IT but my _Personal IT_ . I’m a proud user of a BYOD set of things because of many reasons but mostly because I have not the same capability with the Enterprise “provided” tools.

I’m not going down the road of how we may build a Frictionless IT from a technology view, I’ve got my idea and the only one  “technology related” I want to share is that if, looking at the world as it is now I wonder how long I’ll have to wait before the Enterprise IT recognize the that there’s a bimodal approach to Frictionless IT who consider backends in cloud and microservice on agnostic device. Yes I’m talking about containers at device level, just look at docker and how may run now independently on Windows and Linux and think at scale (down to local devices) and you’ll got the picture of the possibilities.

Said that, I recognize that remove friction from monolithic world require a bit of more effort than simply stripe down the complexity of the technology layers.

I’ve explained in a previous [post][5] the concept of nuclear identities and how those provide a view of the relation between my persona and the digital identities that compose  the surrounding universe of my physical self. Now think for a moment to that concept and try to put it in the context of a  Frictionless IT.

@giano define three main ingredients to reach the Frictionless IT and those are:

  * Ease of use
  * Speed
  * Integration

I’ll re-use them from the identities perspective.

## Ease of use

From a technology perspective the user experience should be the quality indicator of the interaction  of the persona with the system but in,  if we take in account the concept of a Frictionless IT we have to consider two key aspects:

  * The identity may or may be not always the same even if the physical persona is the same
  * The system is not one but a multitude that will increase or decrease based on the context of application of the flow the identity will follow. In other words what I’m going to do after the first tap on the screen.

The UX is nothing else than the top of an iceberg who simply project his beauty in the sky of possibilities offered to a user but still is just the top not the iceberg itself.

[<img style="background-image: none; padding-top: 0px; padding-left: 0px; display: inline; padding-right: 0px; border: 0px;" title="square-shopping-1_610x430" src="http://alfweb.com/bg/wp-content/uploads/2015/11/square-shopping-1_610x430_thumb.jpg" alt="square-shopping-1_610x430" width="520" height="367" border="0" />][6]

Still, from a digital identity perspective we have to consider a couple of factors:

  * How I present myself in front of the application
  * Who will authorize me or how will I be authorized to continue through my hypothetical flow

It’s a classical use case of AuthN and AuthZ but require a couple of extra levels that  are:

  * Speed
  * Integration

We have, looking so far a firs statement that is:

> In a Frictionless IT the Enterprise Identities are only placeholder of the real digital identities and those exist out of the boundaries of the so-called Enterprise ecosystem

Ease of use doesn’t mean to consider all the aspect of a UX but provide the right set of capabilities (please not I carefully chosen to not write tools but capabilities and you should reflect on the subtle difference between these two words).

for a practical example of a correct use of a Frictionless IT UX look at FIDO alliance and the work these guys are doing  (here).

## Speed

Speed is, in my opinion often confused with simplicity.I may have to tap 20 times on a device and still have an overall UX that is quicker than a 3 steps flow. Speed is not about simplicity but about time reaction. In our world is usually seen as a technology enabler, if my backend is quick enough to provide the information&#8217;s in time, if my native or web app may cache some of the information I’ll have them quickly enough to be able to move to the next step in my flow.

But in a world of multiple identities Speed is nothing more than be able to provide the right context at the right time. In a word? cognitive.

Frictionless IT is a nirvana where everything is there ready to be used, the iceberg become larger and larger under the sea surface and consequently the need of a proper context is the only way to offer  the right level of data quality able to guarantee the right velocity to the persona flow.

Context is not static, by definition. Identities are not contextual agnostic but the opposite. The combination of both may be predicted? At some level yes and this capability tight itself deeply back to the Ease of use concept.

> In a Frictionless IT the capability of the Enterprise IT of open itself to external data and share/use them to define the right cognitive context to its personas will mark the difference between being relevant and irrelevant for its own users or in a better definition “internal customers”.

## Integration

This is my favorite topic but I use to not call it as such but with a different term.

Integration = Relationships

The actual lack of evolution in the classical approach of Enterprise Identity Access Management is the missing capability of recognizing the evolution of the digital identities and how those moved from single silos barely linked one to another to complex set of molecular relationships of digital identities.

These molecules is what I explained in my previous post “nuclear identities” and define the integration schema an Enterprise IT should follow. AuthN in a seamless way is maybe the most obvious way to provide it but again if we stop at that aspect we will hit only 10% of the entire iceberg. Integration is the overall picture who have to take in account that what matters is the context, the cognitive decision of a persona to use one tool against the other, the relevant decision to move that tool from a sporadic personal use to an Enterprise tool.

Integration is than the capability of recognize the relationships of the identities and the importance of them in terms of:

  * Attraction
  * Endurance
  * Inheritance

A Frictionless IT has to embrace the idea of a non-existent concept of BYOD or COPE or Shadow IT but of a holistic approach where the Enterprise IT accept to be educated by its own _internal customers_ in a constant learning path who has the final goal of remove the always more thinner separation between the internal and external digital walls.

> The relationships between the persona identities will guide the context of the information flow giving me the capability to be simply me.

 [1]: http://alfweb.com/bg/wp-content/uploads/2015/11/ttech_articleblog_may19_644x300.jpg
 [2]: http://www.alessandroperilli.com
 [3]: http://www.alessandroperilli.com/a-frictionless-experience-is-not-enough-if-its-all-there-is/
 [4]: https://www.redhat-cloudstrategy.com/towards-a-frictionless-it-whether-you-like-it-or-not/
 [5]: http://alfweb.com/bg/byoi-bring-you-own-identity-nuclear-identities/
 [6]: http://alfweb.com/bg/wp-content/uploads/2015/11/square-shopping-1_610x430.jpg