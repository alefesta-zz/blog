---
title: 'BYOI (Bring Your Own Identity) : The Elephant in the Fridge'
author: Administrator
layout: post
date: 2013-04-10
url: /byoi-bring-your-own-identity-the-elephant-in-the-fridge/
categories:
  - BYOD
  - BYOI
  - COPE
  - Identity Management
  - Quest
  - Security
  - Unicorns
tags:
  - BYOD
  - BYOI
  - Classification
  - identification
  - identity management
  - infosec

---
_BYOI is a series I’ve decided to create to “talk” about #identitymanagement so it is about #security, #governance, #management and many other aspects of the #IAM realm._

<img style="display: block; float: none; margin-left: auto; margin-right: auto" src="http://1.bp.blogspot.com/_CLfPAuJpeqo/R4NZCviJ3NI/AAAAAAAABe4/6EtFARVdGZ4/s400/elo-in-the-fridge.jpg" />

Do you know that humor sketch that sound like this:

> How do you put an elephant in a&#160; fridge? chop it up into bits

&#160;

One of my recent post (you can read it <a href="http://alfweb.com/bg/byoi-bring-your-own-identity-the-fridge-dilemma-and-why-your-idea-of-governance-is-potentially-failing/" target="_blank"><em><font color="#000000">here</font></em></a>) was the starting point of a interesting conversation on _data classification_ and the real need of complex policies,security enforcement, MIM, ILM,etcetera. The conversation on twitter between me, Brian Katz ( <a href="https://twitter.com/bmkatz" target="_blank"><em><font color="#000000">@bmkatz</font></em></a>) and Paul Madsen <a href="https://twitter.com/paulmadsen" target="_blank">(<em><font color="#000000">@paulmadsen</font></em></a>) ended up in a really interesting post on the Brian’s blog with the title <a href="http://www.ascrewsloose.com/2013/04/09/eating-elephants/" target="_blank"><em><font color="#000000">“Eating Elephants”</font></em></a>.

In the post Brian pointed out he’s view on _data classification_ and how a different and simpler approach to the common idea of it could help to reach the same results but with a “minimal” effort. I cannot disagree with his point but cannot agree either and this is because of the dilemma I briefly explained in my post, the so called _“The fridge dilemma”._

## The fridge dilemma

Let say that A,B e C are students and decide to share an apartment near the University.They agree to split the rent and the expenses but since all of them follow different courses and consequently different timeframes are not able to eat together at lunch or dinner. The rule is quite simple the fridge (**fRD**) is a sharing place where everybody got it’s own space . A sharing space means that, as long as your “things” are identifiable nothing can go wrong but this is not a strict rule but more a common sense way of acting, it’s a fridge and I have my own “sector” so I do not need to place any “Identification” on my stuff if I don’t want.

So we may say that:

**fRD = = As% + Bs% + Cs% if As[ID],Bs[ID],Cs[ID] is TRUE**

where&#160; **As%**,**Bs%** and **Cs%** are the sharing spaces inside the fridge for the three users and **As[ID]**,**Bs[ID]** and **Cs[ID]** are the policies that **_categorize_** the stuff inside the fridge.

Let say that one day A and B decide to buys the same food from the same shop, let say it’s a salad with walnuts in it. 

Unfortunately B cannot eat walnuts because of allergy and so ask the shop to substitute them with some other fruit, apparently the two salads have no difference, same box, same brand on it, same “colors” and places in the fridge one near the other are really easy to be confuse one with the other.

Both A and B do not use to place identification on their stuff, after all they have their “place” in the fridge.

So **As[ID]** and **Bs[ID]** are set to **FALSE** 

_This is obviously a policy violation and I’ll come back to every single part of the dilemma later in this post_

A is in a rush because she’s running late to a course so open the fridge and grab the “salad”,obviously the wrong one.

So now B is exposed because without knowing it it’s “salad” has gone and if she will not put an adequate attention will get in trouble with his/her allergy. Using an identification label would solve the problem but since we are using a sharing, and consequently open, “space” we cannot guarantee&#160; that everybody will follow the rule exposing themselves and others to a loss of food (information).

## Analyzing the dilemma aka categorization is not classification

The fridge dilemma is a categorization dilemma mainly it is not related to the content of the salads but to the fact that it is difficult for the two users to recognize the “difference” between the two boxes because of the **_policy violation_**. We said:

**fRD = = As% + Bs% + Cs% if As[ID],Bs[ID],Cs[ID] is TRUE**

but we even said that in a obvious violation the formula become

**fRD = = (As% + Bs% + Cs% if As[ID],Bs[ID],Cs[ID] is TRUE) &#8211; rV**

**where** 

**rV = As[ID] AND/OR Bs[ID] AND/OR Cs[ID] is FALSE**

where with **rV** we consider the risk value associated to a policy violation that expose one or more than one user to a recognizable risk.

So the rule was nothing more than a simple categorization made by two separate definitions:

  * if the food is in my sector of the fridge (**As%**,**Bs%**,**Cs%**) is mine.
  * if I place the food in the sharing area of the fridge and got a label with my name on it (**As[ID]**,**Bs[ID]**,**Cs[ID]**) is mine.

