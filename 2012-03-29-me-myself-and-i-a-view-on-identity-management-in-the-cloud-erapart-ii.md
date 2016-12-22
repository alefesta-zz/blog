---
title: 'Me, Myself and I: A view on Identity Management in the Cloud Era–Part II'
author: Administrator
layout: post
date: 2012-03-29
url: /me-myself-and-i-a-view-on-identity-management-in-the-cloud-erapart-ii/
categories:
  - Life
tags:
  - '#identitymanagement'
  - cloud
  - data
  - Security

---
If you wonder what I wrote in Part I just click [here][1]

**Unicorns:** Based on what said in the previous post the problems remain the same, let me describe through the “words” of someone who knows #identitymanagement better than me.

Do you know the Kim Cameron’s ([bio][2])7 laws of identity? 

> **User Control and Consent:** Digital identity systems must only reveal information identifying a user with the user’s consent. 
> 
>  **Limited Disclosure for Limited Use:** The solution which discloses the least identifying information and best limits its use is the most stable, long-term solution. 
> 
> **The Law of Fewest Parties**: Digital identity systems must limit disclosure of identifying information to parties having a necessary and justifiable place in a given identity relationship. 
> 
> **Directed Identity:** A universal identity metasystem must support both “omnidirectional” identifiers for use by public entities and “unidirectional” identifiers for private entities, thus facilitating discovery while preventing unnecessary release of correlation handles. 
> 
> **Pluralism of Operators and Technologies:** A universal identity metasystem must channel and enable the interworking of multiple identity technologies run by multiple identity providers. 
> 
> **Human Integration:**&#160; A unifying identity metasystem must define the human user as a component integrated through protected and unambiguous human-machine communications. 
> 
> **Consistent Experience Across Contexts:** A unifying identity metasystem must provide a simple consistent experience while enabling separation of contexts through multiple operators and technologies. 

Now if we relate this laws to the cloud realm what we have is:

**User Control and Consent:**Let me quote myself :

> **_“The audit not audible”:_** we said:
> 
> Me(Auth)={Me + Me(1to n-1)}/Roles
> 
> where the Roles able to define where I may access or may not are, obviously defined by my Organization. But we just said we are “on cloud” this means that based on the model I am using (IaaS, PaaS or Saas) there are many chances that some of the “Roles” are not defined by “myOrg” but from the provider from I am buying “the service”.

<font color="#000000">User Control and consent means that as customer I must know or at least, must be in the position of be able to control who may access to my resources and in which way, public or private, free of charge or under contract no matter what.</font>

<font color="#000000">So we may define this as:</font>

> <font color="#000000">&#160;<strong>uC (User Control and Consent)</strong> </font>

<font color="#000000">where the value we assign to uC is&#160; the #openess of control that the service provider grant us in terms of Governance (Auditi, Role Based management, etc…).</font>

<font color="#000000">Please take in mind the <strong>uC</strong></font>

**Limited Disclosure for Limited Use + The Law of Fewest Parties:** How do you access to data on cloud&#160; or, better, which way you use to authenticate Yourself to the different service provider who offer you access to your data in your/their cloud? did you catch the non-sense of the question? yes I’ve just said that to access to something that is yours you have to demonstrate that you, are who you said you are.

But it is not only this, let me call this the **#sexdoll**, I’ll describe this concept in the third part of this post, by now I simply say that we may define:

> **lDu (Limited Disclosure Use)**

where the value you assign to lDu the capability of your system to allow you to access using the most limited disclosure of information.

lDu is a value that varies depending on: authentication system (homogeneous vs. heterogeneous) , the number of authentication systems and their ability to recognize one to each other (federation vs isolation).

**Directed Identity:**Take this example, a vendor offer you a new service that allow you to profile your users and allow them to subscribe themselves to multiple services external to your Organization. So you may, from the same “console” access to data inside and outside the organization. This system is based maybe on OAuth and SAML as authentication dialect.

I am not saying this system is not secure or not accurate, neither is my intention to convince you that exist&#160; a solution better than another (yes I work for a company that offer an #identitymanagement solution but not here to do marketing or evangelization).

The image below is and extract of the loginflow used by google to authenticate a user through it’s APIs. This systems is aligned to OpenID (I’ll describe it in a moment).

[<img style="background-image: none; border-bottom: 0px; border-left: 0px; padding-left: 0px; padding-right: 0px; display: inline; border-top: 0px; border-right: 0px; padding-top: 0px" title="loginflow" border="0" alt="loginflow" src="http://alfweb.com/blog/wp-content/uploads/2012/03/loginflow_thumb.png" width="520" height="367" />][3]

from the public Google documentation ("Google Accounts Authentication and Authorization" <https://developers.google.com/accounts/docs/OAuth2?hl=it-IT#scenarios>) :

> The login sequence starts by redirecting the browser (popup, or full-page if needed) to a Google URL with a set of query string parameters. Google handles selecting the correct session (if the user has previously logged in with multiple identities), accepting and validating the user credentials and one-time-passwords (if the account requires it), obtaining consent to release basic profile information, as well as minting and returning an OAuth access token to your application.

Simple and accurate, limited use of information and ability to define “who you said you are”, but what if the same system is used in a multi-tenants ecosystem where every tenant use the same technology but do not recognize the validity of the already logged in account.

All of this would accurate but inefficient, OpenID is an example of solution that try to work around this problem.

> **OpenID:** OpenID Connect is a suite of lightweight specifications that provide a framework for identity interactions via RESTful APIs. The simplest deployment of OpenID Connect allows for clients of all types including browser-based, mobile, and javascript clients, to request and receive information about identities and currently authenticated sessions. The specification suite is extensible, allowing participants to optionally also support encryption of identity data, discovery of the OpenID Provider, and advanced session management, including logout.

<font color="#000000">we may define Di as:</font>

**Di:**is the value you assign the efficiency of the authentication system you use, where the value is determined by the capability of the various system to re-use the already issued information when you did the first login.

The direct consequence of this value define the satisfy the existence of a real **Pluralism of Operators and Technologies.** In other terms we may say that

pOT (**Pluralism of Operators and Technologies)** is True if iD is > 70% of your iD scale.

**Consistent Experience Across Contexts:** in association with **Human Integration** evrything described above must be evaluated to the capability of the system you use to access to your data and to the information related to the use of your data reusing the authentication information but providing an adequate level of separation between identities.

In other words, as administrator of the Organization I must be able to Audit the entire stack of :technologies,roles,information no matter if thei are on-premises, outsourced or cloud based but at the same time as provider of service I must be able to maintain the separation of duties between user that have the same roles in “my” Organization but are defined as “subscribers” of differente “sub”-Organizations.

**cEc:**is the value you assign to the capability of your cloud service provider to satisfy this law.

now, first of all thank you to still be here, second the unicorn is:

> **[(Me(Auth)+uC+lDu)*Di]/cEc**
> 
> **where:**
> 
>  **Me(Auth) value is between 1 and n-1**
> 
> **uC value is between 1 and 10 where 10 is the most satisfying value**
> 
> **lDu value is between 1 and 10 where 10 is the most satisfying value** 
> 
> **cEc value is between 1 and 10 where 1 is the most satisfying value** 

End of part II

In the part III I’ll discuss about the #sexdoll dilemma.

 [1]: http://alfweb.com/blog/archives/113
 [2]: http://www.identityblog.com/?p=360
 [3]: http://alfweb.com/blog/wp-content/uploads/2012/03/loginflow.png