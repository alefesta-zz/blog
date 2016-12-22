---
title: 'BYOI (Bring Your Own Identity) : Are you still driving in the fog?'
author: Administrator
layout: post
date: 2012-12-27
url: /byoi-bring-your-own-identity-are-you-still-driving-in-the-fog/
categories:
  - BYOD
  - BYOI
  - COPE
  - Identity Management
  - Security
tags:
  - BYOD
  - BYOI
  - cloud
  - COPE
  - IAM
  - identity management
  - Policy
  - Security

---
_BYOI is a series I’ve decided to create to “talk” about #identitymanagement so it is about #security, #governance, #management and many other aspects of the #IAM realm._

I drive a lot and when I say_ **a lot,**_ I mean over 1400Km per week. For those&#160; who don’t use kilometers means around 870 miles per week. and yes, I live in Italy, that means that even if you never believed that it’s a _“big”_ Country if you have to drive back and forth the whole northern area. 

Now, as every winter and as in many other countries, it comes the time for the fog and one have to drive for hours focused on the next hundred&#160; meters (110 yards around) trusting only on _his driving ability, his/her level of attention and that others on the road are doing the same_.

Yes driving in the fog <strike>sucks </strike>is stressful but if you look at it from a different angle could be more positive than expected (okay only if you got a blog on identity management and you’re geek enough to think at your job while driving…).

Let me start with a simple question:

> <font color="#333333">what makes so hard driving in the fog?</font>

if you thinking&#160; at it _**nothing**. Full stop._

  * Your driving skills? no changes 
  * Your usual level of attention? even more higher than daily average 
  * Your knowledge of the car behavior? no changes at all 

but even if nothing is changed the simply fact that your visibility is lower then expected makes a whole difference.

  * The road seems more narrowed than usual and I’m sure you may bet on it is the same road where you drive daily. 
  * the speed seems “_different”_ 60 miles are somewhat **slower** than when there’s a sunny day if there is nobody around but, as soon as you spot a couple of backlights in front of you the speed become **faster than usual.** 
  * You’re always in the feeling that something could happen, even if you’re on an highway and you can sport the backlight of the preceding car in front of you. 

for the curious readers who desire to know more about this here’s the _[<font color="#000000">link</font>][1]_

What I just said is that&#160; a simple variable like fog changes your _usual_&#160; way of driving&#160; and consequently makes you a total different driver. Your approach is different because your **“model”** is not **“mature”** enough to compensate the new variable with you’re actual knowledge of environment.

While the end of the year is approaching I saw a growing number of discussions about: #mobile, #identity,#mdm, #enabling users and so on. I participate personally in many tweet chats and discussion where we try to figure out, not only what will happen in the next year but how to “_approach”**&#160;**_ what we seen **this** year.

Let me then challenge you:

> <font color="#333333">what makes you a worst sys-admin,CISO,CIO,CTO, engineer than few years ago?</font>

Let me summarize it a bit:

  * **#COPE**: 
      * Type: Policy 
      * Applicable to: any Devices 
      * Purpose: allows an organization to source and deliver computing devices and services to employees and is how most organizations provide handheld or portable devices/gadgets to their employees. 
  * **#BYOD:** 
      * Type: Device Used in a Corporate Ecosystem 
      * Applicable to:any Device 
      * Purpose:is a business policy of employees bringing personally owned mobile devices to their place of work and using those devices to access privileged company resources such as email, file servers and databases as well as their personal applications and data 
  * **#MDM:** 
      * <font color="#000000">Type: Software</font> 
      * <font color="#000000">Applicable to: any Device</font> 
      * <font color="#000000">Purpose: secures, monitors, manages and supports mobile devices deployed across mobile operators, service providers and enterprises. MDM functionality typically includes over-the-air distribution of applications, data and configuration settings for all types of mobile devices, including mobile phones, smartphones, tablet computers, ruggedized mobile computers, mobile printers, mobile POS devices, etc.</font> 
  * <font color="#000000"><strong>#CLOUD:</strong></font> 
      * Type:Infrastructure/Ecosystem 
      * Applicable to: any Device 
      * Purpose:Cloud computing is the use of computing resources (hardware and software) that are delivered as a service over a network (typically the Internet). The name comes from the use of a cloud-shaped symbol as an abstraction for the complex infrastructure it contains in system diagrams. Cloud computing entrusts remote services with a user&#8217;s data, software and computation. 

