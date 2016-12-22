---
title: 'Me, Myself and I: A view on Identity Management in the Cloud Era–Part III'
author: Administrator
layout: post
date: 2012-04-16
url: /me-myself-and-i-a-view-on-identity-management-in-the-cloud-erapart-iii/
categories:
  - Cloud
  - Identity Management
  - Security
tags:
  - '#cloud'
  - '#identitymanagement'
  - Security

---
If you wonder what I write in Part I and II click [here(Part I)][1] and [here(Part II)][2]

**#SexDoll:** So here we are finally, defining the #sexdoll, firs of all let’s take a classic definition of a it, from wikipedia:

> A sex doll (also love doll or blow up doll) is a type of [sex toy][3] in the size and shape of a sexual partner

<span style="color: #000000;">in other words, we may say that a #sexdoll could be defined as something really similar to something else, who may be used to obtain the same level of services (or sort of).</span>

<span style="color: #000000;">Let me do an example in “our” world: </span>

  1. <span style="color: #000000;">User Joey C. login through the browser to his cloud email service, to do this Joey C. use an authentication system based on a SAML or, in order to be more specific:</span>
  2. <span style="color: #000000;">Joey C. logs into IdM Service Provider system using a SAML, basically this service is provided by the customer itself and it is highly customized,this is due the fact that the customer use a standard (SAML) but do not want that everybody may log in into his system without “explicit permission”.</span>
  3. <span style="color: #000000;">Joey C. log now to a second system,based obviously in the cloud, to do so he got two option :</span>

  1. <span style="color: #000000;">The first is re-login as everybody did in the “ancient” years</span>
  2. <span style="color: #000000;">The second option is to re-use the the previous log-in credentials to access to the second system.</span>

  * <span style="color: #000000;">Joey C. request will be, in fact, redirected to the provider IdM SAML authentication system that will recognize the federated service from a specific organization hostname who will be presented by, guess who, our SAML protocol and the OAuth login request.</span>
  * <span style="color: #000000;">The IdM SAML authentication system of the SP will “talk” with the Authentication systems of Joey C. and the “magic” will happen.</span>

<span style="color: #000000;">So…we just said that we combine SAML and OAuth to give federated access to other systems in order to provide SSO to users or better (and in a more detailed way) SP like Force.com said that ( click <a href="http://wiki.developerforce.com/page/Single_Sign-On_for_Desktop_and_Mobile_Applications_using_SAML_and_OAuth">here</a> for a detailed explantion), but if we stop for a moment and we think about it we just defined the #sexdoll</span>

<span style="color: #000000;">the sD (#sexdoll) is the act of delegate our identity to a third party system in order to obtain the same level of service instead of “do it” as we use to do with a “real” system. I know I’ve played a bit with the words, let me rephrase:</span>

> <span style="color: #000000;">In order to use third party systems without need to re-login each time I need to create a link between “my Org” and the third party “Org”, this is called federation. A Federation means only that I have to use a system (normally defined by the third party) to identify myself when I ask for services, this is called Authentication System.</span>
> 
> <span style="color: #000000;">Since I’m lucky enough to live in a world where, at least, third party systems adopt standard and try to find way to standardize what they consider an annoying yet “timewaster” procedure, as it is login into the “new” system everytime, we ended up to create #sexdolls that allow us to obtain the service we need in the way we need or, at least, we signed a deal for…since as many of you known sexdoll is not necessary a whole body anatomically (or almost) precise body doll but even just a part of it.</span>

<span style="color: #000000;">SAML and OAuth are our sD but not only….</span>

<span style="color: #000000;">sD, in my opinion should  be the combination of other factors that are even much more important in our discussion:</span>

<span style="color: #000000;">Do you remember our question in Part I ?</span>

_how many of you exist? how many identities you “use” daily still continuing being you?_

> **_Me_** : where Me is your network account that allow you to access to your computer every morning when you sit at your office desk

<span style="color: #000000;">and we said:</span>

> **Me(1) to Me (1-n):** where the number of Me is directly related to the number of applications, services,systems you access using a different account.

but we ended up saying:

> **Me** = Employee  Where Employee is (Person + Business Role)

and the conclusion was the **#unicorn** or:

> **First paradigm: _“The audit not audible”:_** we said:
> 
> Me(Auth)={Me + Me(1to n-1)}/Roles

<span style="color: #000000;">the <strong>#sexdoll</strong> just told us that we use a fake “Me” to obtain services and we do not have a real control since we trust the thirdparty so much to give our identity without really control who may access to our data in the third party enviroment.</span>

<span style="color: #000000;">so sD is  for sure :</span>

> <span style="color: #000000;"><strong>lCf(level of Confidence):</strong> where the value assigned is the capability of the customer to obtain an adequate level of information on the third party enviroment in order to know who may access to what (auditing).</span>

<span style="color: #000000;">but sD is even:</span>

> <span style="color: #000000;"><strong>aT (averageTime of Login procedure):</strong> where the average Time of login in the worst condition should be enough to guarantee that a malicious third party cannot act as ourself or as the SP in order to intercept our procedure and re-use those data (Man in The Middle attack).</span>

<span style="color: #000000;">and sD is finally:</span>

> <span style="color: #000000;"><strong>uOp (Uniqueness of Procedure):</strong> where uOp is, or should be, the capability of the authentication system to be unique to the customer system in order to guarantee the proper level of  isolation and control over (even) the third party system (yes it is  another #unicorn)</span>

<span style="color: #000000;">So sD is:</span>

> <span style="color: #000000;"><strong>sD=(lCf *aT) +uOp</strong></span>

<span style="color: #000000;">Now based of what said we demonstrated that there is not a real answer as of today, since the whole formula:</span>

<span style="color: #000000;"><strong>IdM-C (IdM in the Cloud)</strong> = {<strong>[(Me(Auth)+uC+lDu)*Di]/cEc} * sD</strong></span>

is still based on #unicorns and #sexdolls and, personally, this means we are trusting blindly someone who, in some cases may have, access to our sensitive data.

> **Cloud or not Cloud it is not acceptable the risk to place information where you are not able to control who may access to them at any level.**

&nbsp;

<span style="color: #000000;"> </span>

 [1]: http://alfweb.com/blog/archives/113
 [2]: http://alfweb.com/blog/archives/118
 [3]: http://en.wikipedia.org/wiki/Sex_toy