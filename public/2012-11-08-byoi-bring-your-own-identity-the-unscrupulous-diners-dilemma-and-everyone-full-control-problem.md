---
title: 'BYOI (Bring Your Own Identity) : The Unscrupulous diner&#8217;s dilemma and “everyone FULL CONTROL” problem'
author: Administrator
layout: post
date: 2012-11-08
url: /byoi-bring-your-own-identity-the-unscrupulous-diners-dilemma-and-everyone-full-control-problem/
categories:
  - BYOI
  - Identity Management
  - Life
  - Security
tags:
  - BYOI
  - cooperative theory
  - dilemma
  - game theory
  - governance
  - identity management
  - infosec
  - Security

---
_BYOI is a series I’ve decided to create to “talk” about #identitymanagement so it is about #security, #governance, #management and many other aspects of the #IAM realm._

IT Department **(itD)** of Company A set a nice, well formed, deeply discussed in many internal meetings policy to bring governance (call it “finally we will clean that mess”) to the company filserver **(fS).**

A quick view to the policy say something like :

> **Data Security Policies   
>** Each department should appoint two Local Information Security Administrators (LISAs) who will be responsible for managing user data. The LISAs will be the only users capable of requesting changes to data access controls or adding or removing users from the service.
> 
> …
> 
> **File Server Authentication Policies**
> 
> <font size="2">All authentications will be based on the user’s eCommons credentials <br />All Common Internet File Service (CIFS-Windows) access will be managed through the central Active Directory Service. <br />Users must log into the XXX.YY domain to be given access. <br />Network File Service (NFS) access is controlled through User ID (UID) and Group ID (GID) combinations. <br />IT will provide centralized management of the UID/GID ranges for each department. <br />Users will have to use the UIDs/GIDs provided by IT to gain access.</font>

<font size="1"><em>Harvard Medical School – IT Department (“Centralized File Server Policies and Procedures”) &#8211; </em></font>[<font color="#3e372b" size="1"><em>http://it.hms.harvard.edu/pg.asp?pn=netops_nasprocs</em></font>][1] *

<font size="1"><strong><em>*Note:Let me be clear on this, the HMS policy is just a sample of a standard fileserver policy so could work as could not work, I’m not here to debate on the efficiency and/or efficacy of the above policy</em></strong></font>

So the policy is made and the IT spread the new policy through email to all the employees. The LISA (LiS) are chosen by departments and the fileserver structure start to grow, but here’s the problem:

**LisA** and **LisB** ask to **itD** to setup a shared folder where both **DeptA** and **DeptB** can access, due the particular use of the folder after a while **LisA** request to **itD** to add to the folder even the department employees under the governance of **LisC**, **LisD** and **LisE**

You know the story the (in)famous folder become a sort of shared disk between departments and soon or less nobody is able to manage it anymore or at least discriminate between what is still needed and what could be deleted.

This typical situation of un-governance remind me of a classical economic dilemma called “the unscrupulous diners dilemma”:

> In [<font color="#000000">game theory</font>][2]<font color="#000000">,</font> the Unscrupulous diner&#8217;s dilemma (or just Diner&#8217;s dilemma) is an <font color="#000000"></font>[<font color="#000000">n-player</font>][3] <font color="#000000"></font>[<font color="#000000">prisoner&#8217;s dilemma</font>][4]<font color="#000000">.</font> The situation imagined is that <u>several individuals</u> go out to eat, and prior to ordering they <u>agree to split the check equally between all of them</u>. Each individual must now choose whether to order the expensive or inexpensive dish. It is presupposed that <u>the expensive dish is better than the cheaper, but not by enough to warrant paying the difference compared to eating alone</u>. Each individual reasons that the expense they add to their bill by ordering the more expensive item is very small, and thus the improved dining experience is worth the money. However, every individual reasons this way and <u>they all end up paying for the cost of the more expensive meal, which, by assumption, is worse for everyone than ordering and paying for the cheaper meal.</u>

Unscrupulous diner&#8217;s dilemma – Wikipeda

