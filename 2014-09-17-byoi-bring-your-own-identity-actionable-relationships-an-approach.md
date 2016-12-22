---
title: 'BYOI (Bring Your Own Identity) : Actionable Relationships &ndash; an approach'
author: Administrator
layout: post
date: 2014-09-17
url: /byoi-bring-your-own-identity-actionable-relationships-an-approach/
categories:
  - BYOI
  - Identity Management
  - Internet of Things
  - IoT
  - Unicorns
tags:
  - '#unicorns'
  - BYOI
  - identity management
  - IRM

---
&nbsp;

> Relationships must be able to carry authorization data. This can enable a “thing” to act without having to go back to its back-end server to determine the context in which it can operate

Ian Glazer “The Laws of Relationships (A Work In Progress)” &#8211; [https://www.tuesdaynight.org/2014/05/28/the-laws-of-relationships-a-work-in-progress.html][1]

This post has been written with solely purpose of catch my <span style="text-decoration: line-through;">always</span> disconnected thoughts over the things I read and, in this case, related to IRM and Ian’s “Law’s”

> <h4 align="left">
>   ac·tion·a·ble (ˈakSHənəbəl/)
> </h4>
> 
> <p align="left">
>   1. giving sufficient reason to take legal action.
> </p>
> 
> <p align="left">
>   2.able to be done or acted on; having practical value.
> </p>

> #### re·la·tion·ship(riˈlāSHənˌSHip/)
> 
>   1. the way in which two or more concepts, objects, or people are connected, or the state of being connected.

A relation is quite an interesting concept.

> _A relation between two sets is a collection of ordered pairs containing one object from each set. If the object x is from the first set and the object y is from the second set, then the objects are said to be related if the ordered pair (x,y) is in the relation._
> 
> _A_ _function_ _is a type of relation. But, a relation is allowed to have the object x in the first set to be related to more than one object in the second set. So a relation may not be represented by a_ _function machine__, because, given the object x to the input of the machine, the machine couldn&#8217;t spit out a unique output object that is paired to x_

