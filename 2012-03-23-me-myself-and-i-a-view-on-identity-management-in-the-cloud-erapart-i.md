---
title: 'Me, Myself and I: A view on Identity Management in the Cloud Era–Part I'
author: Administrator
layout: post
date: 2012-03-23
url: /me-myself-and-i-a-view-on-identity-management-in-the-cloud-erapart-i/
categories:
  - Cloud
  - Identity Management
  - Security
tags:
  - '#cloud'
  - '#identitymanagement'
  - '#unicorns'

---
_Note from the Author: If you don’t like long post stop reading this one now._

**_Me,Myself and I: a definition of Identity Management_**

So what it is this Identity Management (IdM) thing and why I would care about if I am in the process of design the next, fantastic,hyper-technological cloud architecture?( And, just for the note, no matter if we are speaking about hybrid,public or private cloud). So, why I should care about it? Well, believe it or not you’ll have to face with this IdM thing at some point and somehow you’ll have to find a way to solve the “problem”, but, first of all, let’s define some basic concepts:

> **Identity Management**: Identity management refers to the representation and recognition of entities in computer networks (Jøsang, Fabre, Hay, Dalziel & Pope, 2005)
> 
> **Cloud Computing(short version):**Cloud Computing refers to both the applications delivered as services over the Internet and the hardware and systems software in the datacenters that provide those services. (Above the Clouds: A Berkley view of Cloud Computing) 
> 
> **Unicorn:**Unicorn is a legendary animal from European folklore that resembles a white horse with a large, pointed, spiraling horn projecting from its forehead, and sometimes a goat&#8217;s beard and cloven hooves.(Wikipedia)
> 
> **Plastic Doll (Sex Doll):**In this connection we may refer to fornicatory acts effected with artificial imitations of the human body, or of individual parts of that body. (Wikipedia)

No I’m not crazy, I know I just wrote&#160; a definition of a legendary animal and of a sexual toy but please let me explain better my point of view. 

**Me:**&#160; Basically who am I? This simple question require to drill down at&#160; the real core of the Identity Management dilemma that I am trying to describe here, so please, let me rephrase my above sentence: 

> <font color="#333333">how many of you exist? how many identities you “use” daily still continuing being you?</font>

The below image is a graphical illustration of&#160; a hypothetical you from the point of&#160; view of the “n” You that everybody use daily to access to various systems.

