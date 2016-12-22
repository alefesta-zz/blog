---
title: 'BYOI (Bring Your Own Identity): The Unicorn revealed aka the Catch-22 rule'
author: Administrator
layout: post
date: 2012-12-19
url: /byoi-bring-your-own-identity-the-unicorn-revealed-aka-the-catch-22-rule/
categories:
  - BYOD
  - BYOI
  - Cloud
  - Identity Management
  - Quest
  - Security
tags:
  - '#identitymanagement'
  - BYOD
  - BYOI
  - identification
  - identity management
  - infosec
  - Security
  - social

---
_BYOI is a series I’ve decided to create to “talk” about #identitymanagement so it is about #security, #governance, #management and many other aspects of the #IAM realm._

> **There was only one catch and that was Catch-22**, which specified that a concern for one&#8217;s safety in the face of dangers that were real and immediate was the process of a rational mind. Orr was crazy and could be grounded. All he had to do was ask; and as soon as he did, he would no longer be crazy and would have to fly more missions. Orr would be crazy to fly more missions and sane if he didn&#8217;t, but if he were sane he had to fly them. If he flew them he was crazy and didn&#8217;t have to; but if he didn&#8217;t want to he was sane and had to. Yossarian was moved very deeply by the absolute simplicity of this clause of Catch-22 and let out a respectful whistle. (p. 56, ch. 5)

From the book “Catch-22” – Joseph Heller

### On What is an ID

Who are you? seems a silly question isn’t it, what it means after all “who am I ? “ but please give me credit on this and let me extend a little bit the question; so it is clear to everybody who we are, we are humans, men, women, single, married, divorced, employed,etc.. we are what we are based on a multiple set of experiences,errors,wrong&right decisions and so on. Yes we are complex and unique even if we are made of the same material or in other terms:

> Humans are characterized by having a large brain relative to body size, with a particularly well developed neocortex, prefrontal cortex and temporal lobes, making them capable of abstract reasoning, language, introspection, problem solving andculture through social learning. This mental capability, combined with an adaptation to bipedal locomotion that frees the hands for manipulating objects, has allowed humans to make far greater use of tools than any other living species on Earth. Humans are the only extant species known to build [fires][1] and cook their food, as well as the only known species to clothe themselves and create and use numerous other technologies and arts.

wikipedia definition of “human”

So and ID (identity) is the way we are recognized by others contextualizing the “momentum” .