From: [http://mathinsight.org/relation_definition][2]

So a relationship to exist need at least two parties or at least this is what I was thinking reading  the blog of <a href="https://twitter.com/ricphillips" target="_blank">@ricphillips</a> ( [http://haecceitydotorg.wordpress.com/][3]) and more specifically: “<a href="http://haecceitydotorg.wordpress.com/2014/07/28/to-bind-or-not-to-bind/" target="_blank">To Bind or Not to Bind</a>” and “<a href="http://haecceitydotorg.wordpress.com/2014/09/09/oh-what-a-tangled-web/" target="_blank">Oh What a Tangled Web…</a>”.

But then I start to thinking back at the mathematical concept of a relation and start to wonder if the “initial” assumption (of mine) that two parties are necessarily part of two different identities was correct.

Let’s define an identity as a  certain number of objects (attributes). Those objects could be aggregated into sets . A set  may contain objects  who are part of another set creating a collection of sets _if an only if_  (as per mathematical definition):

> If the object x is from the first set and the object y is from the second set, then the objects are said to be related if the ordered pair (x,y) is in the relation.

This also means (to me) that a relationship may (also) exist within the same _identity_ . I’ll call this _inner relationship_

At the same time the same object,set, collection or identity may be related to an external equivalent creating an _outer relationship_.

If I assume that an_  inner_  and an_  outer_  relationship exist than I may assume that could also  exist a _middle layer_  who has knowledge of one and access to the other in order to pull/push the authorization actions related to one or the other.

[<img style="display: inline; border: 0px;" title="1" src="http://alfweb.com/bg/wp-content/uploads/2014/09/1_thumb.jpg" alt="1" width="511" height="169" border="0" />][4]

<p align="center">
  Fig.1 Model of layer of relationships
</p>

<p align="left">
  <p align="left">
    <em>Outer Identity</em>: All the attributes related to the identity who are defined by the provider of the identity itself. Those attributes are not actionable since they do not carry any information that may directly trigger action to the identity but may be pushed in order to contextualize the identity into the ecosystem where it will “live”.
  </p>
  
  <p align="left">
    <em>Middle Identity</em>: All the attributes related to the identity who may create a relationship between the identity and it’s two sets (inner and outer) of attributes. Those attributes pull information from the outer and from the inner. The attributes are actionable only if the action has been instantiated by the inner set of attributes.
  </p>
  
  <p align="left">
    <em>Inner Identity</em>: All the attributes related to the identity who may create an exclusive relationship with another inner attribute. These attributes are actionable by nature and could not have any relation with an <em>outer attribute</em>. The attribute itself is pulled from a<em>  Middle attribute</em> who is “self defined” at the moment of provisioning.
  </p>
  
  <p align="left">
    The model should than follow a schema similar to this:
  </p>
  
  <p align="left">
    At the moment of the creation of the first identity the provider is responsible to inject a unique set of attributes (<em>outer</em>) who represent the identity toward all the other identities in terms of public uniqueness and identification (authorization and authentication attributes).
  </p>
  
  <p align="left">
    While the <em>outer</em>  attributes are created an action need to be instantiated in order to generate a unique set of attribute called <em>inner attributes</em>. Those attributes are uniquely defined within the identity itself.
  </p>
  
  <p align="left">
    When a second identity is provisioned we will follow the same procedure. The<em>  inner</em>  attributes anyway will be produced using a collection of sets exposed by the initial identity (<em>middle attributes</em>) who link permanently the second identity<em>  inner attributes</em> to the first identity.
  </p>
  
  <p align="left">
    An<em>  inner relationship</em> will be consequently created between the two identities. Any other identity that has not a relationship within this <em>inner circle</em> will not be in a position to join directly since its<em>  inner attributes</em>  were not generated by the original parent.
  </p>
  
  <p align="left">
    An<em>  outer relationship</em> may anyway be stipulated (i.e.: IDP authentication transaction) in order to push further attributes to the identities.
  </p>
  
  <p align="left">
    These further attributes represent a new provisioning process who may fall in a new process of relationship generation who conclude itself generating a new <em>inner relationship</em> who may permit now the two identities to interact (<em> middle relationship</em>).
  </p>
  
  <p align="left">
    Since the<em>  inner relationships</em> carry a common factor of identification do not need to call back the IDP to obtain access and authorization within their “network” still at the same time the single identity to join/un-join the various relationship need at least to pull/push attributes from the “<em>outer”</em>  (IDP) actors.
  </p>
  
  <p align="left">
    A model that represent this is the concept of “my Identity” as personal domain for the <em>identity of things .</em> Let’s assume that a user (parent identity) is filling his/her home of devices. All these devices are part of the “my Identity Domain (<strong>mID</strong>)” of this user. The user has a “main identity” that is based on the first service/product/thing will add to <strong>mID</strong>.
  </p>
  
  <p align="left">
    <strong>mID</strong> is composed by the vendor attribute (<em>outer identity</em>): <strong>oID</strong>, by the user identity (<em>middle identity</em>):<strong>ID</strong> and by the unique set of attributes generated by the addition of the very first other “thing” (<em>inner identity atrributes</em>):<strong>iID</strong>.
  </p>
  
  <p align="left">
    Based on this for every new “thing” added to<strong> m</strong><strong>ID</strong> we will have at least:
  </p>
  
  <p align="left">
    <strong>oID:</strong> public attribute known by every other object at IDP level (vendor/producer), reachable from public network
  </p>
  
  <p align="left">
    <strong>ID:</strong>  is “uniquely” generated by <strong>mID</strong>  but is still public reachable and pull authorization information&#8217;s from IDP and from <strong>iID</strong>
  </p>
  
  <p align="left">
    <strong>iID</strong>: is uniquely generate from the sum of attributes who compose the<em>  inner relationship circle</em>. The attribute is actionable from any identity inside the relationship and do not accept any interference from outside identities if not only through the communication with an <strong>ID </strong>(i.e.: I cannot manipulate the access since the attributes related to the authorization process are not known in the outside world). This attributes are not public but stay private within the identities joined to that specific<em>  inner relationship</em>.
  </p>
  
  <p align="left">
    …continue
  </p>

 [1]: https://www.tuesdaynight.org/2014/05/28/the-laws-of-relationships-a-work-in-progress.html "https://www.tuesdaynight.org/2014/05/28/the-laws-of-relationships-a-work-in-progress.html"
 [2]: http://mathinsight.org/relation_definition "http://mathinsight.org/relation_definition"
 [3]: http://haecceitydotorg.wordpress.com/ "http://haecceitydotorg.wordpress.com/"
 [4]: http://alfweb.com/bg/wp-content/uploads/2014/09/1.jpg