---
title: BYOI (Bring Your Own Identity) :The puffy pastry
author: Administrator
layout: post
date: 2014-08-26
url: /byoi-bring-your-own-identity-the-puffy-pastry/
wp-to-buffer-success:
  - 1
categories:
  - BYOD
  - BYOI
  - Cloud
  - COPE
  - Identity Management
  - Security

---
> <p align="center">
>   cose che non ho, <br />cose che non avrei potuto avere mai, <br />e cose che non so, <br />le cose che non ho <br />sono ciò che sono e non chiedono scusa.
> </p>

<p align="center">
  subsonica – cose che non ho 2014
</p>

<p align="center">
  <a href="http://alfweb.com/bg/wp-content/uploads/2014/08/responsivevsmobilefirstwebdesign0221024x689.png"><img title="responsive-vs-mobile-first-webdesign-022-1024x689" style="border-top: 0px; border-right: 0px; border-bottom: 0px; border-left: 0px; display: inline" border="0" alt="responsive-vs-mobile-first-webdesign-022-1024x689" src="http://alfweb.com/bg/wp-content/uploads/2014/08/responsivevsmobilefirstwebdesign0221024x689_thumb.png" width="463" height="312" /></a>
</p>

What is more secure?

  * Your work place front door
  * Your computer
  * mobile first approach

Let say you have to assign 0 as less secure and 3 as most secure and give a vote to those tree options. Now stop look at the results and think how you evaluate them. I’ll tell you mines: 0,0,0 and at the same time 0,0,3.

Yes you read it well I gave a double vote but in any part of the previous sentences I said you can not. Like for security a static and rigid approach based on the evaluation of the “actual” potential threats a “single response” will lead to only one real result: FAILURE.

It is not that you’re not good enough to evaluate the risk but that the risk is not anymore static as it was before so “one evaluation and see you next audit” will not work anymore but let’s not divagate.

So I gave triple 0 and one 3 to the latter in the list and you should ask yourself is “why?” is so poor in protection that I do not trust them? Well somehow yes. First of all let me explain you my analysis: to me all of these three&#160; offer me a simple thing called “access”. In different ways: the door is a physical access,&#160; “mobile” access (where mobile is used to identify the capability to work anywhere,wherever I’d like to see “” on that), the computer is (still?) my primary working device. In different ways they offer me access to my job, enabling me to do it and so I expect that this access should be regulated and monitored as much as possible. 

> is it? honestly is it?

First things first so let see the front doors. I visit and visited offices everywhere and honestly even if I know that security works perfectly I know that after 10 or 15 times you visit the same building for the almost the same reason the so called “security-boundaries” start to become loose. Don’t get me wrong it is not everywhere simply for the majority of places. It’s a thing called “trust empathy”: I see you so often that I believe you’re a person of trust and so I let you get in more quickly (aka : the person you’re supposed to visit is not at its place when I try to reach him/her but I let you go in anyway).

Call it social engineer if you want I simply look at things the way they are, we’re human and we trust people based on the fact that “in the last 10 times this guys did not created issues and has a clean face”. 

The front door is a ZERO value since it is not the door itself or the security applied. The door simply give you access. It does not evaluate you as person neither define a risk index associated to your identity and correlate with the same index that comes from other front doors. 

> Give&#160; you ACCESS does not mean protect you or the “place” you’re going to visit in any sort of way. It simply means you are granted to enter based on who you said you are.

Door:0 – Bad guys:will continue to get in

The computer (laptop,desktop,etc..). Oh well I fell like shooting on the red cross here. 

Let me give you a simple list here and please tell me if it is in place at your place:

  * token auth (smart card, soft token)
  * 2FA (two factor authentication)
  * SSO (single-sign-on)
  * Encryption
  * VPN (yes even internally)
  * SSL inspection
  * NAC (Network access control)
  * Antivirus & Firewall (locally and with no rights to disables them)
  * Classification (as mandatory requirement)

if you are one of the few that got all these things “up and running” on their computers let me ask you again: are you secure? if you said yes then you just FAILED.

Okay,okay to be fair the level of protection related to the door is a little bit more higher in this case but still the same principle apply. Those things or at least the majority of them simply provide you a level of ACCESS. They enable you, they give you “credit” evaluating your “supposed” (before checked) Identity or information&#8217;s presented to the authentication provider in order to granting your access. But it’s again a separated process from “protection”. 