[<img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: inline; border-top-width: 0px; border-bottom-width: 0px; border-left-width: 0px; padding-top: 0px" title="IdMTree" border="0" alt="IdMTree" src="http://alfweb.com/blog/wp-content/uploads/2012/03/IdMTree_thumb.jpg" width="661" height="387" />][1]

<font size="1">Image 1. Identity Management Tree</font>

Let say you are who you said you are, so we may define you as:

> **_Me_** : where Me is your network account that allow you to access to your computer every morning when you sit at your office desk

You, as person, access to the local network and decide, for example, to check email; obviously for you (Me), it is irrelevant if this system is using your local credential or another through a specific method of authentication (I’ll discuss about this later), what you matter is just that at the very end of the authentication “trail” you are able to read your email.

Let describe the identity you are using to access to the corporate service as:

> **Me(1) to Me (1-n):** where the number of Me is directly related to the number of applications, services,systems you access using a different account.

Now&#160; Me is the main account and it represent you as Employee inside your Firm, so we may speak about You as

> Me = Employee&#160; Where Employee is (Person + Business Role)

As everybody here, you have a Business Role inside your Employer Organization and this Role allow you to access to specific data,services,systems. Your Role is related to other Roles and allow you to claim access to other information just because **“you are who you said you are”**. 

**Myself:** But what it&#160; is&#160; exactly a role? A Role is a definition, it is a way to “describe” the combination of multiple things and adapt it to a organization. 

> **Role samples:**
> 
> **IT Roles**: Users,Sys-Admins,
> 
> **Business Roles**:Account Payable, Account Receivable
> 
> **Business/IT Roles**: Auditors, Controllers, Administrators

So if the Role is a way to describe your position related to the system you are using we may said that you, as yourself, got not only multiple Identities but even multiple Roles inside your Employer Organization.

**I:** Basically you are always who you said you are but you are even other “yourself” related to your&#160; multiple roles and every combination of those two definition allow you to access to the various systems of your Employer. Confused? Okay let say that as long as the systems you&#160; are trying to connect recognize your main identity or the&#160; multiple Me(1 to n-1)you are using, probably you do not even notice this BIG mess of the multiple “Me”, solutions like Single-SignOn (SSO),&#160; express clearly the idea of “I am logged what I do care about how?”.

But is enough? Well, if you are still using system that are all “on-premises” so administered by&#160; your Employer IT Staff, with almost “no connection” with other providers you have almost total control on who access to your system, how , when and why.

This means that if an Auditor comes to you (as sysadmin) and ask for a report of who access to what, you are able to reply in few seconds (or minutes..or well if you are over the 2 hrs times give me a call, got the solution for you)

**The cloud dilemma:**I am not going to discuss about cloud from a technological point of view, so sit down and relax all, my point is what happen when my multiple Me are “in the cloud”?

**First paradigm: _“The audit not audible”:_** we said:

Me(Auth)={Me + Me(1to n-1)}/Roles

where the Roles able to define where I may access or may not are, obviously defined by my Organization. But we just said we are “on cloud” this means that based on the model I am using (IaaS, PaaS or Saas) there are many chances that some of the “Roles” are not defined by “myOrg” but from the provider from I am buying “the service”.

So we may say that my level of control (LoC) is similar to:

LoC=vR(myOrg) – vR(prvOrg)

where:

vR(myOrg) is the level of autonomy in manage Roles inside my organization 

vR(prvOrg) is the level of control of Roles in the provider organization

if, we set the level from 1 to 10, where 1 is the lower level and we consider the 3 cloud models of implementation we may assume that:

SaaS model: I do not have access at all to the Roles, since I simply use a software as a service, this means that my vR(prvOrg) probably is between 1 and 3. Example: Microsoft Office 365 and the role of Admin (is limited to the base management of the users)

PaaS model: as above, I have limited control on who may access to what, I may&#160; maybe control Roles inside the program if it allow me to create them but I do not have control on the Infrastructure stack. My vR(prvOrg) level probably is between 3 and 5.

IaaS model: I built my infrastructure and so I have definitely more control over it, my level of confidentiality is for sure over 5 but still have some “black spots” here and there that I cannot control. This not meant IaaS is better than SaaS and Paas models but only that offer a different angle and a better control in terms of risk management.

Yes I said risk management and not identity management cause this is the unicorn remember?

We said I want&#160; to be sure that **“Me”**&#160; and the **“Me(1 to n-1)”** are the key point of this post but I am “working” in a distributed (even geographically” enviroment called cloud, I access to the data from various systems:corporate computers,tablets,phones, kiosk, etc…

> Risk management is part of the way I manage me, myself and I.

<font color="#000000">in a more “academic” definition what I need to mitigate the risk that someone act like me I need:</font>

  * Be able to strongly authenticate in order to validate my multiple identity .
  * Access rights must be checked against cloud application&#8217;s access control policies.
  * All user interactions must be logged to ensure non-repudiation .
  * User accounts must be de-provisioned in a timely manner .
  * Dormant accounts must be identified and removed quickly .
  * Access permissions must be certified on a continuous basis.

so think about your cloud system, think about your cloud provider, the contract you just subscribed and think about the Auditor that just walked in and ask for a detailed report on who access to what.

The Unicorn start to become more defined isn&#8217;t it? The first big question is:

> how I may audit something it is not auditable by design?

the second question is:

> am I mitigating risk or I simply pretend to mitigate the real risk ?

&#160;

End of Part I

In the Part II I’ll describe the Unicorn, the efficiency vs. accuracy model and of course the plastic doll dilemma.

 [1]: http://alfweb.com/blog/wp-content/uploads/2012/03/IdMTree.jpg