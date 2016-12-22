---
title: 'BYOI (Bring Your Own Identity) : Food doesn&#8217;t taste as good when you have no #data/#mobile/#goverance strategy'
author: Administrator
layout: post
date: 2013-01-07
url: /byoi-bring-your-own-identity-food-doesnt-taste-as-good-when-you-have-no-datamobilegoverance-strategy/
categories:
  - BYOD
  - BYOI
  - COPE
  - Identity Management
  - Security
tags:
  - '#identitymanagement'
  - BYOD
  - BYOI
  - dilemma
  - identity management
  - infosec
  - Security

---
_BYOI is a series I’ve decided to create to “talk” about #identitymanagement so it is about #security, #governance, #management and many other aspects of the #IAM realm._

<font color="#000000"></font>

What do you know about #BYOD, #ShadowIT, #Data? I’m sure everything or almost everything and so I expect you have a clear idea of what is going on in your ecosystem or at least a clear <strike>idea</strike> _#strategy_ on how to handle an un-governed information’s/devices/users. 

I said users on purpose because if there is a starting point that converge to an ending point when it comes to manage information’s, no matter if sensitive or not, for sure those are the users in our ecosystems.

From a technological point of view I’m sure everybody “here” knows how to protect the accidental (or not) data loss but my (personal) question is:

> Why this happen or better Do I need a #strategy that help me with variables I do not know at all?

I’ve already blogged about “unknown variables&#160; [<font color="#000000"><em>here</em></font>][1]&#160; and when it comes do _design a #strategy_ one of my first concerns is always:

> Can I predict something I do not know at all in terms of: behavior,existence,impact?

Let’s imagine you allow #BYOD in your company networks and discover that still,even if your policies are clear and “friendly” to users there is a certain number of “users” who introduce personal devices without declaring them. Could you handle this behavior? Basically the question would be:

> Can you really protect your company data when it comes to users and their bad habits? 

In my opinion?

<h1 align="left">
  No
</h1>

<p align="left">
  not sure I&#8217;ve been enough clear on this so I repeat it :
</p>

<p align="left">
  <em>No your technological policy driven #strategies cannot protect your ecosystems at 100%</em>
</p>

<p align="left">
  Why? Well for many reasons that, at the very end relay on a single “point” of failure:
</p>

<p align="left">
  <em>Users</em>
</p>

<p align="left">
  Let me convince you with a simple “real life” example:
</p>

> Of all the copy shops in all of England, Trudy Coughlan had the rotten luck of walking into Document Image Processing.
> 
> It was June 2007 in sleepy Surrey County, and Coughlan, a statuesque blonde, sauntered through the door of the shop holding a sheaf of 780 pages. Scan them onto two CDs, she told the clerk, a forgettable middle-aged guy in a forgettable office park in the middle of nowhere. Nothing strange about the order, unless you happened to be a Formula One fan and happened to take a close look at the material: schematic drawings, technical reports, pictures, and financial information — enough insider dope to design a Formula One race car. Each page was emblazoned with one of the most famous logos in the world: the prancing black horse of Ferrari….

Inside the Scandal That Rocked the Formula One Racing World &#8211; Wired Magazine (_[<font color="#000000">here</font>][2]_)

Long story short Ferrari Racing Team is one of the most protected environment of the globe and they guys there knows what they do for sure but as the story clearly explain there’s always room for a threat, a breach in your ultra-mega-security architecture.

So again _why this happen?_

> _Users_ are humans and as humans have a “predictable” behavior if&#160; encapsulated in specific perimeters. This not means you have to restrict them in a “small box” neither allow them to run “into the wild” of your ecosystems.

Let’s try to explain how your next #strategy must be built with a little metaphor:

let say you’re invited for a dinner and you have to bring your “own” wine, this means obviously that:

  * **a)** you can decide to drink the host dinner wine and do not taking anything 
  * **b)** take with you a wine bottle but still drink host dinner wine 
  * **c)** bring your wine with you and share it with others 

For **a)** and **b)** the subsequent questions will be:

  * What if I’ll not like the host dinner(**hD**) wine? 
  * What if the **hD** wine will not match the food and so I’ll end up with a bad dinner UX? 

In the case of **c)** the questions will be:

  * Should I bring an expansive wine to offer assuming that the purpose is to have the best dinner UX even if this means I am “paying” the higher cost ? (**hC**) 
  * Should I bring the cheapest wine hoping that **hD** wine is better then mine and so obtain the best dinner UX at the minimum cost for me?(**lC**) 

Of course there is a neutral response that means I’ll bring an “acceptable” wine for the sole reason of&#160; be polite and accept a “so and so” dinner user experience (UX).

