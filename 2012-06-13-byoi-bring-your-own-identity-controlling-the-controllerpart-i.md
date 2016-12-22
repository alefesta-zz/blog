---
title: 'BYOI (Bring Your Own Identity): Controlling the controller–Part I'
author: Administrator
layout: post
date: 2012-06-13
url: /byoi-bring-your-own-identity-controlling-the-controllerpart-i/
categories:
  - Life
tags:
  - '#identitymanagement'
  - BYOI
  - cloud
  - data
  - infosec

---
_BYOI is a series I’ve decided to create to “talk” about #identitymanagement so it is about #security, #governance, #management and many other aspects of the #IAM realm._

In the article [“Cloud, BYOD Increases Need for Automated IAM Systems”][1] of [_@ThorOlavsrud_][2]_&#160;_it was explained how the proliferation of the cloud services produce and increasing demand of control over the applications or, as better than me written by the author:

> As traditional security concepts of perimeter and end-point defense break down as a result of the proliferation of cloud services and the BYOD phenomenon, enterprises are increasingly feeling the need for greater control over access to applications. That&#8217;s where automated identity and access management comes in
> 
> &#160;

<font color="#000000">I totally agree with the article and I’ve already discussed in another post about the role of the IAM in the cloud models, basically it is clear that “moving” services from an (assumed) “local and controlled” ecosystem as it is (or should be) the “on-premises” realm to something “un-controlled” (from an auditing point of view) as could be the cloud either private or public, produce an increasing need of control over it.</font>

<font color="#000000">Just to avoid confusion, when I define cloud as “un-controlled” I mean the inability by who use the service to obtain a full audit of the entire infrastructure (not limited to the silos the customer work in).</font>

<font color="#000000">Now back to the purpose of this post, I am pondering which are the implication on “all this new” way of working, BYOD or Cloud Saas/Paas from an #identitymanagement perspective.</font>

> <font color="#000000">Let start defining the level of security first. When it comes of how to achieve control we use to think at two major areas of IT : antivirus and firewalls,&#160; those are in common opinion the way we manage “what, who, when and how our data are accessed or not”</font>

but we are talking here about a specific realm, something in fact that is _under_ our control but the world, as we know it, is made even by “things” that are not strictly adherent to this.

[<img style="background-image: none; border-bottom: 0px; border-left: 0px; padding-left: 0px; padding-right: 0px; display: inline; border-top: 0px; border-right: 0px; padding-top: 0px" title="SecurityScale" border="0" alt="SecurityScale" src="http://alfweb.com/blog/wp-content/uploads/2012/06/SecurityScale_thumb.jpg" width="527" height="191" />][3]&#160;

Fig.1: Auditable Security scale

The scale represent a visual aid to understand what I mean with “controlling the controller”, let’s start from the left:

**_BYOD:_** A company allow it’s employees to bring their owned devices and connect them to the corporate network, does it sound familiar to you isn’t it? Now the simple explanation to this is **BYOD = lowering cost of IT = increase productivity** for mobile users&#160; (how many of you check corporate email from personal device on Sunday..just ‘cause you can?) but…

> Questions:
> 
> **Q1:how do you guarantee that the device attached to the corporate network is secure?**
> 
> **Q2: how do you provide access to application or services&#160; (VDI, Virtualized Apps, WebPortal Services) and protect them?**
> 
> **Q3:Which entitlements you got to control the device attached to your corporate network?**

In a short way, if I bring my device this means I have only two options:

> 1) I guarantee on my own that the device cannot in any way harm my Employer corporate network. This means I have to maintain my owned device updated with antivirus, firewall and dedicated tools to protect myself and the Employer corporate network.
> 
> 2)My Employer and I agree to install on my device the required and mandatory software the employer think I should have to be protected .

In **case 1** this means the Employer _do not have any kind of control_ over the employee device and should **“blindly” trust** the employee. I am not saying the employee will not try to guarantee the maximum security through the device but that is obvious that, since it is a **personal** device, one is free to use it in any way one like (translated: I love to to test any kind of “so-called” hacking tools and often I am infected with malwares or I love do webcam/Skype/chat conversation with other people without a real control over what these people could send me or inject me).

