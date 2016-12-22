---
title: 'BYOI (Bring Your Own Identity): You have my stick, I have your address'
author: Administrator
layout: post
date: 2012-09-02
url: /byoi-bring-your-own-identity-you-have-my-stick-i-have-your-address/
categories:
  - BYOI
  - Identity Management
  - Quest
  - Security
tags:
  - '#identitymanagement'
  - BYOD
  - BYOI
  - identity management
  - infosec
  - Security

---
_BYOI is a series I’ve decided to create to “talk” about #identitymanagement so it is about #security, #governance, #management and many other aspects of the #IAM realm._

__

__

This post start from an hilarious thread on Twitter between @CloudofCarloine, @mreferre and some others, their tweets where like the one below and I’ll refrain to make “easy” comments on that (maybe):

_[<img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: inline; border-top-width: 0px; border-bottom-width: 0px; border-left-width: 0px; padding-top: 0px" title="StickTweet" border="0" alt="StickTweet" src="http://alfweb.com/blog/wp-content/uploads/2012/09/StickTweet_thumb.jpg" width="513" height="284" />][1]_

Beside the hilarious thread I started to think (as always) at the way we manage security in terms of "#habits.

The case is quite usual: Let’s pretend someone find a USB key or any other “object” (will define this later) somewhere, let’s call this “source entity” (**sE**) and define a value for the object found like:

_**oF= pR *sEB**_

where **pR** is the _potential Risk_ based on a many factors like:

  * Actions Made to avoid harm in the process of analyze the object to get info&#8217;s about the owner 
  * Knowledge of the potential threat that could be triggered by the object (will give samples later in the post) 
  * Environment where the object was found and corresponding risks derived by the Enviroment 

and **sEB** is the _Source Entity Behavior_ that could be measured in a simple scale of three values:

  * Risky: when you simply do not nothing to protect yourself and “your” resources.
  * Medium Risky: when you relay on your security resources to “do your job” and simply trust in them enough to be confident there will be no harm.
  * Low Risky: you put in place all the actions needed to protect yourself knowing there is always a potential risk when your facing something that is, de facto, outside your total control.

So back to our Entity we may said that in case **sE** found an object **oF** should first evaluate&#160; the value of it in terms of potential threads, then compare this to his _level of acceptance of the risk_ (**leR**)&#160; where this last one can be expressed like:

**_leR= rA + sM_**

where **rA** is the level of _Risk Acceptance_ and **sM** are the _Security Measures_ the Entity already have settle up or that can use to protect himself/herself or other Entities.

**rA**&#160; is given by the effect that even in the case of **pR**&#160; is almost null and **sEB** is “Low Risky” something goes wrong.

**sM** is given by (again) **sEB** as:

  * **sE** use standard measures at his/her disposal (i.e.: antivirus on a device connected to a corporate network) 
  * **sE**&#160; standard measures plus extra measures (i.e. : same as before but the device is isolated from any network)

Now since we have the **oF** value and we have the **leR** value we may easily evaluate, in a sort of reverse engineering, the “**_level of Security Habits”_**&#160; that the Entity has.

**lSH= (oF/leR)**

lSH is a theorical value that everybody has and who is highly variable, not only in between single humans, but even for the same human if related to the different situations.

> **So the questions is lSH somehow predictable and eventually manageable in&#160; some way, can I evaluate a single Entity and through his evaluation be able to predict the behavior I expect from my Employees in terms of&#160; #security #habits?**

Let’s&#160; pretend we decide to use a scale for automatically evaluate #security #habits. To help us in this analysys let’s take two examples, one quite common (the @CloudofCaroline/@mreferre case ..let’s call it “The C-M case”) and the other quite “impressive” ,as you will see below, let’s call this one “The Choco Case”:

  * The C-M case:

> At a conference you find a USB key.

  * The Choco case:

> Someone offer you something in exchange of a piece of information (aka password or login username).

&#160;

Based on what just exposed let’s start to do “our math&#8217;s”:

**_The C-M case:_**

> **_lSH is null when sE find oF_**

This is the first step what we expect is that **sE** will start assign a value to **pR** (potential Risk derivate from multiple factors):

**oF** in our case is a USB key, means autorun is active on the device, any&#160; kind of information related to its content is available only if plugged to another eletronic device (owned o at disposal of the **sE**).

So we may say that **oF** get points already, now **sE** must evaluate the environment where **oF**&#160; was found. In this case it’s a public place (a conference or a train station or an airport or the common shared space in **sE** company).

here the evaluation is simple and complex at the same time, since what make the difference is the level of trust (**loE**) **sE** assign to the enviroment. I’ve already discussed in a previous post the **loE**&#160; and how this may lead to wrong assumpition sometimes.

Again from a #security perspective our **oF** get points again so we may already assume that we are in a&#160; situation where**&#160; sE** should already be in position to simply decide to not continue the evaluation on **oF**.&#160; Now as explained before in the evaluation criteria’s we have another factor related to the knowledge of the potential threat that **oF** may lead. 

This third parameter lead**&#160; sE**&#160; to introduce in his process **sEB** (source Entity Behavior): 

For those that are brave enough to leave this long post and read a “long” interlude before come back here I suggest:

[“Risk Aversion”][2] from wikipedia.com

> [“Risk aversion is the reluctance of a person to accept a bargain with an uncertain payoff rather than another bargain with a more certain, but possibly lower, expected payoff.”][3]

(and yes I’ve just challenged you did you took the risk?) 

so **sE** decide based on his/her **sEB**&#160; the best action to take, consequently add or decrease total point to**&#160; oF:**

  * **add points:i.e.:** Insert the USB key on a electronic device at disposal
  * **decrease points:** **i.e.:**decide to walk to an “information point” and leave the USB with all information&#8217;s that **sE**&#160; got.

We have now the **oF** value and we are, consequentially in the position to define the **leR** (level of acceptance of the Risk). This value is quite simple to find out since we simply add every single behavior of the**&#160; sE** till now.

So what is “your” **lSH** now? I’ll do my own math’s here:

  * **USB key** = 0.5 points on a scale from 0 to 2 where 0 is low risky and 2 is high risky
  * **Potential content of the USB key:** 1 since I have autorun disabled by default on my “resources” to avoid threat derivated from “unknown” devices plugged in. I accept the risk that this is not enough to protect if I plug the “unknown” device.
  * **Environment evaluation:**2 points in a scale from 0 to 2 where 0 is low risky. I do not care about where I am, if I find something and I do not have already infos about what it is and who is the owner I consider the object as potential dangerous to “me”.

so till now&#8217; the **pR** for me is at 3.5 out of 6 potential points.

Now what I should do, let say that instead of bringing back the USB to the closest information point and tweet/email a common “I’ve found an USB here and here at ..” I’ll take the risk and decide to plug the key into my computer:

**sEB** gets 0 points in a scale from 0 to 2, since I accept the risk but I put in place all the measures (where 2 is the most risky action one could take: i.e. plug without an AV active etc..)&#160; and get another point since, as usual, before plug in an “unknown” device I unplug my computer from any network (in this case is not 0 since I should double check the device with a portable and, just updated AV) 

So my**&#160; sEB** is 1 point and my**&#160; oF**&#160; is 3.5 (pR*sEB).

now my **leR** is 1 point (from **sEB**) less 0 since I do not do any extra “effort” to protect myself if not those I do every time and the finaly **oF**&#160; value is 3.5 (3.5 less 0 point (in a scale of –1 to 1) since I accept the risk but I protect myself enough)

At this point I’m able to calculate my **lSH**&#160; that is given by **oF**&#160; divided by**&#160; leR**. In my case is 3.5 on a scale from&#160; 0 to 13 where 0 is the maximum #security #habit

**_The Choco Case:_**

> Someone offer you something in exchange of a piece of information (aka password or login username).

I’ll not start to do again all the steps to not annoy the few that followed me till now, but in exchange I’ll share this story, not just because it’s true but even because show how the **lSH** of the people is lower that one may think.

[“Passwords revealed by sweet deal”][4] from a BBC news article of 2004.

The impressive point here is that those people failed in the early steps of the process:

  * **Enviroment:** a public place like a metro station
  * **Action Made to avoid threat**: nobody of them considered the action derived from sharing information with “unknown” entities.
  * **Acceptance of** risk: absolutely low, not only were sharing something strategic like a password or a username to someone but in a place where an, other someone, may take the information.

For those who are thinking _“well they simply told they would share ..actually they never really did or there’s no evidence that the shared information was the right one..”_ I suggest you to read:

[“Social Engineering: Eight Common Tactics”][5] from csoonline.com

I’m sorry for the long post, but please follow me in this last dissertation.

> The question was is lSH somehow predictable and eventually manageable in some way? Can I evaluate a single Entity and through his evaluation be able to predict the behavior I expect from my Employees in terms of #security #habits?

The answer is **yes** and **identity intelligence** is the answer to it, I call it identity intelligence since it is what we need to be able to use lSH in a governance model.

We used to approach risks from what we learned from **_risk management_** lessons:



  1. Identify the hazards
  2. Decide who might be harmed and how
  3. Evaluate the risks and decide on precaution
  4. Record your findings and implement them
  5. Review your assessment and update if necessary

> But this means we simply decide that the lsH of our employees is low and this&#160; explain why most of them would share a sensible data as their own password and login for a choco bar.

What if we build a model where the **sE (**source Entity) is evaluated based on his/her lSH? 

Let say for example that if a corporate allow its employees to use their owned devices and want to know the right level of control to apply to these owned devices could, for instance, ask to indicate this level to its employees.This is nothing more that a **lSH** process made from a company entity toward an unknown **oF** (the BYOD of employees).

We evaluate the enviroment (known is the **sE** enviroment), the action to be made (are the one we are asking to the**&#160; oF**), the **lsR** (we expect a threat at some point in time from one of this**&#160; oF**).

> **lSH** is simply the rules that the **oF** will set to protect not the**&#160; sE**&#160; but him/herself from a threat who damage the corporate networks (**sE**) and it’s started from his/her device (**BYOD**).

 [1]: http://alfweb.com/blog/wp-content/uploads/2012/09/StickTweet.jpg
 [2]: http://en.wikipedia.org/wiki/Risk_aversion
 [3]: http://en.wikipedia.org/wiki/Expected_value
 [4]: http://news.bbc.co.uk/2/hi/technology/3639679.stm
 [5]: http://www.csoonline.com/article/460135/social-engineering-eight-common-tactics