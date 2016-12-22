---
title: 'BYOI (Bring Your Own Identity): Controlling the controller–Part II'
author: Administrator
layout: post
date: 2012-06-15
url: /byoi-bring-your-own-identity-controlling-the-controllerpart-ii/
categories:
  - BYOI
  - Cloud
  - Identity Management
  - Security
tags:
  - '#identitymanagement'
  - BYOI
  - cloud
  - cooperative theory
  - game theory
  - infosec
  - Security

---
_BYOI is a series I’ve decided to create to “talk” about #identitymanagement so it is about #security, #governance, #management and many other aspects of the #IAM realm._

In [Part I][1] I explored the Auditable Security scale and how the new era of BYOD (Bring Your Own Device) got similarity, from a security perspective, to thesis like “The Tragedy of commons”.

I’m restarting now from the last point of that post to continue my dissertation on an approachable model to achieve&#160; control even over the controller who provide the controlling system.

From [Part I][1]:

**_Cloud Services:_** If we explore the other side of the scale we will end in, exactly the opposite situation, controlling the Controller.

In this case it is the customer who is the owner of the service that can’t achieve an adequate level of control over the controller due the fact that:

_1) The Controller that provide the controlling system to the controlled (i.e.: Identity Management as a Service, Antivirus as a Service, Security devices in a IaaS model) but since those services and devices are “shared” at some level with other customers it is not possible to allow everybody to “ see” everything_

_2)The Controller do not have an efficient model to provide a full report on the entire stack of&#160; services provided to the controlled customer (again in we are speaking about shared resources that are, for sure, isolated in silos but still shared at top level with others)._

now this case arise more complex questions like :

_1) how I may be sure that the controller do not agree with a competitor to allow him to get in my data? If the controller is the one who provide me reports about audit can obviously modify them to its advantage._

_2) Exactly as for the BYOD case, where it is my duty to have a security level up to date and where it becomes responsibility of the Controller/provider? It is again a legal agreement but again I’m in IT not in legal so I (excuse my low language here) I do not give a s\*** of agreement I just care about security and who is in my network._

_3)Is it the actual model of #identitymanagement still valid? I am talking about RBAC,DAC and MAC models here._

End of [Part I][1] excerpt 

Let’s make things simple and clear here:

Assuming Corporate A (cA) decide to move its data to a cloud environment owned by Service Provider X (SPx); beside the technological aspect of this, cA will ensure that, at any time and for any reason, will be able to require and/or generate a full audit report on it’s systems and data.&#160; this means that this report should include every aspect of the security stack in other words “who have access,real or potential, how may have access, with which role, etc&#8230;”.

As example in real life of this I’d like to share an excerpt of the [“Amazon Web Services Overview of Security Processes”][2] document from <http://aws.amazon.com> :

> “Moving IT infrastructure to AWS creates a shared responsibility model between the customer and AWS <…>AWS manages a comprehensive control environment that includes the necessary policies, processes and control   
> activities for the delivery of each of the web service offerings. The collective control environment encompasses the   
> people, processes, and technology necessary to maintain an environment that supports the effectiveness of specific   
> controls and the control frameworks for which AWS is certified and/or compliant.”

now back to our example we may said that cA and the SPx agree to share risks and security, probably the SPx provide cA and all other customers of a systems to manage identities and access (IAM as a Service) based on a standard RBAC model. The fact that this IAM systems use an RBAC (Role based access control) is due the fact that again SPx is in the position to provide the same level of access and control to customer in their tenancy and maintain an higher level on the top of everything.

An RBAC (Role based account control) model is quite simple to understand:

> RBAC: it’s a model where&#160; an identity may or may access or not to a defined set of information, manage and or administer them based on a role. The identity may have more than one role inside the same structure in some cases (Multi-roles architecture).

In a multitenancy architecture we&#160; assume that we have at least two layer of administration, that from the #identitymanagement perspective lead us to an approach where I need at least two roles:

**sA:** a top level administrator role who manage the whole infrastructure level as well the multitenant silos single services.

**mA:** a multitenat adminstration role who is allowed to manage the entire silos in which is “releagated” by contract.

this is an exaggerated&#160; simplification of an RBAC model, of course, but it is useful to point out the intrinsic limitation of the model when we apply it to multitenancy architectures (as for example a public cloud infrastructure).

So here it comes again the question:

How I may control the controller?

the RBAC approach could not be applied as we just seen not because it doesn’t work but because it cannot allow the controlled to achieve the necessary control, even over the controller, even when its role is in a more restrictive position than the the role he wants to audit. At the same time neither probably MAC (mandatory access control) or DAC (Discretionally access control) could be used&#160; due other form of limitation:

MAC is even more restrictive than RBAC model and it is on Controller duty to manage “who access to what”. It would work if the Controller who is in charge dot administer the multitenancy environment would be not the provider itself.

DAC reside on an approach where one subject may create,delete and or change any policy&#160; he have access to, as said before discretionally . This approach is, in some way, the natural behavior of the role of the tenant based in a cloud silos, since it is based on a RBAC model the role itself extend its ownership toward the whole infrastructure stack of the cloud silos but, due the fact that this silos must be segregated from others, the role must have a sufficient level of “power” to manage the environment in total autonomy.

Again and to conclude this post, the solution reside in a different approach (that I’ll explain deeper in detail in a next to come post) that flat down the classic RBAC model and approach the entire problem using the game theory and the cooperative models.

first the definition of a cooperative game:

>  **In** [**game theory**][3]**, a cooperative game is a game where groups of players ("coalitions") may enforce cooperative behaviour, hence the game is a competition between coalitions of players, rather than between individual players. An example is a** [**coordination game**][4]**, when players choose the strategies by a** [**consensus decision-making**][5] **process.**

[wikipedia “Cooperative game”][6]

Assume that the RBAC model do not change but that we introduce a different way of control, either a third party or the simple creation of a committee of tenant who have, potentially, access to everything in terms of Audit.

I am not saying I am going to create a super-user Role but simply allow access to the top-level audit roles to all the equivalent roles owned by the tenant. 

Call this role the “share-role” (sR), the tenant auditor (tA) and the SP Auditor role ( spA) where:

> **spA** = spAR where spAR are the actual SP employee who are in charge for the administration of the SP enviroment.
> 
> **sR =spAR + (tA1+tA2+..+tAn-1)**

where sR is the sum of the spA plus the sum of the tenant in charge for control.

> Since everybody got access to the same level of information, so potentially may have access to a competitor audit information, the result will be that even if those tenant are competitors, at the very end will cooperate taking decision based on a&#160; consensus decision-making process.

In other words it is interest of everyone to access the competitor information but due the fact that even the competitor is in the same position will be decided to protect all information at the same level.

On the same position the SP role will be not anymore in a position where can incurs in a illegal agreement with one of the tenants to allow an unauthorized access to the information of a competitors.

this approach could be defined as DRBAC (Discretionally Role Based Access Control) and will be discussed in a future post.

 [1]: http://alfweb.com/blog/archives/131
 [2]: http://d36cz9buwru1tt.cloudfront.net/pdf/AWS_Security_Whitepaper.pdf
 [3]: http://en.wikipedia.org/wiki/Game_theory
 [4]: http://en.wikipedia.org/wiki/Coordination_game
 [5]: http://en.wikipedia.org/wiki/Consensus_decision-making
 [6]: http://en.wikipedia.org/wiki/Cooperative_game