Related to 2FA and encryption I suggest you to look at “[http://thenewstack.io/dont-be-a-saas-hypochondriac/][1]” from Tal Klein (@virtualtal) while for the SSO or federation I simply let you think at chaos theory called “butterfly effect”.

> Butterfly effect: a simple flapping of the wings of a butterfly weeks earlier may produce a tornado weeks later

if I managed to get into your system with your credentials (I did not know your credentials but I actually logged in as you) what will stop me to get in any other application that in a transparent way will log me in? Single-Sign-On is there to make your life easier while granting that the credential used are still the one used in the very first place but again this is not about evaluation constantly who you said you are (well actually in some way yes but let say not so often or not in an adaptive way) neither is about applying some sort of analysis on you, as identity and your risk in using the next application.

VPN used internally in order to secure the channel as the SSL inspection related to it, well I bet I may count on the finger of a palm the companies that actually are using it, after all the “internal” network is secure isn’t it? 

You were granted ACCESS so now what on earth makes the difference? oh an by the way you’re using SSO application and a company registered device to access to “your” data so again what is going to stop you?

All this is “simply” about Manage IDentity (IDM) or better Identity ACCESS Management (IAM) or in a newer form IDentity Access Management (IDAM). It’s take in account the many identities your “physical” one is related in the ecosystem (your company network, the partner application you’re company&#160; is using,etc) define an almost infinite list of “rules”: compliance, certification,attestation, segregation,etc.

You define the relationship between these rules and the approval steps required to grant the .access to the target object (provisioning the credentials to the app and enable the end-user to use it). It’s about a “one way” process. A user is: provisioned, deprovisioned, disabled temporary, an access is modified based on a missed re-certification process.

It’s static and it’s not about evaluation related to what you do but only to “who you are and what you need to do your job”.

Identity Access Management is about that. Is about managing your (identities) access so the computer get a ZERO again since is not secure more or less than the front door of your office.

computer:0 – Bad guys: still gets in

And now the “mobile first approach”. Again first things first, you need the basics so please read “[http://www.ascrewsloose.com/2014/08/18/mobile-first-isnt-mobile-only/][2]” from Brian Katz (@bmkatz)

Mobile first has an issue to me that is very well explained by brian in this post “[http://www.ascrewsloose.com/2014/08/26/whos-on-first/][3]”

“The question is though, how does Infosec solve this Abbot and Costello problem for most companies. Abbot saying who’s on first and Infosec responding, yeah, who’s on first? The whole point of Infosec is to protect the data and make sure only the right people (identity) are able to get to the right data (access). The problem, which has yet to be addressed in most companies, is how to do this while following the same FUN principle that we used to design app experiences.”

yes you need to get in an extra level of identification with a mobile first approach, I say “identification” and not “authentication or authorization” on purpose. It’s not about granting you access but evaluating your actions. It’s about governance and this why I partially disagree with what Brian says in his post. yes IAM is needed since it’s a part of the process, to be fair it’s “basic” to the mobile first process. You need to enable user to have the freedom to work from anywhere, with everything they want (company devices, personal devices,etc..)and to do so you apply what Brian call the FUN (Focus on User) development approach. You have, anyway, to grant a certain level of security and this is don through many steps that must: grant the user is who said it is (Authentication), capability to use a second or a third application without the need to re-issue the credentials (SSO/Federation), enable the user to swtich from one device to another and continue to work (cross-session management) but..

This is about granting your the ACCESS to your data not protect them once you’re in. Mobile first need extra layers. Think at your apps like the puff pastry, if you look at it from outside it’s a single piece of pastry but if you cut it you’ll find many layers all separated but still tighten each other that makes that single pastry irresistible (if not I’ll share&#160; with you a couple of recipes and you’ll tell me…).

IAM give you access, the 2FA or any other strong authentication mechanism enable you to access to the data but it’s in the analisys of your behavior, in the way you use the data, from where, when, how, why that the protection reside.

so mobile first (actually) 0 – Bad guys (maybe harder life?):still get in.

mobile first means your IAM should adapt to that “first”. It’s not anymore about define the level of authentication and neither is about the way you are authorized (granting process) it’s about the way you behave always. IAG (identity access governance) is what has been introduced to cover the “hole” left from the IAM solutions after that the user has been correctly authroized to access the data. The governance is there to introduce more evaluation rules that consider not how you access but why you need that specific access and correlate this information to what you already have.

But we’re speaking about someone who is doing is job in a total new way. it’s about the incipit of this post : The things I don’t know are the things I never had..

Mobile first says “everything,everywhere,every time …and with the capability to use a mix of devices to do my job”. 

I, as IDAM specialist reply with a list of things you need:

  * FUN approach
  * IAM (SSO,Federation,etc..)
  * IAG (compliance,attestation,certification,etc..)
  * EMM (MDM, device management, call it whatever you like)
  * REE (Risk engine evaluation)
  * AAA(Adaptive Authentication and Authorization)

This makes your mobile first approach an irresistible puffy pastry and I bet the last two are missing right now but no worries I’ll write about both soon…

 [1]: http://thenewstack.io/dont-be-a-saas-hypochondriac/ "http://thenewstack.io/dont-be-a-saas-hypochondriac/"
 [2]: http://www.ascrewsloose.com/2014/08/18/mobile-first-isnt-mobile-only/ "http://www.ascrewsloose.com/2014/08/18/mobile-first-isnt-mobile-only/"
 [3]: http://www.ascrewsloose.com/2014/08/26/whos-on-first/ "http://www.ascrewsloose.com/2014/08/26/whos-on-first/"