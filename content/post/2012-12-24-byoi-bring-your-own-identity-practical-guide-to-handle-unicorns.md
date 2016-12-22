---
title: 'BYOI (Bring Your Own Identity) : Practical guide to handle Unicorns'
author: Administrator
layout: post
date: 2012-12-24
url: /byoi-bring-your-own-identity-practical-guide-to-handle-unicorns/
categories:
  - BYOI
  - Cisco
  - Cloud
  - Identity Management
  - Quest
  - Security
  - Unicorns
  - Vmware
tags:
  - '#identitymanagement'
  - '#unicorns'
  - BYOI
  - cloud
  - engineersunplugged
  - identity management
  - infosec
  - Security

---
_BYOI is a series I’ve decided to create to “talk” about #identitymanagement so it is about #security, #governance, #management and many other aspects of the #IAM realm._

> The unicorn is a legendary animal from European folklore that resembles a white horse with a large, pointed, spiraling horn projecting from its forehead, and sometimes a goat&#8217;s beard and cloven hooves

wikipedia&#160; on “unicorn”

> Thinking outside the box (also thinking out of the box or thinking beyond the box) is to think differently, unconventionally, or from a new perspective. This phrase often refers to novel or creative thinking. The term is thought to derive from management consultants in the 1970s and 1980s challenging their clients to solve the "nine dots" puzzle, whose solution requires some lateral thinking.

wikipedia on “thinking outside the box”

My “home” office is a white wall, deliberately, it’s a white wall with nothing attached not because I’m a fanatic of “minimalist” or any other sort of fashion architecture flow but simply because it help me to focus and look beyond the boundaries where I found myself too often encapsulated.

This is a long post so before to embrace the reading I’m warning you.

The “unicorn” is a mythological animal so, by definition, cannot be “solved” but this is because we, as grown&#160; adults in a dichotomist world, tend to look at things only from our perspective that is a way to look at things in a “ black or white” way.&#160; I am not saying that everybody is like this and most of the “solution architects” or “engineers” our there are able to look at things from so many angles that the common definition of “scale of grey” could not even be applied since is too restrictive.

But, again, when you are too much focused on a single side of the “story” sometimes there’s not enough time to stop and look at the other side and discover that your “unicorn” is, sometimes, just a shiny “white horse” for someone else.

Few days ago my attention was catched by one of the, many (TOO many) great episodes of #engineersunplugged.

For those who don’t know what #engineersunplugged is :

  1. Shame on you! you illiterate go to [<font color="#3e372b"><em>this link</em></font>][1] and start to learn! 
  2. Double Shame on YOU! I tell you just: Cisco,VMware,EMC, everyone is there and share knowledge in few minutes in front of a white dashboard. 
  3. Triple Shame on YOU: you should already follow [<font color="#000000"><em>@CommsNinja</em></font>][2] consequently you should know everything about #engineersunplugged 

Seriously is a one of the best blog/idea I’ve ever see because still do what makes Information Technology a great field to work in: sharing knowledge for free and with a simple language that could be appreciated by the&#160; newbie and the expert.

