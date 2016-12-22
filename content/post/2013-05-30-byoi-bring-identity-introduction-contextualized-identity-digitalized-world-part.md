---
title: 'BYOI (Bring You Own Identity) : An introduction to Contextualized Identity in a digitalized world'
author: Administrator
layout: post
date: 2013-05-30
url: /byoi-bring-identity-introduction-contextualized-identity-digitalized-world-part/
categories:
  - BYOI
  - Identity Management
  - Life
  - Security
  - Uncategorized
tags:
  - Security; BYOI;Strategy;Identity

---
<p align="center">
  <a href="http://alfweb.com/bg/wp-content/uploads/2014/05/dilbert130815.png"><img style="float: none; margin-left: auto; display: block; margin-right: auto; border-width: 0px;" title="dilbert-130815" src="http://alfweb.com/bg/wp-content/uploads/2014/05/dilbert130815_thumb.png" alt="dilbert-130815" width="572" height="179" border="0" /></a><a title="http://www.discoveringidentity.com/wp-content/uploads/2013/09/dilbert-130815.png" href="http://www.discoveringidentity.com/wp-content/uploads/2013/09/dilbert-130815.png"><span style="color: #000000;">http://www.discoveringidentity.com/wp-content/uploads/2013/09/dilbert-130815.png</span></a>
</p>

## 

> <p align="center">
>   What is a an “identity”?
> </p>

Seems a quite easy question and I bet that many of the readers almost immediately  associate the concept of “identity” with the common definitions of “digital identity”, in all the multiple declination we are able to give to them today. But my question was even more simple. I was referring to the general definition of the word itself. It’s about identities and not necessarily regarding human nature. Let’s give a first definition of an Identity through the words of Michael Pauen:

> Identity is what makes something what it is. It’s what makes a pebble a pebble, a chair a chair, and a human a human. On the face of it, identity specifies single individuals only and it seems to include all the properties these individuals have: Either something is identical with itself or it is something different. On a second look, it turns out that this can’t be the complete truth. One of the reasons is that identity may persist over time. Cities and also humans preserve their identity even if they undergo significant changes, as long as they preserve what makes them special: In the case of the cities, it’s their place, in the case of humans, it’s their specific set of properties…

It’s indeed a philosophical approach to the concept of identity but still apply to a “digital” concept of an identity if we look at some part of the definition:

_“Identity is what makes something what it is”_ : In a digital world as it is ours we have to face the challenge of define what is and who is the “one” asking us an information, whether it is an application in the form of an API, a Web Service, a method of authentication, a human who is actually typing its credentials.

_“…identity specifies single individuals only and it seems to include all the properties these individual have…”_: Again in our so well connected world this apply perfectly to any authentication method and especially in the federated approach where the ability to pass to the the other party only the relevant information&#8217;s and not those who may either: expose sensitive information without reason or make fail the process due the lack of capability of uniquely identify the “actor” requesting the authentication.

But an identity, as perfectly explained by Pablo Garcia Mexia, could be or better, is even a legal definition:

> Among other meanings not applicable in this context, the Oxford English Dictionary defines “identity” as  “the facet of being who or a what a person or thing is”. The definition combines both an objective and a subjective perspective, also common to other languages: objective, for in the end identity can be deemed “ a fact”: and subjective, in that it is this fact that makes that person be what he or she is.  From the legal point of view, both notions converge on the idea of human dignity…As an expression of human dignity, identity unfolds in rights such as that to have a name, self-image, privacy ( especially of personal data) and even in the freedoms of thought and expression (since both are signs of a particular and irreplaceable personality).

Easy it is the link between this and the concept of digital identity but introduce a concept I personally find very intriguing:

_“The definition combines both an objective and a subjective perspective, also common to other languages: objective, for in the end identity can be deemed “ a fact”: and subjective, in that it is this fact that makes that person be what he or she is.”_: From a legal definition of the term we assume that every so called “identity” must or could be contextualize. If I don’t look at the entire set of properties able to define an “identity” I will not able to uniquely identify  _“ who or what a person or things is”._

