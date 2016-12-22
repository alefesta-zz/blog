---
title: 'BYOI (Bring Your Own Identity) : the reverse RBAC model and why you should be the ombudsman of yourself'
author: Administrator
layout: post
date: 2012-10-31
url: /byoi-bring-your-own-identity-the-reverse-rbac-model-and-why-you-should-be-the-ombudsman-of-yourself/
categories:
  - BYOI
  - Cloud
  - Security
tags:
  - '#identitymanagement'
  - cloud
  - identity management
  - infosec
  - rbac
  - Rule of Trust
  - Security

---
_BYOI is a series I’ve decided to create to “talk” about #identitymanagement so it is about #security, #governance, #management and many other aspects of the #IAM realm._

> “Two men are arrested, but the police do not have enough information for a conviction. The police separate the two men, and offer both the same deal: if one testifies against his partner (defects/betrays), and the other remains silent (cooperates with/assists his partner), the betrayer goes free and the one that remains silent gets a one-year sentence. If both remain silent, both are sentenced to only one month in jail on a minor charge. If each &#8216;rats out&#8217; the other, each receives a three-month sentence. Each prisoner must choose either to betray or remain silent; the decision of each is kept secret from his partner. What should they do? If it is assumed that each player is only concerned with lessening his own time in jail, the game becomes a non-zero sum game where the two players may either assist or betray the other. The sole concern of the prisoners seems to be increasing his own reward. The interesting symmetry of this problem is that the optimal decision for each is to betray the other, even though they would be better off if they both cooperated.” – Wikipedia <font color="#000000">(</font>[<font color="#000000">http://en.wikipedia.org/wiki/Prisoner&#8217;s_dilemma</font>][1]<font color="#000000">)</font>

To describe the concept of _reverse RBAC_ first of all should be known the concept of RBAC itself:

“_Within an organization, roles are created for various job functions. The permissions to perform certain operations are assigned to specific roles. Members of staff (or other system users) are assigned particular roles, and through those role assignments acquire the computer permissions to perform particular computer-system functions. Since users are not assigned permissions directly, but only acquire them through their role (or roles), management of individual user rights becomes a matter of simply assigning appropriate roles to the user&#8217;s account; this simplifies common operations, such as adding a user, or changing a user&#8217;s department._

Three primary rules are defined for RBAC:

  * · **Role assignment(Ra):** A subject can exercise a permission only if the subject has selected or been assigned a role. 
  * · **Role authorization(rAuth):** A subject&#8217;s active role must be authorized for the subject. With rule 1 above, this rule ensures that users can take on only roles for which they are authorized. 
  * · **Permission authorization(pAuth):** A subject can exercise a permission only if the permission is authorized for the subject&#8217;s active role. With rules 1 and 2, this rule ensures that users can exercise only permissions for which they are authorized.” 