In **case 2** the real problem is, how I manage this? I mean an agreement of any form could be potentially a “two-way factor” of “fighting” between the Employer and the employee. What if one of the “corporate” application broke my “personal” device? What if I infect the corporate network with my device? After all I’ve agreed to be controlled but this is still a personal device so, there is nothing that said I am responsible in case of a “failure” in the corporate controlling systems and, last but not least, how the Employer could guarantee to be able to manage ALL the devices attached to the corporate net? (i.e.: ipad, iphone, android, smartOS, MS Windows, Linux, etc….).

From the BYOD perspective we are, in my opinion, in a case that could be easily explained with a sociological/economic theory called **“the tragedy of commons”:**

> The **tragedy of the commons** (or **tragedy of the _unmanaged_ commons**) is a dilemma arising from the situation in which multiple individuals, acting independently and rationally consulting their own self-interest, will ultimately deplete a shared limited resource, even when it is clear that it is not in anyone&#8217;s long-term interest for this to happen.

(wikipedia :[http://en.wikipedia.org/wiki/Tragedy\_of\_the_commons][4])

In the tragedy of the commons we got multiple individuals that are at the same time Employee and Employer who introduce in a shared resource (corporate network) an un-managed resource (BYOD) with the idea to do a better use of the shared resources but act in a total different way (I download apps from the corporate network since it is more fast, I access to corporate sensible data even from places where privacy is not guarantee aka trains, airports and public places).

The Identity Management include the way I provide Governance, Privilege Account Management and explore the different way I may reconcile multiple digital identities to a single “human” in order to bring security and control over “who ask to access to what”. The recent public exposure of sophisticated attacks like Flame ([“Flame is Lame”][5] via @mikko) is another important signal of how the concept and the approach to security must be changed.

> **The classic approach** (personal antivirus vs. corporate antivrus, firewall, IDS, NAC and so on… ) **cannot work correctly anymore** if not tight to an #dentitymanagement model that should **approac**h not the device but **the identity of the “owner” of the device**. We should know who may access to what controlling from where he access not in terms of device but in terms of:from where, how, when and most important why.

As we have learned in the recent years cyber terrorism&#160; sponsored by government is a reality and so we cannot trust anybody but, instead of become paranoid we should re-model our approach&#160; and this lead me to the other side of the Auditable Security Scale.

**_Cloud Services:_** If we explore the other side of the scale we will end in, exactly the opposite situation, controlling the Controller.

In this case it is the customer who is the owner of the service that can’t achieve and adequate level of control over the controller due the fact that:

_1) The Controller that provide the controlling system to the controlled (i.e.: Identity Management as a Service, Antivirus as a Service, Security devices in a IaaS model) but since those services and devices are “shared” at some level with other customers it is not possible to allow everybody to “ see” everything_

_2)The Controller do not have an efficient model to provide a full report on the entire stack of&#160; services provided to the controlled customer (again in we are speaking about shared resources that are, for sure, isolated in silos but still shared at top level with others)._

now this case arise more complex questions like :

_1) how I may be sure that the controller to not agree with a competitor to allow him to get in my data? If the controller is the one who provide me reports about audit can obviously modify them to its advantage._

_2) Exactly as for the BYOD case, where it is my dutie to have a security level up to date and where it becomes responsibility of the Controller/provider? It is again a legal agreement but again I’m in IT not in legal so I (excuse my low language here) I do not give a s\*** of agreement I just care about security and who is in my network._

_3)Is it the actual model of #identitymanagement still valid? I am talkin about RBAC,DAC and MAC models here._

I wont’ boring you with another 20 pages post on this so I’ll write a PART II of this where I’ll analyze the models and where they fail or have success from a “cloud-aware” perspective.

 [1]: http://www.cio.com/article/706289/Cloud_BYOD_Increases_Need_for_Automated_IAM_Systems?page=2&taxonomyId=3003
 [2]: http://www.twitter.com/ThorOlavsrud
 [3]: http://alfweb.com/blog/wp-content/uploads/2012/06/SecurityScale.jpg
 [4]: http://en.wikipedia.org/wiki/Tragedy_of_the_commons
 [5]: http://www.f-secure.com/weblog/archives/00002383.html