Let’s analyze the options:

Let say for a moment that you are considering to bring your wine (I’ll see option a) and b) later) and have to decide for option **hC**&#160; or **lC**.

You’ll probably go for **hC** only if:

  * Your dining partners understand wine 
  * This is a repeated dinner and you already have an idea of the “level” of wine “shared” on by others in the past 
  * You think that host dinner wines are not at an acceptable level for you 

You’ll go for **lC** only if:

  * At the last dinner (if it is a repeated event) the wine selection didn’t satisfy you 
  * This is an isolated invitation and your host seems to do not know nothing about wine 
  * You don’t care at all about the possible experience to share with other at dinner and consequently wine tasting is not something you care about. 

Assuming you have a neutral position you’ll probably end up thinking at something similar to this formula:

**UX = (wS + fS +tS)** where:

  * **wS:** wine Selection&#160; made by you and others (host dinner) 
  * **fS:**food Selection made by host dinner and relative information shared with you in case you have to bring the wine 
  * **tS:** time Sharing in terms of topics discussed, etc.. 

But since the dinner have to come the **UX**&#160; is only expected and probably you’ll reduce your math to a simpler “algorithm” like:

  * It is a repeated dinner so I know the level of wine knowledge 
  * It is an isolated event and I have “choices” (my wine or dinner host wine) 

In this case you’ll end up with **hC** in the first case and **hC-1** in the second one because in both case you cannot risk to go for the cheapest selection and ruin **your** dinner over then others experience.

This theorem is called “Unscrupulous diner&#8217;s dilemma” :

> <font color="#666666">T</font>he situation imagined is that several individuals go out to eat, and prior to ordering they agree to split the check equally between all of them. Each individual must now choose whether to order the expensive or inexpensive dish. It is presupposed that the expensive dish is better than the cheaper, but not by enough to warrant paying the difference compared to eating alone. Each individual reasons that the expense they add to their bill by ordering the more expensive item is very small, and thus the improved dining experience is worth the money. However, every individual reasons this way and they all end up paying for the cost of the more expensive meal, which, by assumption, is worse for everyone than ordering and paying for the cheaper meal.

Wikipedia on “Unscrupulous diner&#8217;s dilemma”

Now let’s use imagine that our #strategy must embrace #BYOD so questions are:

  * _Do need my company enable #BYOD?_ 
  * _Would my users prefer a corporate device to a personal device?_ 
  * _Would my user still use their personal device without declaring them even if there is a policy that allow them for #BYOD?_ 

**Do need my company enable #BYOD?** If you don’t do it and your workforce is #mobile you have to assume that you’ll end up with :

  * _most of your #mobile users will start to use a “personal device” because help them to get their job done violating the security policies (the cheapest wine)_ 
  * _something will break into your network and you’ll not able to understand quickly what is it because you don’t have any kind of “management control” over personal devices (the host dinner offer the cheapest wine selection)_ 

**Would my users prefer a corporate device to a personal device?** Honestly it depends on the users, what you offer, what they “think” they need but I assume that:

  * _User will go for a #BYOD if company offer no mobile option at all or a very low level one (giving your users a mobile device is not enabling them for #mobility)_ 
  * _Users will stay with corporate devices/apps if those allow them to get their job done_ 

in both cases it depends on the “knowledge” of the users regarding corporate policies and “choices” (the expansive wine)

**Would my user still use their personal device without declaring them even if there is a policy that allow them for #BYOD?** Assuming not all your users got an “acceptable” knowledge of your #mobile #strategy you should have to accept that this will be the “best” choice for them even just because:

  * _They&#160; have not #security habits and so do not understand that bring a personal device “unknown” to the corporate IT department expose themselves and the company to possible data threats._ 
  * _They continue to perceive a “value” in use of they personal device on the corporate network even just for personal use._ 

Consequently our #strategy would say that:

Users will go for the highest selection in most of the cases exposing our corporate data to an higher risk unless we don’t provide them with:

  * an acceptable #mobile #strategy fully understandable by them 
  * a #strategy that support them with apps and devices that could be “acceptable” to users and perceived as a “value”for their job 
  * a dynamic strategy model that adapt itself to the users (design for #mobile users first) that can go along with the other “internal” policues (users are not always mobile) 

at the very end users will got for **hC** and so you have to provide them a **hC-1** solution aka “don’t be cheap on #mobile strategy”.

 [1]: http://alfweb.com/blog/archives/238
 [2]: http://www.wired.com/cars/coolwheels/magazine/16-06/ff_formulaone?currentPage=1