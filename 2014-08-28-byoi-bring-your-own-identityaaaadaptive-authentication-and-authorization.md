---
title: BYOI (Bring Your Own Identity):AAA(Adaptive Authentication and Authorization)
author: Administrator
layout: post
date: 2014-08-28
url: /byoi-bring-your-own-identityaaaadaptive-authentication-and-authorization/
wp-to-buffer-success:
  - 1
categories:
  - Uncategorized

---
> <p align="center">
>   Fatta la legge, trovato l’inganno
> </p>

Italian way of saying (Done the law, found the workaround)

In my last post “[http://alfweb.com/bg/byoi-bring-your-own-identity-the-puffy-pastry/][1]” I described how the approach to “security” should be a&#160; multi-layered approach and I presented a “list” of&#160; “features” that should be implemented or considered in order to implement a good solution for a “mobile first” approach.

One of the things I inserted on the list was called “AAA”: Adaptive Authentication and Authorization. As promised in the previous post I’m writing this one to explain what I meant with that acronym.

First of all what Adaptive means. In today world seems that everyone is focused on two major things: 

  * the need of encrypt everything
  * the need of provide the easier way to use apps (read:SSO,federation,MFA)

All of sudden seems that everyone discovered that use company data over the network _could be_ dangerous if it is not encrypted end-to-end (that by the way is not always possible). To add even more_&#160; pressure_&#160; to this everyone got hypochondriac on the fact that most of the apps they’re using are on_&#160; the cloud_ (read with emphasis and a dramatic tone please).

On the other hand a more important topic comes more and more into the conversations :the usability of apps, especially those apps that should be used in a “mobile first” approach. It’s not only about usability or the way you login and maintain that access through other apps or through the same app but on different devices is simply about having a different set of them, focused on what you expect as end-user. Like my friend Brian Katz says (I’m writing a lot his name lately but it’s a sign of the respect I have for him and for his ideas) “FUN (Focus on Users Needs)”.

So we have two topics who generate a sort of friction sometimes: The need of more security in place and the need of more usability.

Just think at the capability of an app to recognize your connection status and “transfer” this status on another device to allow you to continue your work. From usability point of view it’s one of the things that put a smile on your face almost immediately. From a technical point of view it is something we already start to see but…well, from a security point of view:

  * how do I grant that you are still who you said you are on the second or third device?
  * how do I “pass” the authorization
  * how do I recognize the “authentication” that you have passed on the first device and allow you to re-use it on the second device?

> <p align="center">
>   in a word “NO THANKS”.
> </p>

[<img title="how-to-share-a-cookie" style="border-top: 0px; border-right: 0px; border-bottom: 0px; float: none; margin-left: auto; border-left: 0px; display: block; margin-right: auto" border="0" alt="how-to-share-a-cookie" src="http://alfweb.com/bg/wp-content/uploads/2014/08/howtoshareacookie_thumb.png" width="244" height="244" />][2] 

The friction will stay there..someone will go for the user needs, someone else for the security all around…we will continue to have conversations and discussions but nothing will change…ever.

Nah, that’s not the way things should go. I’m sorry I like to find solution to problems not the reverse. I use to say that “security is a habit” that means everyone should be responsible and everyone should be engaged in making things more secure, at any level.

So here’s the “use case”:

  * UserA connect to APP01 with&#160; DeviceA1
  * APP01 prompt UserA with two Authentication requests:
  * a token (soft token anyone?)
  * UserA social login (and if UserA is already signed-in than this part could be passed automatically)
  * UserA is presented to APP01 and:
  * VPN is started or requested
  * login is denied
  * login is accepted
  * login is subjected to a third validation (AD account?)

Why those last 4 cases? Since something played a role in the authentication process and decided upon it based on different rules.I’ll explain this later let us continue the use case (so we granted login to UserA in our case)

UserA need some data that stay on another device and for other reason I’ll not explain cannot be transferred on DeviceA1

  * UserA login on DeviceA2 using a token authentication
  * UserA open APP01
  * no Authentication is presented:
  * Login is denied
  * Login is granted
  * Login is subjected to an extra authentication process

  * APP01 present UserA the last status retrieved from the use of the application
  * UserA use the data need, close the DeviceA2 and return to Device A1 
  * The APP01 is updated with the data:
  * UserA cannot continue
  * UserA retrieve the status of APP01 only after an authorization process
  * UserA retrieve the last status update of APP01 and may complete the job

It appears like a simple flow and seems to work very well. UserA was subjected to restriction or granted to operate based on what seemed like a set of rules. A typical IAM scenario but with a tiny difference. It was applied not to the consequence of the action but to the status of the action. It means was adaptive based on some simply questions:

  * Who you are
  * What you are using
  * How you are using it
  * What you are using it associated with what you are already using

**Who you are:** the first time I have no choice on asking for your credentials but there are always smart way to do it right? Social login and soft token are both usable and secure for end users. The second time (second device) I relay on the security of the device itself if possible (smartphone to laptop equals social login to AD credentials) so I already know who you are and so I only need to check for the “second authentication level”. Again there are smart ways to do it so maybe I apply&#160; a combination of authentication at login (AD account&#160; plus token), re-use one of them (the token) and pass it to the credential store of the APP to check if I am still who I said I am.

**What you are using:** is not only about the device itself but is a combination of information&#8217;s: it’s the device a registered one within the company? Are you using the device from an “internal network” (VPN) or from outside (Geolocation/Device management etc..). I know you are who you said you are but it’s unlikely possible that you use your smartphone from US and the laptop from China at the same time isn’t it?And if you’re using a VPN on a first device I expect you’ll do on the second one so there will not be “false positives”.

**How you are using it:** Maybe it’s me and my unconditional love for cognitive sciences but I believe that if you’re going to authorize someone use your data a certain level of analysis on how this “one” is using them should be applied. In other words I’m okay let you use two devices for the same Application but I’m NOT okay to upload a file from one them since I have not control over what you’re doing (i.e.: I “see” you’re uploading the file starting from&#160; a file sharing cloud service like google drive or dropbox etc..). It’s about behavioral analysis and must be done in real-time. Adaptive means I adapt the rule based on the way you are going to use that rule.

**What you are using it associated with what you are already using:** Like I’ve just said mobile first doesn’t mean “everything in” means I select and grant access to my company data through many ways but still I apply a certain level of control. This is the most important case since you may decide to use a new device or new service to do your job and so I have to adapt myself. How? well this is about your #infosec approach I would not go for a “deny all” but for a “ask and explain”. 

So the triple A means you may decide to combine different technologies and different set of controls that relay to a sort of “single pane of glass” like a classical IAM/IAG solution.

Well not so classical after all since must be adaptable and be in a position to react working in synergy with other “actors”. Now my question is: does it exist? I’m not going to fool you..you know for who I work and would be really easy to write a “yes we can” but I play fair and I’ll say this.

So far I think nobody of us: IAM/IAG vendors has this capability. We may cover all the aspects but combine them in a single solution is a different story. I see at least two major issues in build what I’ve just described.

  * maturity of the authentication mechanism
  * Agent vs.. agentless approach (precision)

The first one is related to how to authenticate and how to combine the authentication metadata. The problem is that when we go for “external” providers we need to find a standard to use and which are the information we need to pass or to ask. It’s a longtime debate and will come to an end with a stable standard but still we are there discussing what is better to embrace and what is “died” or almost “died”.

The second one well is more about developers and what to use. HTML5 and latest web 3.0 technologies are helping a lot. Latest devices are more precise and consequently should be more easily to retrieve the information&#8217;s related to them in order to get position etc. Still we have an issue, vendors are not setting up a standard to interoperate between heterogeneous apps. What I would need from end user point of view is the capability of App01 to interoperate to App02. We do that integrating box, dropbox, google drive into “our” apps but not between them or at least we do that only for few of them. 

Why I should need this? Let say that instead of enable you to upload the files from box to your salesforce app what will be “shareable” will be the authentication credentials or the level of authorization within the company. I’m talking about IDaaS yes I am but this will be probably something to explain in other post. In this case having the capability to “share” authorization and authentication information&#8217;s and to use different set of them allow me to check who you are and what you’re doing more quickly and react if something “wrong” come along the path.

to conclude I trust you as end user but I’m an end user too and I know how quickly I forget the “basics” of security sometimes so let me “analyze you” in order to help you otherwise you’ll end up with what that old Italian way of saying:

> <p align="center">
>   Fatta la legge, trovato l’inganno
> </p>

 [1]: http://alfweb.com/bg/byoi-bring-your-own-identity-the-puffy-pastry/ "http://alfweb.com/bg/byoi-bring-your-own-identity-the-puffy-pastry/"
 [2]: http://alfweb.com/bg/wp-content/uploads/2014/08/howtoshareacookie.png