[<font color="#000000">http://en.wikipedia.org/wiki/Diner%27s_dilemma</font>][5]

Now let’s analyze the dilemma and comparing what it says to “our” dilemma.

**itD** gave to **LisX** the capability of setup their own access policies in terms of indicate who may access and who don’t. We may assume that, in a simplistic way, **LisX** got only two choices:

**sA:** Stric access policy: only users from my department may access to the folder in writing mode and others will, eventually, access in read only mode.

**oA:** Open access policy: I allow most of the users to access in write mode to the folder regardless of their department or real need.

if we run for a secure environment we may say that :

**sA > oA** where **sA**&#160; and **oA** got a value **x** that represent a combination of**&#160; Slp (Security level perceived)**&#160; and **pWl**&#160;**(perceived working enviroment limitation)** expressed in the form of:

**Slp –pWl > sA –oA**

in other terms the value obtained from the Security applied and the “perceived” limitation of the working environment (like ability to easily access to the folder) must be at least greater then the difference between setup a secure and strict access rule and run for a lazy and open one.

Now if this would be a single player&#160; game probably we would not have any kind of problem with this formula, unfortunately we are into a n-player game so we have a position where players can only choose between two options:

**a full cooperative model (cCm):** all the **LisX** involved cooperate and take decision based on a agreement every time:

**a non full cooperative model(ncCM):** every **LisX**&#160; involved decide to follow the mutual agreement for most of the decision but from time to time decide just for him/herself.

there would be, for the truth, a complete non coopertive model but we assume that the actors involved are able to work together (okay I know sometimes, maybe often, this model is fully applicable!!!)

If we look at the original dilemma we may assume that the **cCm** would guarantee everyone the best choice: a higher level of security, a clear workflow that permit to know everyone what to do and when in order to give someone access to the folder, etc…; but this would mean that everyone should “agree” on a **Slp** and accept the **pWl.**

<font color="#000000">I don’t want to be boring so let it put it in this way: did you ever had a dinner with other friends and you agreed first to split the bill in equal part? did it happen that at somepoint someone decided to run for something “out of the rule” like a <a href="http://en.wikipedia.org/wiki/Limoncello">limoncello</a> liquor? let’s call it the “limoncello effect” (<strong>lE)</strong>:</font>

**lE= LisX(Slp-pWl)**

<font color="#000000">where the <strong>lE</strong> is the personal and individual way of looking at the agreement and the consequent decision of “walk” outside the path even if this will compromise the agreement goal.</font>

**lE**&#160; is based on the simply rule that every **LisX** will evaluate the agreement based on the personal evaluation of :

**Security risk perceived (sRp):**&#160; (i.e. :the personal definition of the level of risk associated with how difficult could be for a user to get into the folder and delete all the data)

**Grade of freedom toward other LisX (gF):** I think I have more freedom since I am in a higher position in the company hierarchy.

**Confidence in the company DLP or IDS systems (Cs):** This is something really common in every company “why I should care where there are all these security systems”.

**lE** is the unknow variable that will “move” the agreement made by **LisX** from a full cooperative model to an “not-working-anymore” kind of non full cooperative model.

The formula then is:

**Slp [LisA(lE),..,LisX^n-1(lE)] –pWl[LisA(lE),..,LisX^n-1(lE)] > sA[LisA(lE),..,LisX^n-1(lE)] –oA[LisA(lE),..,LisX^n-1(lE)]**

or in a simplistic and less mathematical way:

> <font color="#333333">in a n-player structure where the level of security is granted by what the players decide you have to expect a certain level of misalignment between what the player agreed to do and what they will end up to implement.</font>
> 
> <font color="#333333">Based on this (<strong>risk management</strong>) you’ll have to setup a deviation rule that could force the players to continue to adopt the agreement (<strong>attestation and certification</strong> of the permission on folders).</font>

<font color="#333333">If you force the <strong>LisX</strong> to evaluate the </font><font color="#000000">on a scheduled basis and provide a simple report that show how all the players are behaving then you are created a deviation rule that modify the <strong>lE</strong> variable and help all the players to get back in track. This sort of deviation could be expressed in the form of <strong>dV (deviation variable)</strong> where:</font>

**dV = lE/(ccP + pCP)**

<font color="#000000">where <strong>ccP</strong>&#160; is a certifcation process run from a third party (ombudsman see <a href="http://alfweb.com/blog/archives/165">my previous post</a> on that)&#160; to decide if permission are appropriate or not and <strong>pCP</strong>&#160; is the personal certification/attestation the<strong>&#160; LisX</strong> must run on a scheduling basis.</font>

<font color="#333333">To conclude we may then say that if the diner&#8217;s dilemma does not have a real solution at least we may find one for your file/folder structure or anyway provide you a way to get more limoncello at dinner!</font>

&#160;

**<font color="#000000">&#160;</font>**

 [1]: http://it.hms.harvard.edu/pg.asp?pn=netops_nasprocs
 [2]: http://en.wikipedia.org/wiki/Game_theory
 [3]: http://en.wikipedia.org/wiki/N-player_game
 [4]: http://en.wikipedia.org/wiki/Prisoner%27s_dilemma
 [5]: http://en.wikipedia.org/wiki/Diner%27s_dilemma