The above definitions are indeed related to physical identities so I have, before present the “contextualized identity” term to define what is a digital identity.

> I’ll define a digital identity a relevant set of properties that identify in a unique manner an “actor”. A  device  represent an “identity” if I may “read” unique properties like its MAC address, its manufacturer unique ID, the connected (and supposedly) unique IP, the certificate presented to the authentication system, etcetera. Humans when “connected” to a digital “_alter-ego”_ like an account or a digital certificate or any device uniquely and directly related to them are “digital identities”, as per the previous definition.

But is it true? for humans can be this definition applicable? In my opinion not anymore or anyway not in a near future. Anyway before go through the  analysis of why I think human “only” cannot be anymore uniquely identifiable I’ll “share” the concept of  _“contextualized identity”_.

The contextualized identity is a sum of the above definitions who try to embrace the evolution of the modern era toward a more and more connected environment where the boundaries between physical, social and working identities is, day after day, more thinner.

> A contextualized identity is made by a superset of metadata who represent in a variable form a unique subject. This superset is made of _general_ (static) and _detailed_ (dynamic) metadata who represent the identity contextualized to the moment in time where it is used.

In other words I cannot define an Identity only by the _general_ information&#8217;s even if those are not forged and so I could, on a general basis, trust them. Why not? Because there are variables who may forge the result of the process even without “touch” the _general_ information’s.

Seems more an authentication topic than any

## 

## “Big Data” vs “Contextualized Information&#8217;s”

The increase of the volume of data challenge the IDentity Management. The cultural shift we are facing is  to move from a “persona centric” approach to a “data centric” approach, where the context where the information is consumed or, even just, requested represent a first important layer who embrace security, risk management, governance and all the IDentity management “definitions”. But is it possible to approach the challenge looking only at the context of where the information is either requested or consumed? My point is that even simply a different form of regulation in two different countries would make this approach &#8220;weak”. I’m not saying  a computational analysis cannot recognize where the information is at the moment is going to be requested but that this would need a deep “knowledge” of the regulation applicable in order to guarantee that “identity” cannot ask for a specific “information” when the rule is either satisfied or not. I am, at the same time, conscious that many vendor are actually able to provide this capability but again it’s only a “simple static” decision that avoid or the information to “transit” from a specific silos to another or to deny the capability of the “identity” to request the information related to a subset of contextualized metadata (i.e.: geolocalization).

The raise of the volume of data and the evolution of the digital identities toward a more and more mixed “life” where social and working identities are used together (i.e.: gamification, social federated authentication, etcetera) means that we must not only be able to define the context related to the information but even for the “identity” itself.

The context is not related to the data but to why the data is going to be consumed in that specific moment in time.  Said that, the information must be first of all contextualized toward (at least) two directions:

  * Where the information is at the moment is going to be consumed
  * Why the information is going to be consumed

The results of the two give us a context where to operate (_general_) and raise a second evaluation made by:

  * Who is going to consume the information (the digital identity)
  * what is used to consume the information (the digital identity of the method used)

the sum of the four variable give us a reasonable set of information that allow us to contextualize the “form of  the request”. But we have to know at this point other information to correctly contextualize the information and they are:

  * The kind of information going to be consumed (classification/categorization)
  * The privilege assigned to the identity to consume the information (privileged access/account management)
  * The Location of the identity who’s going to consume the information
  * The number of device that can consume the information at the same time using the same Identity in the same moment in time
  * The status of the Identity (both the consumer and the device used) while the information is consumed
  * The status of the information consumed in that moment in time (aka if the data is going to move from one geographical location to another)

All this variables are indeed part of the picture and helps to contextualize the request in order to decide upon it.

Let me refresh your mind with what the term “context” means:

> The circumstances that form the setting for an event, statement, or idea, and in terms of which it can be fully understood…the parts of something written or spoken that immediately precede and follow a word or passage and clarify its meaning

