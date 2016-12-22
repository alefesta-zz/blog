---
title: 'BYOI (Bring Your Own Identity) : Sex Dolls vs. Real Women (aka should you trust what you trust?)'
author: Administrator
layout: post
date: 2012-12-12
url: /byoi-bring-your-own-identity-sex-dolls-vs-real-women-aka-should-you-trust-what-you-trust/
categories:
  - BYOD
  - BYOI
  - Cloud
  - Identity Management
  - Security
tags:
  - '#identitymanagement'
  - BYOD
  - BYOI
  - federation
  - identity management
  - infosec
  - login
  - social

---
_BYOI is a series I’ve decided to create to “talk” about #identitymanagement so it is about #security, #governance, #management and many other aspects of the #IAM realm._

The question is simple why do you trust “someone” or even better what makes you sure that you can trust a service/person/thing the way you trust them?

Recently I was reading an article written by [<font color="#3e372b">@johnfontana</font>][1] [<font color="#000000">“Trust will make or break cloud ID management services</font>”][2] on a podcast on security and trust framework at <font color="#000000"></font>[<font color="#000000">kupperingcole</font>][3]&#160; <font color="#000000"></font>[<font color="#000000">“Identity Management as a Service (IdMaaS) &#8211; the Dope or are we Duped?”</font>][4] <font color="#000000"></font>with [<font color="#3e372b">@kimcameron</font>][5] and Chuck Mortimore (salesforce.com).

One of the points&#160; that make me think&#160; from the article of @johnfontana was:

> “Where we have seen trust frameworks be really successful in the past is where member organizations have some means and motivation for cooperation be that altruistic, economic, etc.,”

### What is Trust?

A common definition of trust is:

> In a social context, trust has several connotations. Definitions of trust typically refer to a situation characterised by the following aspects: One party (trustor) is willing to rely on the actions of another party (trustee); the situation is directed to the future. In addition, the trustor (voluntarily or forcedly) abandons control over the actions performed by the trustee. As a consequence, the trustor is uncertain about the outcome of the other&#8217;s actions; he can only develop and evaluate expectations. The uncertainty involves the risk of failure or harm to the trustor if the trustee will not behave as desired.

wikipedia – “trust (social science)”

So we have basically two actors: the trustor (**tR**) and the trustee (**tE**) where the level of trust (**loT**) is based on a simple formula:

**if&#160; tE[App(loT)]>App(loT) then tR(trust)tE**

<font color="#000000">where <strong>App(loT)</strong> is the service/application the <strong>tR</strong> will use. If the app/service provided by the <strong>tE</strong> satisfy all the security requirements of <strong>tR</strong> than probably it will start to use it against the same kind of app/service not provided by any “compliant” entity.</font>

<font color="#000000">This is a simple visualization/definition of trust, <strong><em>we start to rely&#160; on the action of another party if and only if, this party, is able to satisfy our expectation.</em></strong></font>

<font color="#000000">Based on this definition&#160; social single sign in is a technological solution that could works in the “cloud age” and enable users to access to application/services provided by different party as long as:</font>

  * _<font color="#000000">The Corporate who I’m work for trust the “social service” I rely to logging in.</font>_ 
  * <font color="#000000"><em>The “Corporate” I work for is in my list of <strong>tE</strong> (trustee) entities</em></font> 
  * <font color="#000000"><em>The “Social service” provided is in my list of <strong>tE</strong>(trustee) entities</em>.</font> 

if all the above questions are satisfied I’ll use the service trusting the entire " **chain**”.

### The definition of Trust

But what is really trust? My concern is how I apply the above definitions of Trust in real life? Do I trust anyone in this way?

I thank @johnfontana for another tweet ispiration:

[<img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: inline; border-top-width: 0px; border-bottom-width: 0px; border-left-width: 0px; padding-top: 0px" title="image" border="0" alt="image" src="http://alfweb.com/blog/wp-content/uploads/2012/12/image_thumb.png" width="502" height="212" />][6]

in case someone do not know to what SCotUS (Supreme Court of the US) refer in the tweet&#160; here’s the <font color="#000000"></font>[<font color="#000000">link</font>][7]

Before, we said that**&#160; tR** trust the **tE**&#160; based on an **evaluation of the service expectations** and if, and only if, those are satisfied then ****will start to use the service.

But we also seen that in a Social/Federated ecosystems there are multiple **tR**&#160; actors (the end user and the corporate) and multiple **tE** actors (the corporate and the Social service Provider).

So our (as end user)**&#160; loT (Level of Trust)** it is could be based only on two approaches:

  * _**tR(loT)** for Corporate (**tEC**) is highly enough but still require the same level for Social (**tES**)_ 
  * _**tR(loT)**&#160; for Corporate(**tEC**) is highly enough that **do not require** futher investigation/action toward Social (**tES**)_ 

based on this approach even if the technological aspects of a federated login tell us that the “transmission” is secure enough we must look at the behavior of our actors to understand which service offer and how to offer it.

So the trust is indeed something that

> <font color="#333333">can’t explain it to you, but I know when I feel it</font>

### The Sex doll

What is a sex doll?

> A sex doll (also love doll or blow up doll) is a type of [sex toy][8] in the size and shape of a sexual partner for aid in [masturbation][9]. 
> 
> The sex [doll][10] may consist of an entire body with face, or just a pelvic part, with the accessories ([vagina][11], [anus][12], [mouth][13], [penis][14]) for [sexual stimulation][15]. The parts are sometimes vibrating and may be removable or interchangeable.

<font color="#000000">Let me change a little bit the first sentence to help you to see my point: …is a <strong>type</strong> of <strong>service </strong></font>that could be **similar** to the one offered by a **trusted** service provider (the woman)… 

it’s an obvious question but: why you prefer a real woman to a sex doll? 

If you look at it from a different perspective (I’m adding a bit of humor so please no offense here) a sex doll: 

  * is secure : you have total control over her/his sex life 
  * is always approachable: normally do not say “no” to your approaches 

You have total control over it so makes the **sex doll** definitely a better choice over a real woman. 

So why you still find more appealing the **real woman (or man)** to the sex doll?&#160; After all we are saying that there is an higher risk of being “exploited” by another human than a plastic toy. 

> so from the **tE/tR** point of view the sex doll is more secure than a real woman(man)

<font color="#000000">There are many studies on human behavior in social environments that could “easily” answer to the questions above and one of them found produced an interesting result.</font> 

<font color="#000000">From “Trust, gullibility, and social intelligence” written by Toshio Yamagishi and Masako Kikuchi</font> 

> <font color="#000000">…</font> 
> 
> A series of experiments conducted in Japan by Yamagishi and his associates are presented, all consistently showing that high trusters (as measured with a general trust scale) are more sensitive than low trusters to information potentially revealing lack of trustworthiness in others and judge other people’s choice in a one-shot prisoner’s dilemma more accurately.

>      <font color="#000000"></p> 
> 
> <p>
>   …When opportunity cost for staying in a commitment <br />relation is generally high, it is more advantageous not to stay in secure and stable commitment relations but to explore opportunities that lie outside, and yet such social exploration involves the risk of being exploited by untrustworthy people…
> </p>
> 
> <p>
>   </font>
> </p>
> 
> <p>
>   <font color="#000000">in other words we tend to choose the <strong>service</strong> based on a simple opportunistic behavior that could lead us to the risk of being exploited.</font>
> </p>
> 
> <h3>
>   The real woman
> </h3>
> 
> <p>
>   So I’m an end user (<strong>tEE)</strong>&#160; and my Corporate (<strong>tEC)</strong> offer me a new service (<strong>tES</strong>) to login into Corporate Apps from my BYOD/COPE device.
> </p>
> 
> <p>
>   Based on what we said above I should check both the <strong>tEC</strong>&#160; and <strong>tES</strong> security frameworks and decide to use both (the corporate ID and the social ID) applying the same level of security (frequency of the password change, complexity, etc…).
> </p>
> 
> <p>
>   But since I’m an opportunistic <em>animal<strong> </strong></em>I probably do a simple consideration:
> </p>
> 
> <p>
>   <strong>tEC trust tES =tEE trust tEC (tES)</strong>
> </p>
> 
> <p>
>   where
> </p>
> 
> <p>
>   <strong>tEC(loT) guarantee tES(loT)</strong>
> </p>
> 
> <p>
>   <font color="#000000">based on this last formula I, as end user, will do not take too much attention to the social service password and will probably no change it too much, since the <strong>sex doll</strong> offered to me seems secure enough to use it but unfortunately what I do not noticed is that it is not a <strong>sex doll</strong>&#160; but a<strong>&#160; real woman</strong></font>
> </p>
> 
> <p>
>   <font color="#000000">As example<font color="#000000">:</font><a title="http://www.wired.com/gadgetlab/2012/08/apple-amazon-mat-honan-hacking/" href="http://www.wired.com/gadgetlab/2012/08/apple-amazon-mat-honan-hacking/"><font color="#000000">http://www.wired.com/gadgetlab/2012/08/apple-amazon-mat-honan-hacking/</font></a></font>
> </p></blockquote> 
> 
> <p>
>   <font color="#000000">What all this means that even in a techno-digital-social world a human will continue to apply the same “rules” and “behaviors” of a <em>real</em> social interaction.</font>
> </p>
> 
> <p>
>   <font color="#000000">Will trust a subject and somehow will assume that that another entity, presented by the first subject could be trusted because of the highly level of trust between him/her and the first actor.</font>
> </p>
> 
> <blockquote>
>   <p>
>     <font color="#000000">Based on this (wrong) assumption instead of apply a #security #habit will reduce his attention to the second entity trusting that could not make harms to him/her in anyway (wrongly again).</font>
>   </p>
> </blockquote>
> 
> <p>
>   To conclude don’t trust your sex doll if she can speak and argue with you all the time…it’s a real woman (man).
> </p>

 [1]: https://twitter.com/JohnFontana
 [2]: http://www.zdnet.com/trust-will-make-or-break-cloud-id-management-services-7000006705/
 [3]: http://www.kuppingercole.com
 [4]: https://www.kuppingercole.com/watch/idmaas_dope_or_duped
 [5]: http://twitter.com/Kim_Cameron
 [6]: http://alfweb.com/blog/wp-content/uploads/2012/12/image.png
 [7]: http://en.wikipedia.org/wiki/I_know_it_when_I_see_it
 [8]: http://en.wikipedia.org/wiki/Sex_toy
 [9]: http://en.wikipedia.org/wiki/Masturbation
 [10]: http://en.wikipedia.org/wiki/Doll
 [11]: http://en.wikipedia.org/wiki/Vagina
 [12]: http://en.wikipedia.org/wiki/Anus
 [13]: http://en.wikipedia.org/wiki/Mouth
 [14]: http://en.wikipedia.org/wiki/Penis
 [15]: http://en.wikipedia.org/wiki/Sexual_stimulation