---
title: 'BYOI (Bring Your Own Identity): On the internet nobody knows you’re a dog'
author: Administrator
layout: post
date: 2012-11-02
url: /byoi-bring-your-own-identity-on-the-internet-nobody-knows-youre-a-dog/
categories:
  - BYOI
  - Identity Management
  - Security
tags:
  - '#identitymanagement'
  - authentication
  - BYOI
  - identification
  - identity management
  - infosec
  - Security

---
_BYOI is a series I’ve decided to create to “talk” about #identitymanagement so it is about #security, #governance, #management and many other aspects of the #IAM realm._

[<img style="background-image: none; border-bottom: 0px; border-left: 0px; padding-left: 0px; padding-right: 0px; display: inline; border-top: 0px; border-right: 0px; padding-top: 0px" title="Internet_dog" border="0" alt="Internet_dog" src="http://alfweb.com/blog/wp-content/uploads/2012/11/Internet_dog_thumb.jpg" width="508" height="567" />][1]

Peter Steiner –The New Yorker July 5, 1993.

[<font color="#000000">http://en.wikipedia.org/wiki/On_the_Internet,_nobody_knows_you%27re_a_dog</font>][2]

This adage&#160; invented by the cartoonist and contributor of The New Yorker Peter Steiner arise a still actual questions: Do you know is who’s actually using your systems?

or better:

> <font color="#333333">The ability of authenticate a party doesn’t means that you were able to identify it correctly.</font>

Authentication and Identification are often confused because of the similitudes in the process of “allow an actor Y **(aY**) into a given systems X (**sX**) where:

**aY**=**pID** ^(**dID**^1,…,**dID**^n-1)

**sX**=**aPP**^1,..,**aPP**^n-1

with **pID** as phisical identity associated to one or a multiple list of digital Identities (**dID**) who request access to a given application/service (**aPP**).

Let us analyze a simple process that will lead **aY** to obtain the use of**&#160; sX**:

First of all who is **aY** for **sX**? 

First example: 

The filial imprinting

> In the mid 1930s German ethologist Konrad Lorenz popularized filial imprinting, the process by which a newborn animal learns to recognize the unique characteristics of its parent, typically its mother. This phenomenon was termed imprinting (translated from the German word prägung) by Lorenz&#8217;s mentor, Oskar Heinroth, who believed that the sensory stimulus encountered by the hatchling was immediately, and irreversibly, "stamped" onto the animal&#8217;s brain. Lorenz demonstrated this with his famous goslings, which had spent their first hours of life with him and subsequently followed him everywhere; as adults they preferred the company of humans over fellow avians.

[<font color="#000000">http://www.scientificamerican.com/article.cfm?id=strange-but-true-newborns-can-bond-to-mother-from-different-species</font>][3]

A mother and a newborn are always able to recognize each other by unique characteristics. The parties do not ask for&#160; a verification of the identity but leverage on a unique information that make them sure about who is approaching and which role have in the relation.

_This is an example of physical identification._

Second Example:

The Door key

> <font color="#333333">My door has two separate keys: one short for “quick” close/open and the other longer for a safer close of the door itself. If I am leaving the house I secure the access using both keys, this guarantee (well let’s pretend at least)that only people who have disposal of the two keys may enter in the house. The keys are made with a unique cut that make them, almost, impossible to reproduce.</font>
> 
> <font color="#333333">When I “log in” into the house I use both the keys in order to “unblock” the “system” and be allowed to open the door.</font>

The key do not guarantee I am who I “said” I am but only provide a way to access to the “system” through a recognizable process.

_This is an example of physical authentication_

But the question&#160; is what if I am in the digital world? Things become a little more “confused” here:

> The ways in which someone may be authenticated fall into three categories, based on what are known as the factors of authentication: something the user knows, something the user has, and something the user is. Each authentication factor covers a range of elements used to authenticate or verify a person&#8217;s identity prior to being granted access, approving a transaction request, signing a document or other work product, granting authority to others, and establishing a chain of authority.
> 
> Security research has determined that for a positive identification, elements from at least two, and preferably all three, factors should be verified. The three factors (classes) and some of elements of each factor are:
> 
> **the ownership factors:** Something the user has (e.g., wrist band, ID card, [security token][4], [software token][5], [phone][6], or [cell phone][7]).   
> **the knowledge factors**: Something the user knows (e.g., a [password][8], [pass phrase][9], or [personal identification number][10] (PIN), [challenge response][11] (the user must answer a question)) .   
> **the inherence factors:** Something the user is or does (e.g., [fingerprint][12], [retinal][13] pattern, [DNA][14] sequence (there are assorted definitions of what is sufficient), [signature][15], face, voice, unique bio-electric signals, or other [biometric][16] identifier).

wikipedia on authentication &#8211; [<font color="#000000">http://en.wikipedia.org/wiki/Authentication</font>][17]

Said so we may define the authentication as the process to identify a entity in order to grant access to a give systems, where with the term “identify” we means that process of recognize the distinctive factors that make “unique” the entity.

**The ownership factors:** Something that the only the entity may have : **_a username_** related to a specific subscription (**uSr**)

**The knowledge factor:** Something that the user only knows:** _the password_** related to the above username (**pWd**)

**The inherence factor:** Something the user is or does:**_the role_** that the user have into the subscribed service (**sR)**

<font color="#000000">We may then define the user identification process as:</font>

<font color="#000000"><strong>aY(sX) = uSr+pWd+sR</strong></font>

<font color="#000000">where <strong>aY(sX)</strong> value is the sum of the multiple <strong>dID</strong> of the <strong>pID</strong> :</font>

**pID(dID^1,…,dID^n-1) =[((uSr+pWd+sR)^1),…,((uSr+pWd+sR)^n-1)]**

<font color="#000000">where <strong>pID</strong>&#160; could be defined as <strong>aY</strong>&#160; and <strong>sX</strong>&#160; is the subscribed system.</font>

<font color="#000000">So once we got the identification process clear become even more clear the authorization process that we may define as:</font>

<font color="#000000"><strong>aUH= (aY(sX)) * aUH(YsH)</strong></font>

<font color="#000000">where <strong>aUH</strong> is the authentication system made by:</font>

  * <font color="#000000"><strong>the identification process( aY(sX))</strong></font>
  * **the protocol/service used (aUH(YsH)):** where **YsH** is the method the authentication system is using&#160; to check the identification parameters(i.e. SAML, kerberos/LDAP,x.509,etc…).

> i.e.:Security Assertion Markup Language (SAML, pronounced "sam-el"[[1]][18]) is an [XML][19]-based [open standard][20] data format for exchanging [authentication][17] and [authorization][21] data between parties, in particular, between an [identity provider][22] and a [service provider][23]. SAML is a product of the [OASIS][24]Security Services Technical Committee. SAML dates from 2001; the most recent update of SAML is from 2005.

wikipedia on SAML

[<font color="#000000">http://en.wikipedia.org/wiki/Security_Assertion_Markup_Language</font>][25]

<font color="#000000">now let’s back to the beginning: what do you know about who’s writing this article?</font>

  * <font color="#000000"><strong>pID</strong>: he typed or dictated to a computer this post</font>

<font color="#000000">real example: (<a href="http://talkingpets.ca/en/speakdog.aspx">http://talkingpets.ca/en/speakdog.aspx</a>)</font>

  * **dID:**&#160; somehow have access to this blog

real example: (<http://www.livescience.com/7423-dogs-computers.html>)

  * **sX:** someone (the human me) left the computer un-blocked…if you need examples of this..just wait to be in office again.

now the question is for you…am I the dog of mine or am I who I said I am?

 [1]: http://alfweb.com/blog/wp-content/uploads/2012/11/Internet_dog.jpg
 [2]: http://en.wikipedia.org/wiki/On_the_Internet,_nobody_knows_you%27re_a_dog
 [3]: http://www.scientificamerican.com/article.cfm?id=strange-but-true-newborns-can-bond-to-mother-from-different-species
 [4]: http://en.wikipedia.org/wiki/Security_token
 [5]: http://en.wikipedia.org/wiki/Software_token
 [6]: http://en.wikipedia.org/wiki/Phone
 [7]: http://en.wikipedia.org/wiki/Cell_phone
 [8]: http://en.wikipedia.org/wiki/Password
 [9]: http://en.wikipedia.org/wiki/Pass_phrase
 [10]: http://en.wikipedia.org/wiki/Personal_identification_number
 [11]: http://en.wikipedia.org/wiki/Challenge_response
 [12]: http://en.wikipedia.org/wiki/Fingerprint
 [13]: http://en.wikipedia.org/wiki/Retina
 [14]: http://en.wikipedia.org/wiki/DNA
 [15]: http://en.wikipedia.org/wiki/Signature
 [16]: http://en.wikipedia.org/wiki/Biometric
 [17]: http://en.wikipedia.org/wiki/Authentication
 [18]: http://en.wikipedia.org/wiki/Security_Assertion_Markup_Language#cite_note-0
 [19]: http://en.wikipedia.org/wiki/XML
 [20]: http://en.wikipedia.org/wiki/Open_standard
 [21]: http://en.wikipedia.org/wiki/Authorization
 [22]: http://en.wikipedia.org/wiki/Identity_provider
 [23]: http://en.wikipedia.org/wiki/Service_provider
 [24]: http://en.wikipedia.org/wiki/OASIS_(organization)
 [25]: http://en.wikipedia.org/wiki/Security_Assertion_Markup_Language