<font size="1">Wikipedia definition – “</font>[<font size="1">http://en.wikipedia.org/wiki/Role-based_access_control</font>][2]<font size="1">”</font>

So we may assume that :

**Ra=rAuth + pAuth**

where :

**rAuth** is true only if **Ra is true** and **pAuth is not null**

so based on the simple formula we may easily understand that if **Ra** got an high value than is potential level of access to any data in the ecosystem is of equal value.&#160; As a example this is a short transcript on [<font color="#000000">“Nebula project”</font>][3] and its RBAC model:

> Every Nebula user has a set of global roles, which typically correspond to IT training courses that they&#8217;ve completed. These roles include System Administrator, Network Administrator, IT Security Administrator, etc. Additionally, each user has a similar set of project-specific roles. A user&#8217;s ability to make API calls for any project is the result of the \*intersection\* of these two sets of roles.

[<font color="#000000" size="1">http://nebula.nasa.gov/blog/2010/06/03/nebulas-implementation-role-based-access-control-rbac/</font>][4]

_My question is what happen if I run a full audit to a model like this? The answer could be split in two possible option:_

  * I run the Audit against the&#160; Service Provider and I’ll limit my result to those information&#8217;s that are into the perimeter (legal/technological) of my role.
  * I run the Audit against the Service Provider and I instruct an [<font color="#000000">ombudsman</font>][5] of the Audit to to obtain two things: 













  * guarantee the SP that nobody can access to level where do should not have access
  * obtain a full audit report (or something similar)

now let me play the evil part of a moment and assume that the world is not the utopic place where we live, where all of us are (or most of the company we work for) are driven by truth and honor and not by money and profit okay? yes I’m kidding but not so much, what I mean is: I’m a tenant in an cloud ecosystem and I need of a full Audit report, this means I need to have&#160; a full “view” of the entire stack of potential data breaches, how I may obtain it? this question is one of the strategic questions that companies must or are asking themselves before to get into an hybrid cloud model. 

So the only way is through this third party who should be absolutely incorruptible, with any adherence to the cloud SP or any other entity that could false the Audit report right?

I’m not meaning these articles are truth but only that show something that potentially could happen:

<div>
  &#160;
</div>

> A former senior analyst at Moody&#8217;s has gone public with his story of how one of the country&#8217;s most important rating agencies is corrupted to the core.   
> Read more: [<font color="#000000">http://www.businessinsider.com/moodys-analyst-conflicts-corruption-and-greed-2011-8?op=1#ixzz2Asu7Ownu</font>][6]

> The reason you hire McKinsey is that its consultants have seen strategic business issues like yours before, and therefore might have developed good insights into how to approach them. But the reason they’re familiar with those issues is that they’ve been given highly confidential information about your competitors. So when you hire McKinsey you’re essentially trying to acquire, for a very high hourly fee, the kind of corporate intelligence that can only be built up through long exposure to highly-sensitive commercial information. Read more: [<font color="#000000">http://blogs.reuters.com/felix-salmon/2011/03/09/mckinseys-corrupted-culture/</font>][7]

the debate can run forever the point is how you could be sure that the SP and the ombudsman are not in a sort of undercover legal contract? What guarantee you about the Audit results? It’s again the [<font color="#000000">“restaurant dilemma”</font>][8] you trust the food you eat based on many parameters but none of these are 100% secure.

In other terms if I am a company and want to move toward an hybrid cloud solution I would must calculate the risk of a data breach&#160; associated to the inability to demonstrate or known the potential risk associated due the (again) potential (il)legal contract between the SP and the ombudsman.

Do you remember the prisoner dilemma? I’m not going to get into a discussion on if the dilemma is applicable in the reality or not but let me get the idea associated with it.

I’m a tenant A (**tA**) who decide to subscribe a service with a Service Provider (SP).&#160; The SP has a legal contract with another tenant (**tB**) who is a competitor of&#160; **tA**.

in a usual RBAC model I would have a situation like the one below:

[<img style="background-image: none; border-bottom: 0px; border-left: 0px; padding-left: 0px; padding-right: 0px; display: inline; border-top: 0px; border-right: 0px; padding-top: 0px" title="ombudusman" border="0" alt="ombudusman" src="http://alfweb.com/blog/wp-content/uploads/2012/10/ombudusman_thumb.jpg" width="526" height="478" />][9]

now both **tA** and **tB** don’t know about the the Unknown Role (**uR**) and about its capability to look into their data. I am not going to define why uR is there and what are the countermeasures that **tA** and **tB** should adopt.

What would happen if both **tB** and **tA** would be allowed to move to the top of the stack at the same level of the SP? I would have a situation similar to this:

[<img style="background-image: none; border-bottom: 0px; border-left: 0px; padding-left: 0px; padding-right: 0px; display: inline; border-top: 0px; border-right: 0px; padding-top: 0px" title="ombudusman2" border="0" alt="ombudusman2" src="http://alfweb.com/blog/wp-content/uploads/2012/10/ombudusman2_thumb.jpg" width="525" height="512" />][10]

Question is who guarantee **tA** from a **tB** intrusion and how can the SP still guarantee to both an adequate level of security?

Again looking at the prisoner dilemma I would say that the what make “secure” the environment is that if, from a technological point of view the RBAC model is still valid and should exist but from the perspective of, let me say, governance models the RBAC should be more similar to the figure below:

[<img style="background-image: none; border-bottom: 0px; border-left: 0px; padding-left: 0px; padding-right: 0px; display: inline; border-top: 0px; border-right: 0px; padding-top: 0px" title="ombudusman3" border="0" alt="ombudusman3" src="http://alfweb.com/blog/wp-content/uploads/2012/10/ombudusman3_thumb.jpg" width="535" height="512" />][11]

> The reverse RBAC means that based on a legal agreement I, as tenant accept that a counterpart of my level (another tenant) have the ability to dig into the systems of the SP environment in order to obtain a full audit report on who may access and how.

at the same time the SP can conduct an audit in any moment on any tenant in order to define who may access to what and why, for a given tenant the ability to “sit” at a level of the SP is derived by its code of conduct. 

the code of conduct (**cOc**) is based on a legal agreement between party that provide the rules to of “certification” that allow a tenant to move up in the reverse RBAC stack.

So the question is why this should stop **tA** to “look” at **tB** data?

Let say that **tA** have three options:

  * **tA** is 0 (zero) when decide to not look at **tB** data even if got the option to.
  * **tA** is 1 (one) when decide to look at **tB** data
  * **tA** is 2 (two) when try to gain an agreement with **SP** to hide is illegal action toward **tB**

assume that **tA** does not have any notion of what **tB** is doing.

so we have those possible options

  * _tA =0, tB=0 > no harm_
  * _tA=1, tB=0 > SP can conduct audit and downgrade tA_
  * _tA=0,tB=1 > as above_
  * _tA=1,tB=1 > SP downgrade both_
  * _tA=2,tB=0 > tB can leverage on its status and conduce, with other tenants, a full Audit that lead to a legal act_
  * _tA=2,tB=1 >potentially other tenant can conduce a full Audit on tA and tB conduct._
  * _tA=2,tB=2 > no harms since all the parties cannot attack each other without damage_

based on the above quick analysis what we see is that **tA** and **tB** are not encouraged to arm the other party since the only way to act is to use the dominant position to maintain “peace” between parties.

In conclusion the reverse RBAC model&#160; could be described like:

> If the parties are at the same level, in terms of control of the data of the SP we obtain a stuck position where anybody is enticed to act in a fraudulent manner or will be pushed back to a non-dominant position in the cloud ecosystem.

 [1]: http://en.wikipedia.org/wiki/Prisoner's_dilemma
 [2]: http://en.wikipedia.org/wiki/Role-based_access_control
 [3]: http://nebula.nasa.gov/
 [4]: http://nebula.nasa.gov/blog/2010/06/03/nebulas-implementation-role-based-access-control-rbac/
 [5]: http://www.thefreedictionary.com/ombudsman
 [6]: http://www.businessinsider.com/moodys-analyst-conflicts-corruption-and-greed-2011-8?op=1#ixzz2Asu7Ownu
 [7]: http://blogs.reuters.com/felix-salmon/2011/03/09/mckinseys-corrupted-culture/
 [8]: http://alfweb.com/blog/archives/156
 [9]: http://alfweb.com/blog/wp-content/uploads/2012/10/ombudusman.jpg
 [10]: http://alfweb.com/blog/wp-content/uploads/2012/10/ombudusman2.jpg
 [11]: http://alfweb.com/blog/wp-content/uploads/2012/10/ombudusman3.jpg