Now what got this to share with security? well as Brian correctly pointed out in his post:

> Chances are, the organization has already picked a tool to help them classify the data and maintain the buckets that they have painstakingly decided upon. That is the easiest part. They now have to spend their time, money, and a lot of effort to train all their employees on how the categories should be applied to each piece of data. They then have to train them on the tool. This can be as long as a three-year process before any data actually gets put into any buckets, this is a lifetime for most organizations and they are probably moving on to the next program at this point.
> 
> Remind me how this helps me to secure my data again? How does it keep me from exposing it to anyone who has the time when I store it in Drop box or Box? It doesn’t, which is why I favor a much more simplistic approach. Start with only two buckets of data. The first bucket is all corporate data, regardless of importance or whatever other classifications you can think up and the second bucket is all non-corporate data. It doesn’t get much simpler than this. Once you have your bucket of corporate data, you figure out how to secure it.

Can one argue with that? no if you’re approach is _data governance_ centric and you’re starting point is that _you know which data are on your network and where_ but what if_&#160; your data are unstructured and so you are not aware of where they are_?

So let’s first see how to manage**&#160; _categorization_.**

Brian gave a incredible simple but powerful way to categorize data: 

  * Corporate Data
  * Not Corporate Data

It’s impressive how this approach solve the categorization issue bringing governance (or at least an early form of it) to the business. On a more complex way to look at it we can even use a different way to **categorize** our data like the one described in the document <a href="http://csrc.nist.gov/publications/fips/fips199/FIPS-PUB-199-final.pdf" target="_blank"><em><font color="#000000">“Standard for Security Categorization of Federal Information and Information Systems”</font></em></a>

> The FISMA defines three security objectives for information and information systems:   
> **CONFIDENTIALITY**   
> “Preserving authorized restrictions on information access and disclosure, including means for protecting personal privacy and proprietary information…” [44 U.S.C., Sec. 3542]   
> A loss of confidentiality is the unauthorized disclosure of information.   
> **INTEGRITY**   
> “Guarding against improper information modification or destruction, and includes ensuring information non-repudiation and authenticity…” [44 U.S.C., Sec. 3542]   
> A loss of integrity is the unauthorized modification or destruction of information.   
> **AVAILABILITY**   
> “Ensuring timely and reliable access to and use of information…” [44 U.S.C., SEC. 3542]   
> A loss of availability is the disruption of access to or use of information or an information system.
> 
> …
> 
> **The potential impact is LOW if—**   
> − The loss of confidentiality, integrity, or availability could be expected to have a limited adverse effect on organizational operations, organizational assets, or individuals.2
> 
> &#160;
> 
> **The potential impact is MODERATE if—**   
> − The loss of confidentiality, integrity, or availability could be expected to have a serious adverse effect on organizational operations, organizational assets, or individuals.
> 
> &#160;
> 
> **The potential impact is HIGH if—**   
> − The loss of confidentiality, integrity, or availability could be expected to have a severe or catastrophic adverse effect on organizational operations, organizational assets, or individuals.
> 
> &#160;

following this document we may setup a simple formula that help us building our **Security Categorization** model:

**SC information type = {(confidentiality, impact), (integrity, impact), (availability, impact)} where the acceptable values for potential impact are LOW, MODERATE, HIGH, or NOT APPLICABLE.**

but again this works, like**&#160; categorization** works only if**&#160; you have a clear idea of the data in your networks (aka structured data)**.

## The unstructured data called classification

The dilemma is nothing more the representation of the reality in most of the companies. We tend to focus on what we know and our risk analysy models only look at the**&#160; known** risk not at what is**&#160; un-known or un-structured**. Brian again is right when he said that _data classification_ when implemented in a canonical ILM model is expansive in terms of efforts and costs and that:

Let’s look at the “fridge” again. The salad is not categorized but is still recognizable since we got some important information’s like :

  * it’s a salad
  * was bought in a specific shop
  * it’s content is different from the other salad in the fridge

these information cannot explain who’s the owner of the two salads and so the **policy violation** is still there but at the same time help the **fridge owner** to **structure** the _data**&#160; and eventually place this information back to the right category**._ 

> I’m aware of potential _sensitive data_&#160; left on uncontrolled area’s of my network and so I can update/re-build my risk model consequently.

<img style="display: block; float: none; margin-left: auto; margin-right: auto" src="http://media.npr.org/assets/news/2010/02/03/risk-f8e65a31b255214aefefa3dac504a377ed3811f3-s6-c10.gif" width="384" height="288" />

****

The approach to classification explain why _governance_ must come later and why a simple _categorization_ even if powerful in terms of cost effectiveness cannot guarantee the adequate level of security on long terms. It’s because we have to “look” at what we don’t see and not at what we think is in the fridge.

as Brian says: “How do you eat an elephant? One bite at a time” but my reply is: “ were you aware that the elephant was in the fridge?”