So is contextual identification possible? Somehow yes if relegated to a single “domain” or a “network of trust”. What I mean is that those variables are or need to have at least two kind of conditions in common:

  * Need the analysis of an elevated volume of data
  * The results of this analysis must be known by all the parties involved or at least have to presented in a form known by them.

## Internet of Things and the Un-trusted world

[<img style="float: none; margin-left: auto; display: block; margin-right: auto; border-width: 0px;" title="Flickr_Untrusted_Connection" src="http://alfweb.com/bg/wp-content/uploads/2014/05/Flickr_Untrusted_Connection_thumb.gif" alt="Flickr_Untrusted_Connection" width="453" height="301" border="0" />][1]

We said: The Identity should be contextualized in a way that is identifiable in a uniquely way.

We said: The context of the identity and the result of the process of the analysis where the context apply should be as well uniquely identifiable

We said also: The results should be shared through parties involved so that the uniquely identification mentioned at the first point may exist.

But…

We do NOT live in a connected world as it should be needed by the Contextualized Identity. We live in the “internet of things”

> <h3 align="center">
>   Inter·net of things
> </h3>
> 
> <p align="center">
>   <i>noun</i>
> </p>
> 
> <p align="center">
>   noun: <b>Internet of things</b>
> </p>
> 
> <p align="center">
>   a proposed development of the Internet in which everyday objects have network connectivity, allowing them to send and receive data.
> </p>

<p align="left">
  It does NOT say : where everyone knows what is going to happen and neither says: where even the regulations are responsible to provide guidance to the way the information&#8217;s are shared in a uniquely way that allow to identify a single transaction between two or multiple identities in a way that is always applicable no matter the context, method or circumstance it happen.
</p>

<p align="left">
  In a world of connected “things” seems quite difficult to get the information out from some of these things and use these information&#8217;s in a valuable way. Let me use a simple example:
</p>

<p align="left">
  <em>A man with a heart pacemaker fly from Australia to United States of America through Europe. The man heart pacemaker is able to identify PII data and send them to his hospital so that over than track the current state of the  device they may alert the emergency response if something goes wrong.</em>
</p>

<p align="left">
  This works perfectly with the “local” hospital and maybe with some partners but, at the state of now, doesn’t work with any other emergency response structure around the globe
</p>

<p align="left">
  It’s not a technical limitation but a more complex sum of events: regulation, lack of federation between structures,etc.. but most of all what it really lack is, again a unique way to identify uniquely the information in a way that if associated to the context where it happen will produce an event that may be even re-used by other parties.
</p>

<p align="left">
  Which parties? if Emergency response unit in Europe receive an alert from our Mr. X pacemaker could eventually trigger a chain that sounds like:
</p>

  * <div align="left">
      Emergency Unit link and retrieve data of Mr. X directly from his originating Hospital
    </div>

  * <div align="left">
      The data type are linked to the assurance that in through a federated exchange of information with Hospital of Mr. X provide information regarding the assurance coverage
    </div>

  * <div align="left">
      Bank of Mr.X re-use assurance data to put “in control” Mr. X money transfer to guarantee that, since he’s abroad, he may obtain quickly the funds for him and his family
    </div>

  * <div align="left">
      etc..
    </div>

<p align="left">
  Since the contextualized data told us that Mr. X is abroad, in defined circumstances and that other XY ppl has been through this before all the chain may operate in a optimized way still maintaining a segregated layer between Mr.X identity and the contextualized identities similar but still unique all the chain parties have.
</p>

<p align="left">
  To make it more clear, the context define the actions that the identity is subject to, in example guarantee that the identity may act in a different way acting as a “different” identity.
</p>

<p align="left">
  Identity is what makes something what it is.The context is presented as the circumstances that form the setting for an event, statement, or idea, and in terms of which it can be fully understood.
</p>

> <p align="left">
>   A contextualized identity is a uniquely set of metadata that may be fully understood by any party without requiring a specific knowledge of them but only a minimal capability of use them in accordance with what the identity request.
> </p>

 [1]: http://alfweb.com/bg/wp-content/uploads/2014/05/Flickr_Untrusted_Connection.gif