We are then talking about:

  * _Networks_ 
  * _Software_ 
  * _Hardware_ 
  * _Application_ 
  * _Data_ 

All “**new stuff"**” isn’t it? We can spend hours discussing the best way to approach the “new new”. But, are we sure about that? Let me ask you again the same question:

> What makes you a worst sys-admin,CISO,CIO,CTO, engineer than few years ago?

This is taken from an article back in 2006, I using it to demonstrate my point:

> First, it concerns me how many computers used in both home and business environments are running with default settings for everything, just as the computer was when it came out of the box. Worse yet, most of these machines are connected to an &#8216;always-on&#8217; high speed Internet connection, or LAN, or both. Running with all the default settings may be the easy way to go, but it is not secure at all! Crackers and malware writers are counting on these types of settings.   
> Next, the sheer volume of ever-increasing Viruses, Worms, Trojans, Adware, Spyware and other malware assures that more and more users will encounter problems as time goes on. It is a simple mathematical certainty. Now that many crime organizations are thrown into the mix with great funding capabilities for their plans, the problem is constantly growing.   
> The problem for the average user is in not knowing where to begin or what to do. This article will guide you through the steps necessary to help you make a secure environment by “hardening” your Windows Operating System. I know the average computer user trusts that the default settings the computer ships with will be safe, but the truth is, it&#8217;s not! The use of third party software is a must. You will need a good firewall, anti-virus software and a few anti-spyware programs. 

For the curious readers- click _[<font color="#000000">here</font>][2]_

I’ll re-use the article to get even deeper in my thesis:

> First, it concerns me how many computers used in both home and business environments are running with default settings for everything, just as the computer was when it came out of the box. Worse yet, most of these machines are connected to an &#8216;always-on&#8217; high speed Internet connection, or LAN, or both

So in 2006 we were concerned that a device, connected to our network and to another network could harm our corporate ecosystem and consequentially we were trying to figure out what kind of policy was better to apply :

> This article will guide you through the steps necessary to help you make a secure environment by “hardening” your Windows Operating System

today we speak about how to secure a device so that could not harm our corporate data and we normally go for a “ _corporate driven policy” (#**COPE**)_ or a “_corporate imposed software control_” (#**MDM**).

In 2006 we were worried about :

> Running with all the default settings may be the easy way to go, but it is not secure at all! Crackers and malware writers are counting on these types of settings.

<font color="#000000">and</font>

> <font color="#000000"></font>The problem for the average user is in not knowing where to begin or what to do. 

<font color="#000000">Today we have to approach personal devices who not just “use” corporate data/apps but even personal data and if from the user perspective the use of a “<em>corporate imposed control system</em>” is not acceptable on the other hand the lack of #security #habits of the average user leave to many question marks to the corporate security requirements.</font>

My two cents on this:

> <font color="#333333">We must stop driving in the fog thinking that this is something different from what we normally do when it’s a sunny&#160; day.</font>

Let me explain better what I just wrote:

Our security models are**&#160; still right** and are**&#160; now wrong**.

Are **right** because even if from a technological point of view the 2006 networks got nothing to spare with a cloud network the “_bones"_” of the architecture are the same, the _principles_ are the same and so the applicable models, at their _bones_ must be the same.

As reference I’ve blogged and presented this approach already with the “the curious case of the cow , the cheese makers and the BYOD” (_[<font color="#000000">here</font>][3]_).

Are **wrong** because the **fog** require to evolve into a new model that require a better knowledge of the environment, of the behavior of the actors who are in the environment itself.

You know the car, you are confident about your driving skills and you accept a defined level of trust in the drivers who are riding in the same road of you, nevertheless you have to acquire more information&#8217;s that come only with the “maturity” of your model.

To conclude :

> <font color="#333333">Stop searching to re-build something that, not only already exist but even worst you already know and apply since years. The fog is a temporary phenomenon and probably it is already started to disappear in your ecosystem.</font>

 [1]: http://www.mpg.de/6605179/foggy-perception
 [2]: http://www.5starsupport.com/tutorial/hardening-windows.htm
 [3]: http://alfweb.com/blog/archives/176