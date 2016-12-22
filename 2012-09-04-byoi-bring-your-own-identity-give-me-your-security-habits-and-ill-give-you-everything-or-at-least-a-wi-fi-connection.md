---
title: 'BYOI (Bring Your Own Identity) : Give me your #security #habits and I’ll give you everything (or at least a Wi-fi connection)'
author: Administrator
layout: post
date: 2012-09-03
url: /byoi-bring-your-own-identity-give-me-your-security-habits-and-ill-give-you-everything-or-at-least-a-wi-fi-connection/
categories:
  - BYOI
  - Cloud
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

Following my last [post][1] I’m going to develop a little bit more the “predictive model” based on employee #security #habits. 

The idea of a model who may help a company&#160; to predict and, consequentially, avoid risks or thread, simply analyzing&#160; the #security #habits may sound, at first, as a sort of discriminating framework who simply dived&#160; those who are good from those who are bad.

The model anyway is not built for that, or anyway if correctly applied the idea beyond is to simply define a dynamic system of rules who may proactively protect the corporate resources from any kind of threat.

First of all then the basics, which are the rules or, better, how this rules must be developed. I remember when I was almost 16 y/o and literally fall down in love with “fuzzy logic”, in a world full of problems where the only solution was something set in a dichotomy solution I found myself lost in the “island” of the multiple choices and solutions.

For those who are not accustomed with the word “fuzzy” and less more “fuzzy logic” I’ll give you a simple example of how it works:

Let’s take the possible value of a simple combination of numbers 0 and&#160; 1,&#160; we will find out easily that the possible combination draw a square like the one below.