As said my attention was catch by an specific episode where two friends [<font color="#000000"><em>@CloudofCaroline</em></font>][3] and [<font color="#000000"><em>@mreferre</em></font>][4] spoke about “unicorns” and “single pane of glass”. I could embed the video here but I think it’s more appropriate to encourage you to go to see the video directly on [_<font color="#000000">#engineersunplugged</font>_][5] (click on the link on the left) page and come back here.

So in the episode Caroline and Massimo explained the concept of “single pane of glass” even known as “unicorn”. As perfectly said (as always) by both it should be a “monster” who is able to manage almost everything from a single “point of view” and possibly without making difference of ecosystems whether they’re public,private,hybrid,”whateveritis” clouds or on-premises infrastructures.

The picture below show a better view of the result on the #engineersunplugged dashboard.

<img style="display: block; float: none; margin-left: auto; margin-right: auto" src="http://blogs.cisco.com/wp-content/uploads/caroline_massimo.jpg" width="496" height="372" />

[<font color="#000000"><em>#engineersunplugged</em></font>][5] &#8211; Engineers Unplugged (Episode 7): Halloween Edition Featuring Scary Architecture

### Meeting the Unicorn

A “unicorn” is something similar to this:

[<img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: block; float: none; border-top-width: 0px; border-bottom-width: 0px; margin-left: auto; border-left-width: 0px; margin-right: auto; padding-top: 0px" title="001" border="0" alt="001" src="http://alfweb.com/blog/wp-content/uploads/2012/12/001_thumb.jpg" width="516" height="479" />][6]

@CloudofCaroline & @mreferre “monster scary architecture”

The unicorn present itself as a complex architecture made by:

A first “layer” that is recognizable (the horse body) :

  * A layer made by different ecosystems like: 
      * On-Premises Infrastructures 
      * Private Cloud Infrastructures 
      * Public Cloud Infrastructures 
  * An API stack able to provide “connectors” to (but not only) : 
      * Services 
      * Applications 

A second “layer” (the mythological corn) composed by (and not only):

  * A SOA layer 
  * A SLDC layer 
  * An Orchestrator Component 
  * A Compliance(Certification/Attestation/Re-Certification) model 
  * An Automation component (CRUD activities of any kind) 

it is quite obvious that put togheter all these components and layers lead to a sort of “monster” that, even if able to manage them must do it not only with a single “horse body” but with _multiple_ “bodies” (aka heterogeneous ecosystems").

I’m not going to solving the unicorn providing any kind of advice on using a software vendor or another. My blog post only purpose is to provide a personal point of view and so, even if I can give the same answer as employer of a HW/SW vendor what I’ll try to do here is to be as possible “vendor-free”.

### To handle a Unicorn let it come close to you

So it is a “monster” and as every “monster” we are scary from them, we think we cannot handle them and we take them "at distance”.

> I trembled and my heart failed within me, when, on looking up, I saw by the light of the moon the daemon at the casement. A ghastly grin wrinkled his lips as he gazed on me, where I sat fulfilling the task which he had allotted to me. Yes, he had followed me in my travels; he had loitered in forests, hid himself in caves, or taken refuge in wide and desert heaths; and he now came to mark my progress and claim the fulfilment of my promise.

Frankenstein – Mary Shelley

At the beginning of this post I cited the definition of “thinking outside the box”, what&#160; make me shudder of surprise when I saw for the first time the “single pane of glass” episode was not that I saw the “unicorn” the way @mreferre and @CloudofCaroline saw it but that I didn’t see at all a “unicorn” neither a “monster” but a long time friend.

The “monster” it is only a “monster” to the eyes who don’t know it, think at the descriptions of whales made by various explores in history as example.

Below I redraw the unicorn from my point of view:

[<img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: block; float: none; border-top-width: 0px; border-bottom-width: 0px; margin-left: auto; border-left-width: 0px; margin-right: auto; padding-top: 0px" title="002" border="0" alt="002" src="http://alfweb.com/blog/wp-content/uploads/2012/12/002_thumb.jpg" width="529" height="396" />][7]

“Single Pane of glass” reviewed.

Let say for a moment (this not the way to handle the unicorn yet) that we can move the orchestrator in a “position” where can act as**&#160; bridge** between the **API stack** and the various ecosystems.

The **orchestrator** is made by a main component who manage the activity discriminating which_&#160; connector**&#160;**_or **sub-orchestrator** engage to complete the request made by the **actor**. The **actor** is an identity who have access to a single entity/ecosystems through a **role.**

<font color="#000000">The<strong>&#160; role</strong> define what the<strong>&#160; actor</strong> can request to the<strong>&#160; entity</strong> and doing so will trigger the<strong>&#160; orchestrator </strong>in order to fulfill the request. Unfortunately this is only a way to look at the “<em>unicorn” </em>that</font> obviously do not answer to our questions:

  * How I can handle the “_unicorn”?_ 
  * Does exist the “_unicorn” ****_and if so where I can find it? 

### Once the Unicorn is at your disposal let know each other

So you see the <font color="#000000"><em>Unicorn</em> near you now and you know that somehow if this <strong>orchestration</strong> process could be setup than you got a chance to handle the “monster”.</font>

<font color="#000000">The figure below represent a more complete view of the “<em>Unicorn handled”.</em></font>

[<img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: block; float: none; border-top-width: 0px; border-bottom-width: 0px; margin-left: auto; border-left-width: 0px; margin-right: auto; padding-top: 0px" title="003" border="0" alt="003" src="http://alfweb.com/blog/wp-content/uploads/2012/12/003_thumb.jpg" width="511" height="327" />][8]

_Unicorn unveiled diagram_

We spoke about a “_magic”_ **orchestrator** but as we even said was not enough to “handle” the “_Unicorn”_. So let see again the infrastructure we have:

  * The **Orchestrator** will take care of the so-called CRUD activities in terms of: 
      * Users 
      * Apps 
      * Infrastructure Layers 

This is the “main” **Orchestrator** who do now have nothing to share with “local” **orchestrator** based on the Provider/Customers ecosystems infrastructure. Those for the “_Unicorn"_ are just the terminal dot of a uni or bi-directional **connector**.

  * The **Workflow** layer who must satisfy: 
      * **Role** assignment/reconciliation fo the **actor**: in terms of who am I on the various ecosystems and what I can, consequently, do. 
      * **Policies** that must be matched in order to proceed in the request made by the**&#160; actor.** 
      * **Rules** that are directly or indirectly bound to the**&#160;&#160;** ecosystems **connectors** and that must be satisfy in order to trigger the “remote”**&#160; orchestrators.** 

The **Workflow** is far from being a complex schema of views, stored procedures or whatever you call it but simply an aggregator of instructions that dynamically evaluate every single request and decide upon it.

  * The **Compliance/Attestation/(Re) Certification** component must satisfy: 
      * **Compliance** of the request in terms of: **Role** of the**&#160; actor**,**&#160; coherence**&#160; of the request in the relation_&#160; who ask toward which ecosystem_<font color="#000000">, <strong>need</strong> of the request (in terms of evaluate the real-time metrics who allow a request to be made).</font> 
      * **Attestation/(Re) Certification** in terms of guarantee which**&#160; actors** may be in charge or express a request, to which ecosystems they have access, to which data, at which level, etc.. 
      * **Allowance**&#160; of specific connectors (SSO through Social logins, Access to Data in specific _silos**,CRUD** activities_ for custom Apps/Ecosystems,etc..). 

### On the existence of the Unicorn

So now if we look back at the last picture our _Unicorn**&#160;**_ is not anymore a “monster” but more a well-known “animal”. A long time friend who sometimes has been caught struggle in the IT realm because of it’s too much biz-alike models and that lately has seen to come more and more on the mouth of everyone as the “missing piece” of the IT story.

We draw the picture of the _Unicorn_ and we seen that can “easily” manage the&#160; “single pane of glass” but we still do not know how to call it.

IDasS or IDmasS ([<font color="#3e372b"><em>here</em></font>][9] for a definition of the name from Kim Cameron) it’s just a name but explain the architecture in many&#160; ways:

  * It can be _offered/received ****_from a on-premises or a cloud infrastructure since it manage both and the starting point is not the focus but instead the capacity to connecting dots (connectors through API stack). 
  * It is_&#160; heterogeneous ****_by definition because it not manage directly the ecosystems but relay on the “local” **orchestrators**. 
  * It acts as a junction point for the ecosystems since it’s main purpose is to aggregate the request and evaluate them in a way with regards of the : **rules,policies,boundaries** setup by the customer and the Service Provider. 

Should be, in other words, something similar&#160; to this:

[<img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: block; float: none; border-top-width: 0px; border-bottom-width: 0px; margin-left: auto; border-left-width: 0px; margin-right: auto; padding-top: 0px" title="Untitled" border="0" alt="Untitled" src="http://alfweb.com/blog/wp-content/uploads/2012/12/Untitled_thumb.jpg" width="521" height="342" />][10]

Hyper-view of an **actor** from the “_unicorn_” perspective.

To conclude the “single pane of glass” is far from be an “_Unicorn”_ and if it is far from being solved is not due the unknown definition of**&#160; what is is** but simply because sometimes we forget to look at things from different angles and perspectives. 

Thanks and Merry Xmas and Happy new year to those who inspired me in this post : [<font color="#3e372b"><em>@CloudofCaroline</em></font>][11], [_<font color="#3e372b">@mreferre</font>_][12] and [<font color="#000000"><em>@CommsNinja</em></font>][13]

 [1]: http://blogs.cisco.com/tag/engineers-unplugged/
 [2]: http://twitter.com/CommsNinja
 [3]: http://twitter.com/CloudOfCaroline
 [4]: http://twitter.com/mreferre
 [5]: http://blogs.cisco.com/datacenter/engineers-unplugged-episode-7-halloween-edition-featuring-scary-architecture/
 [6]: http://alfweb.com/blog/wp-content/uploads/2012/12/001.jpg
 [7]: http://alfweb.com/blog/wp-content/uploads/2012/12/002.jpg
 [8]: http://alfweb.com/blog/wp-content/uploads/2012/12/003.jpg
 [9]: http://www.identityblog.com/?p=1205
 [10]: http://alfweb.com/blog/wp-content/uploads/2012/12/Untitled.jpg
 [11]: https://twitter.com/cloudofcaroline
 [12]: https://twitter.com/mreferre
 [13]: https://twitter.com/commsninja