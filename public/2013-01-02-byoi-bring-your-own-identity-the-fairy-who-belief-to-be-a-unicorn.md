---
title: 'BYOI (Bring Your Own Identity) : The Fairy who belief to be a Unicorn'
author: Administrator
layout: post
date: 2013-01-02
url: /byoi-bring-your-own-identity-the-fairy-who-belief-to-be-a-unicorn/
categories:
  - BYOD
  - BYOI
  - COPE
  - Identity Management
  - Security
  - Unicorns
tags:
  - '#identitymanagement'
  - BYOD
  - BYOI
  - EMM
  - identity management
  - Security

---
_BYOI is a series I’ve decided to create to “talk” about #identitymanagement so it is about #security, #governance, #management and many other aspects of the #IAM realm._

Recently I’ve posted&#160; a”rant” on how&#160; an #identitymanagement solution may solve a “monster” Unicorn (_[<font color="#000000">here</font>][1]_), the intention was to demonstrate that what was called a “Unicorn” by some was something well known by others and so not a&#160; mythological animal at all. One of the comments I saw showed me anyway that trying to solve the Unicorn I was creating a more complex one or at least I could end up in a sort of “double Unicorn”.

The comment was this:

[<img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: block; float: none; border-top-width: 0px; border-bottom-width: 0px; margin-left: auto; border-left-width: 0px; margin-right: auto; padding-top: 0px" title="mas" border="0" alt="mas" src="http://alfweb.com/blog/wp-content/uploads/2013/01/mas_thumb.jpg" width="350" height="242" />][2]

The point is that often we saw things from different perspective and few weeks later I found myself again thinking at that comment and the different perspective we have of things.

I am part of a small group of people on twitter, we use to engage each other into “_totally random_” conversations around #mobile, #identity, etc.. I would say that we are basically like an ex-drugs addicted group with the only fact that we are far from be “ex-“ and definitely proud to be **addicted** to our conversation topics. 

In a recent conversation I saw a question about #idm and its relation toward #mobile, actually it was in the middle of a debate around EMM (Enterprise Mobile Management) and the use of it to protect/secure a personal/corporate device/user; the question obviously make my eyes blink immediately for two reasons:

  * It was simple&#160; but complex in the answer 
  * It was like if someone ask you “what color is green” and you found yourself unable to reply 

This is the question (and thanks to the “actors” in the tweet to be so inspirational to me):

**[<img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: block; float: none; border-top-width: 0px; border-bottom-width: 0px; margin-left: auto; border-left-width: 0px; margin-right: auto; padding-top: 0px" title="mam" border="0" alt="mam" src="http://alfweb.com/blog/wp-content/uploads/2013/01/mam_thumb.jpg" width="377" height="203" />][3]**

### Splitting the obvious

What is #idm and it is the right word to use in the context? Let see what was asked but let us try to introduce a context in it giving a short list of&#160; “_parameters_”:

  * Definition of a #mobile device 
  * Definition of _dual persona_ 
  * Definition of Enterprise vs Personal 

A #mobile device it is NOT a smartphone ONLY. A #mobile device is everything connected to a network and able to transmit or receive or both #data and that is not located&#160; always in the same place/position, examples are:

  * smartphones 
  * laptop (yes since you can use them **in** office and **out** of the office) 
  * Nike runner RFID transmitter (here) 
  * A cow (in some cases like here) 

With the terms of _dual_ _persona_ we mean , in a mobile management context,&#160; the provisioning and maintenance of two separate and independent end user environments on a single mobile device. Typically, the first environment is personal and the second one is for work. 

The difference between Enterprise and Personal is not a definition but the context where your digital identity belong to,if to the first or to the second one or, as worse case, to both at the same time.

So when we ask what #idm is we should ask:

  * What is#idm if I am using a#mobile device and I am in a context where I need to access to sensitive data with my Enterprise ID? 
  * What is #idm if am using a #mobile device and I am in a context where I am using two apps one for personal purposes and the other for business purposes? 

To simplify the reading let’s call these two question **#idm-E** and **#idm-P** where obviously E and P means Enterprise and Personal.

We have now a _context_ and a more clear question, even better we got multiple questions but, before to get back to them and provide a full answer we need to know ask ourselves some more questions like:

Is it #idm the correct acronym?

### The Basics of the Complexity

I have conversations about #identitymanagement everyday and I am always surprised how people technologically well schooled still confuse the terms and the meaning&#160; of it (and it is not related to the tweet conversation above in any form). So here’s my little tentative to explain a little bit better which term and to what it refer to:

**#idm is IDentity Management**: every CRUD (Create,Read,Update,Delete) activity related to a “_persona_” is under this name, even if it is normally related to information technology #IDM could be even something to a more physical and tangible process.&#160; It is related to an IDentity and the information&#8217;s this IDentity got and may _transmit,_&#160; think at yourself, you are an IDentity, a physical one but still one, your name, surname, age, weight, your address etc are all information’s related to your ID and you present them to others from time to time to _identify_ yourself (not authenticate but identify, see my other post for this _here_). Your twitter account creation was an #idm process.

**#idam is IDentity & Access Management:** if #idm manage the simple IDentity making no difference between an administrative and a personal IDentity the word “Access” give you a clear hint. The _dual persona_ concept is somewhat related to this realm even if #idam it’s not the correct acronym fot that. #idam it’s not only the way you manage an IDentity but how this one is provided with permissions, roles and authorizations processes to manage data,applications,infrastructures,etc&#8230; or simply login to “something”.The activation of the Twitter account you’re using was an #idam process.

**#idpam (mostly known as #pam) is IDentity & Privileged Account Management:** if #idm manage the CRUD activites for an IDentity and #idam take care of the way these IDentities access to the resources the #pam realm embrace every IDentity that need a “_special_” access, to re-uses a well-known defintion of #pam: “It’s to know not only who you said you are but who’s got the keys of the kingdom”. The_&#160; dual persona_&#160; concept is referred to this acronym but with a big difference: we are still speaking about the process to create and recognize the IDentity and in this case be sure that the “_administrative_” one got the right level of access to the resources. The&#160; account/key pair for the use of the twitter API in order to write an own application that can “push” information&#8217;s to Twitter is #pam process.

**#idgm (mostly known as #dgm) is IDentity Governance Management:** similar to #idam but it refer not to generic access but to data resources, it give you help in defining who (IDentity) may access to specific set or subset of data in your environment, through the analysis of the use of the resources (file share, application,local or remote network path) giving you an idea on how are used, from who, when, etc&#8230; Twitter does not have this kind of feature but Facebook clearly yes (let’s pretend my facebook notification systems advise me of a nice picture you just “shared” with “some friends” and I decide to publish it on Twitter…oh yeah already happened _here_).

Now that we know the basics we may try to look back at the questions:

  * **#idm-E** is in the #idam realm because it&#160; require the use of a specific IDentity who own a certain level of access, not necessarily administrative, to a network or to some set of data evaluated like sensitive. 
  * **#idm-P** could be in the realm of #idam and #pam or to the first one only for both cases: the personal app and the business app. 

### The Unicorn that is a Unicorn

I’ve already explained the Unicorn called #identitymanagement so it’s not my intention to get back to the definition itself but to add a further explanation of what it is a Unicorn.

A Unicorn in the Information Technology is something without a solution or at least that, seems, to not have an easy one:

  * _#ID* is not a DLP (Data Leak Protection) systems so can tell you which of your IDentity acess to what and how but, still, cannot save you from losing your own data_ 
  * _#ID* is not a IDS (Intrusion Detecting System) again can give you a report on your activity on the resources you have access to and/or share with others but will never stop someone to try to hack your networks boundaries_ 
  * _#ID\* is not a Risk Management Systems (RMS) can help you in the analysis of&#160; how the IDentities in your ecosystems use the resources but this is #governance not #riskmanagement to me. Through the knowledge of your environment you may build more precise models of #riskmanagement but it’s something you do pnly through the use of an #ID\* solution that provide #idgm capabilities._ 
  * _#ID\* is not an authentication system neither a way to provide rules for authentication. We use the information&#8217;s provided by the IDentity to control/match the authentication process between the two/multiple counterparts and in somecases to simplify the authentication process like we do through the extensive use of social single-sign-in these days, but again this is not #ID\* but Authentication._ 

So #ID* is a Unicorn because to solve all the questions related to an IDentity require more and more complexity that in some cases, like some “monster” heterogeneous architectures can lead to an _impossible_ solution. 

### The Fairy who thought to be a Unicorn

The difference is quite easy:

  * A Unicorn is something complex and that maybe can’t be solved with a single pane of glass (see my other post on _this_) 
  * A Fairy is something that cannot be solved not because of its complexity but simply because have no solution at all 

As we defined above #ID* is something we use to manage and add governance to the _persona’s_ so have nothing to spare with the device you’re using and or the fact that this device is #enable you to be #mobile or not. We gave a definition of #mobile as:

> Any device that could transmit,receive data or both of them to and from any network to which is connected

So this means that an IDentity is required only to guarantee that the data transmitted or received are:

  * Transmitted by the correct IDentity 
  * Received by the correct IDentity 
  * The information are exchanged upon a correct identification of the parties 
  * The IDentity who transmit the information can only access to a specific set or subset of data as defined by its role,position,definition in the target hierarchy 

The question come out quite easy:

_What an EMM got in common with all this?_

Yes an Enterprise Mobile Management (eco)system for sure include the management of the IDentities and their governance rules/policies but this not means that cannot exist without or that is made _only_ by it. Beside this we should look at the definition of an EMM system:

> Enterprise mobility management (EMM) is the set of people, processes and technology focused on managing the increasing array of mobile devices, wireless networks, and related services to enable broad use of mobile computing in a business context.

So EMM is a sort of “operational” risk management framework who act as a controller over the devices/users to prevent data breaches or failures. But is #ID* prepared to integrate itself in an EMM solution? The fairy would say “yes of course” but to be able to do that we must make some clear distinctions:

  * #ID* is not a security model neither a risk management model, can help both, the security and the risk management realms to work but it’s a total different story. 
  * #ID* is not about what is running on the #mobile device but is about #enable the user to use a specific applications because of its roles/position/policy set. 
  * #ID* is not about prevent unauthorized use of a specific application by any third party software but only, at very least, authenticate IDentities to #enable them to use those apps. 

This means that if we look at EMM and try to simply integrate any #ID* solution on the market _we only create a Unicorn that is, at the very end a Fairy_ and consequently got any solution if not to present multiple NOT-integrated tools that act as a solution through a nice dashboard and a some hundred of days of professional services to make it work in your environment.

> EMM becomes a fairy if limited to #ID* possibilities and/or MDM features but easily become a Unicorn if used to achieve a real control of applications and devices _without_ the #ID* solution.

To conclude to avoid the Fairy and stay away from Unicorns if you plan to setup a good EMM in your ecosystems remember always:

  * Users are not #mobile or #notmobile but simply users on systems 
  * Devices are any kind not only #mobile and must be considered as a whole stack of "technology” 
  * Acess a Data it’s not “more secure” just because it’s from _inside_ your corporate network 
  * the word #mobile means you actually have not always total control over the _dual persona_ (aka the USER) because it’s _out_ of your network 

Thanks to the #mobile group friends who inspired this post and&#160; for being such a pleasure in every tweeter conversations:

[<font color="#000000"><em>@bmkatz</em></font>][4]<font color="#000000"><em>, </em></font>[<font color="#000000"><em>@b52junebug</em></font>][5]<font color="#000000"><em>, </em></font>[<font color="#000000"><em>@swarnapodila</em></font>][6]

 [1]: http://alfweb.com/blog/archives/222
 [2]: http://alfweb.com/blog/wp-content/uploads/2013/01/mas.jpg
 [3]: http://alfweb.com/blog/wp-content/uploads/2013/01/mam.jpg
 [4]: http://twitter.com/bmkatz
 [5]: http://twitter.com/b52junebug
 [6]: http://twitter.com/swarnapodila