[<img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: block; float: none; border-top-width: 0px; border-bottom-width: 0px; margin-left: auto; border-left-width: 0px; margin-right: auto; padding-top: 0px" title="fuzzysquare" border="0" alt="fuzzysquare" src="http://alfweb.com/blog/wp-content/uploads/2012/09/fuzzysquare_thumb.jpg" width="358" height="314" />][2]&#160; 

Following the, so called, traditional logic this square have only four(4) solutions or couple of solution, (0,0),(1,0),(1,1),(0,1) and everything <u>must </u>follow accordingly.

But what if I want to know the value of the black spot at the center of the square, because it is a part of the square itself and so must have a value even if not relay on the perimeter where the values are known.

Traditional logic cannot help you in this but, so called “fuzzy” logic may,now following the same principles I’ve built the idea of the “level of #security #habits” framework.

Traditional risk management follow simple rules like:

  1. Identify the hazards 
  2. Decide who might be harmed and how 
  3. Evaluate the risks and decide on precaution 
  4. Record your findings and implement them 
  5. Review your assessment and update if necessary 

these kind of rules are the same we apply in the operation layer in a way similar to this:

  1. Identify the type of attack 
  2. Enforce perimeter protection systems with specific rules 
  3. Enforce inside&#160; policies to protect from specific threat (virus,data theft,etc..) 
  4. Analyze on scheduled basis the vulnerability of the system 
  5. Start again from number 1 

This simple sequence may be applied to many aspects of the modern IT environment and become much more complicated and fallacious when we move to “fuzzy” systems like, for example, cloud.

Why? because of the unpredictable type of attack in terms, of number of systems that may be attacked, location of the attack (more datacenter I build, more systems I get in, more heterogeneous is, more fallacious will be the overall protection system).&#160; 

I’ll not go into a discussion about intrusion detection systems or firewall systems but I’ll focus my post on risk management and, as said before, predictive analysis of the employee habits.

the usual risk management process follow&#160; a simple table like the one below:

[<img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: inline; border-top-width: 0px; border-bottom-width: 0px; border-left-width: 0px; padding-top: 0px" title="image" border="0" alt="image" src="http://alfweb.com/blog/wp-content/uploads/2012/09/image_thumb.png" width="525" height="583" />][3]

from “Risk Management Guide for Information Technology Systems” (<http://csrc.nist.gov/publications/nistpubs/800-30/sp800-30.pdf>)

You may see how the entire process is based on a crucial point: **identify the risk** but the point is, how you may identify something you don’t know?

BYOD is a sample of an unpredictable&#160; risk threat, because of the resource, I allow users to connect their owned devices to the corporate networks to make use of resources, data and application. From the company perspective this is often perceived as a way to improve productivity&#160; like [here][4] and [here][5],&#160; I strongly suggest you to read both and take notes of the last one where it says:

> ““There is an employee satisfaction piece to finishing an email on the train so you can spend more time with the wife and kids and dog at home though – it gives you an enhanced work/life balance, and it feels good to use a cool phone to get work done rather than carrying a large overweight [corporate] laptop” .. “
> 
> An extra layer of security is added because BYO devices are generally not allowed on the corporate network.
> 
> “You can download any app you want onto your phone but smartphones are a huge target for attacks – the phone doesn’t get onto our network,” he said.
> 
> “They can interact with the network, though. They can use the IM capabilities, interacting with an environment that looks like the network but isn’t.”

isn&#8217;t it funny? yes it is because what we just said is:

> I’m trying to figure out where the next attack will come and as response to this I’ll open an extra door to my corporate networks through something I cannot control completely like an owned device then to protect myself from this open door I restrict even more my rules.

Unfortunately you cannot predict what attackers will use and so, you cannot identify your potential threat that lead us to the very end that you’re going to fail in phase 1: identification.

You’re not yet convinced so, let’s do a recap:

I deploy a strict infrastructure that allow your owned device to run only in a sort of&#160; “limbo” where you may interact only through IM, email or other sort of things…well “things” that exchange info’s, email, im that goes to people that ARE inside your effective network.

now let’s pretend someone find a way to attack you through, a pdf, your strict systems would fail…isn’t it?

for the skeptics here’s the [article][6] about PDF wave.

So we easily demonstrate the classic model of risk management will fail when must face new infrastructure ecosystems like those build on BYOD or Cloud or anyway complex distributed data possibly dynamically dislocated.

What if the rule is dynamic in terms of allow the end user to built is own rules and match this rules based on corporate rules? Let’s pretend to built a real example:

  * User A decide to use his owned device into corporate network 
  * Company propose User A to fill in a request where he explain the use is going to make of the owned device within the corporate network 
  * User A fill in the request and choose between a set of rules who think may be applied to him in order to gain a correct level of security. 
  * Company define a mandatory set of rules that will be applied on top of the rules chosen by User A. 

so we have **cR** (company rules) that are mandatory and **uR**(user rules) that discretionally chosen by the user.

if we set a value&#160; **luS**(level of User Security) based on the simple sum of **cR** and **uR** where **uR** is evaluated on the average choice made by other users we may place User A in a&#160; quadrant.

this quadrant simply represent the potential habit of a user in terms of security toward the company resources.

so back to the “fuzzy” square we got:

**luS = cR + uR**

[<img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: block; float: none; border-top-width: 0px; border-bottom-width: 0px; margin-left: auto; border-left-width: 0px; margin-right: auto; padding-top: 0px" title="rulesquadrant" border="0" alt="rulesquadrant" src="http://alfweb.com/blog/wp-content/uploads/2012/09/rulesquadrant_thumb.jpg" width="389" height="341" />][7]&#160;

obviously it appears that as long we stay on the perimeter more easier will be exposed to a possible threat.

So how these rules may be applied dynamically? As said id a collaborative model so must be enforced somehow by both parties and again there are many way to do that.

One model could be the use of games, let say&#160; for example that I build a long set of rules and I award the user who apply them correctly as a way to recognize his/her loyalty&#160; toward the company.&#160; A user may build propose his/her own rules in order to be allow to use a specific company resource. 

For those who are blinking eyes now I would only remember that part of identity management is the use of self-service portal in order to get access to specific resources and so, why not, firewall/antivirus specific rules? 

so again we got luS that is now:

**luS= cR + (ucR +usR**)

where **ucR** are “user company Rules” made from the company but chosen by the user through a self-service portal and **usR** are “user self Rules” that are suggestion and requirement made by the user in order to be allow to use company resources.

now we are not anymore on the perimeter because our combination of **cR** and **uR** is made not anymore by 0 and 1 but 0 and something between 0.1and 1.0.

> We are now moving to the center.

But probably is not enough since even company must&#160; move in the same way, so again we need to redesign even the way corporate security design its rules.

Many new model come and one of the latest is Geotagging as a way to identify the position of an employee and decide if may or not may access to corporate resources.

I’ll post my ideas about that in a, next to come, post.

By now simply pretended we define for company a way to manage rules that is more similar to a business process than an IT process, where the rules are built by every single “actor” into the company and managed by the IT.

So now how **luS** is more similar to:

**luS = (cmR +cdR) + (ucR +usR)**

where **cmR** are the **mandatory** rules that the IT apply to the corporate ecosystem to protect the company from “common and known” type of attack and **cdR** are the **discretionally** Rules that every single Business Unit is allowed to submit to IT for evaluation and agreement.

The **cdR** obviously must be different and/or in case it is equal to a **uSR** request cannot be submitted by the same group of users.

So now we are in the center since we built a dynamic model that change month by month allowin company to enforce or release rules and protection systems based on user/company feeling…a sort of internal defcon level that could be applied discretionally.

 [1]: http://alfweb.com/blog/archives/142
 [2]: http://alfweb.com/blog/wp-content/uploads/2012/09/fuzzysquare.jpg
 [3]: http://alfweb.com/blog/wp-content/uploads/2012/09/image.png
 [4]: http://www.computerworlduk.com/news/mobile-wireless/3377143/byod-makes-employees-work-extra-20-hours-unpaid/
 [5]: http://www.theregister.co.uk/2012/08/31/byod_intel_productivity/
 [6]: http://www.computerworld.com/s/article/9175159/Researcher_warns_of_impending_PDF_attack_wave
 [7]: http://alfweb.com/blog/wp-content/uploads/2012/09/rulesquadrant.jpg