[<img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: block; float: none; border-top-width: 0px; border-bottom-width: 0px; margin-left: auto; border-left-width: 0px; margin-right: auto; padding-top: 0px" title="human" border="0" alt="human" src="http://alfweb.com/blog/wp-content/uploads/2012/12/human_thumb.gif" width="506" height="508" />][2]

you don’t identify in your dog/cat or any other animal/object (well except your computer but that’s another story…) because they are not “like you”. You identify and get along well with others who got other IDentifiable&#160; signals like being an adult or listen the same music or hanging out at the same places, all these are form of IDentification.

_PhysicalID =I am who I am because of the sum of things I do,say,live,share, etc.._

We can so say that a physical ID is the result of what you do,think, are, but we live in a digital era don’t we?&#160; Most of us were born in an era where computers where quite different from now and where Internet didn’t exist&#160; as we know it (and not only that for the humoristic side click [<font color="#000000">here</font>][3] )so our “digitalID” was basically a converged model to our Physical ID, but what about today?.

A digital ID is defined as:

> Digital identity is a psychological identity that prevails in the domains of cyberspace, and is defined as a set of data that uniquely describes a person or a thing (sometimes referred to as subject or entity) and contains information about the subject&#8217;s relationships to other entities.

wikipedia on “digital identity”

Based on this statement the “convergence” between **me** as physiscalID (**pId**) and **me**&#160; as digitalID (**dID**) should stay in place if only:

  * If only I had a single **dID** and this could be associated in a uniquely way to my **pID** 
  * if only my multiple **dID** are related/correlated to **me** in a public and identifiable way 
  * if only&#160; my **dID**&#160; could be seen/perceived as part of a uniuqe (bigger and complex) **dID** directly related to my**&#160; pID** 

_Somehow all these “if” are true and somehow are false._

[<img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: block; float: none; border-top-width: 0px; border-bottom-width: 0px; margin-left: auto; border-left-width: 0px; margin-right: auto; padding-top: 0px" title="Presentation1" border="0" alt="Presentation1" src="http://alfweb.com/blog/wp-content/uploads/2012/12/Presentation1_thumb.gif" width="517" height="563" />][4]

Are TRUE because it’s always **me** no matter if the **dID** I’m creating/using is job or personal related and are FALSE because, as we all knows, the (as example) twitter account you create do not ask for a **pID** certification/attestation if you’re not a “public” V.I.P. and so there is no correlation between “that kind” of**&#160; dID**&#160; and you as**&#160; pID**.

### 

### The authentication process

We defined what is and ID and we are now aware of the difference between a **pID**&#160; and a **dID**, we also see, so far, that a **pID** is a sum of **dID** but that not “all the” **dID** could be related or are significant to our **dID**.

The challenge of a world “full” of **dID** is to provide a certain level of security/protection that could help an <font color="#000000">entity (<strong>enT</strong>) to identify the actor who is asking “permission to enter/use” its informations (in the form of applications,infrastucture,data).</font>

<font color="#000000">Let’s come back to our <strong>pID</strong> and consider a “usual”activity we (most of us) do every morning: driving our cars.</font>

[<img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: block; float: none; border-top-width: 0px; border-bottom-width: 0px; margin-left: auto; border-left-width: 0px; margin-right: auto; padding-top: 0px" title="key" border="0" alt="key" src="http://alfweb.com/blog/wp-content/uploads/2012/12/key_thumb.gif" width="486" height="324" />][5]

As a **pID** it is quite obvious I know which “application” I need (the car) when I start the process but this do not mitigate the risk that someone else could try to use the same “application”instead of me.

When I press the button on the remote control who disable the alarm I am authenticating myself already (first auth level). What I’m doing is to present my **pID** as the “**owner"**” of a specific information that only **me** and the **device/application/system** know and allow me to proceed to the next auth level.

_It is quite known that a simple frequency “sniffer” could replicate the signal and disable the alarm._

When I press the “second” button I open the “doors” and get into the “application”, this allow me to present myself ready to pass the final auth systems. I insert the key knowing that (or supposing that) only this particular “token” can start the engine.

_Like the frequency “cloner” even the key could be cloned or at least there are other ways of start the engine of a car._

That said what we have here is an identification process where through a&#160; multiple authentication system I am able to access to the data I want through the chosen application. Simple and effective isn’t it?

But when it comes to my **dID**? 

  * _First of all the authentication system is related to every single application/infrastructure and so could vary from one to another._ 
  * _Second the authentication system could or could **NOT** try to correlate itself with another **dID** or even more to your **pID**._ 

and it is even worse because of the proliferation of multiple **dID** we started to “federate” the systems.

It’ s a bit like to say that the “key” that disable the alarm and start the engine of the car is only the “common/social” system used by all the car owners. It’ s similar to all the car model owners but it’s uniquely related to my**&#160; pID** anyway to drive the car I need another “key” who may identify me as “driver”&#160; and it’s my driver license.

To add more complexity the driver license not only identify with my local “organization” but could be used as unique **ID** with other foreign “organizations” .

The license ID is a **FederatedID (fID)** and it is a **dID** that could be related uniquely to a set of **dID** who “should” lead to a **pID**.

### The Risk of not knowing

The unicorn start to appear isn&#8217;t it? The fact that **me** is in some case could be “federated” and related to my **pID** and in other cases could not (because of the personal use I do of that specific **dID**) makes difficult the use of a so-called “social” **dID** in a corporate ecosystem but in spite of everything we see a growing trend in this kind of auth/identification methodology.

Let me come back to the “driver” example, so you got the keys, the driver license and, supposedly, you’re able to drive but what do you still miss? Can’t speak for every country but for sure in Italy to drive a car you must apply for a&#160; form of assurance that cover at least damages suffered or inflicted. What is an assurance? it’s an elementary for of risk management where with the term “risk management” we mean:

  1. _Identify the hazards_ 
  2. _Decide who might be harmed and how_ 
  3. _Evaluate the risks and decide on precaution_ 
  4. _Record your findings and implement them_ 
  5. _Review your assessment and update if necessary_ 

and it’s applicable to the **pID** and the car example because the perimeter is well known and even the potential threats. It’s the result of many years of analysis on what may happen or not but our “**unicorn**” live in the digital era and here to work should&#160; know:

  * the potential threat based on a perfectly implemented security management of the multiple **dID** 
  * <font color="#000000">the correlation between the multiple <strong>dID</strong> the user have in control even those that are not directly related to the corporate <strong>dID</strong></font> 
  * <font color="#000000">the entire stack of security controls made by every single provider of <strong>dID</strong> involved in the process and how this is able to react to a threat.</font> 

<font color="#000000"><em>If the last one is probably the most easier to find out it depends on who is expected to place in act this control (see my previous </em><a href="http://alfweb.com/blog/archives/203"><font color="#000000"><em>post</em></font></a><em>).</em></font>

<font color="#000000">In other terms there is not a real risk management when it comes to multiple federated <strong>dID</strong> because of the lack of knowledge in terms of : experience, number of threats,regulation,technology used. </font>

<font color="#000000">What we may do (the unicorn) is to learn from our errors and try to develop a better model.</font>

### The Catch-22

So&#160; if we try to recap we are saying:

  * _The only way to avoid complexity in an multiple complex ecosystems “game” is to introduce a form of federation_ 
  * _To provide an acceptable level of security this form of federation must not expose information&#8217;s if not those that are relevant to guarantee the ability to authenticate the **dID**_ 
  * _The risk management should be able to guarantee that the federated systems is “threat-proven” or that could react to any threat even to those so-called&#160; “unknown” ._ 
  * _The risk management do not know if can guarantee the last point because of its lack of knowledge on the “new” model_ 
  * _The Federated login have consequentially potential security breaches because of the lack of information&#8217;s that the the risk management entity can provide to the ****<font color="#000000"><strong>pID</strong> that will use the <strong>dID</strong> authentication/identification system.</font>_ 
  * <font color="#000000"><em>The simplification of the complex ecosystems can lead to unknown results</em></font> 
  * <font color="#000000"><em>Without the simplification of the auth/ID ecosystems users (<strong>pID</strong>) would not be able to work in a profitable way&#160; (see consumerizations, mobility, cloud, etc..)</em></font> 

<font color="#000000">or in a simpler formula:</font>

> <font color="#000000">I cannot avoid the use of a social federate ID to sign-in into the corporate data but I would be crazy to allow to use this system because of the lack of #security #habits of the users in terms of managing the “public” <strong>dID</strong> against the way they “use” their “corporate” <strong>dID</strong>. It’s a catch-22 because if I (as corporate) do not use a federated sign-in systems I do not enable the user to work as they are asking me but if I do I am expose myself consciously.</font>

<font color="#000000">The unicorn is far from be solved but it is at least revealed and by now is a lovely catch-22 rule.</font>

 [1]: http://en.wikipedia.org/wiki/Fire
 [2]: http://alfweb.com/blog/wp-content/uploads/2012/12/human.gif
 [3]: http://johnsciacca.webs.com/apps/blog/show/5863790-born-around-1970-here-s-stuff-i-know-about-you-
 [4]: http://alfweb.com/blog/wp-content/uploads/2012/12/Presentation1.gif
 [5]: http://alfweb.com/blog/wp-content/uploads/2012/12/key.gif