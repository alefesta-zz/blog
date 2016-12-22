---
title: BYOI (Bring You Own Identity):To serve and protect (or not?)
author: Administrator
layout: post
date: 2015-01-13
url: /byoi-bring-you-own-identityto-serve-and-protect-or-not/
wp-to-buffer-success:
  - 1
categories:
  - BYOI
  - Life
  - Security
  - Uncategorized
tags:
  - BYOI
  - identity management
  - life
  - Security; BYOI;Strategy;Identity

---
_BYOI is a series I’ve decided to create to “talk” about #identitymanagement so it is about #security, #governance, #management and many other aspects of the #IAM realm._

> “We change our behavior when the pain of staying the same becomes greater than the pain of changing. Consequences give us the pain that motivates us to change.”   
> ― Henry Cloud

[<img title="36288_01_google_begins_encrypting_search_results_especially_in_china_full" style="border-top: 0px; border-right: 0px; border-bottom: 0px; float: none; margin-left: auto; border-left: 0px; display: block; margin-right: auto" border="0" alt="36288_01_google_begins_encrypting_search_results_especially_in_china_full" src="http://alfweb.com/bg/wp-content/uploads/2015/01/36288_01_google_begins_encrypting_search_results_especially_in_china_full_thumb.jpg" width="413" height="294" />][1]&#160;<a title="http://www.tweaktown.com/image.php?image=imagescdn.tweaktown.com/news/3/6/36288_01_google_begins_encrypting_search_results_especially_in_china_full.jpg" href="http://www.tweaktown.com/image.php?image=imagescdn.tweaktown.com/news/3/6/36288_01_google_begins_encrypting_search_results_especially_in_china_full.jpg" target="_blank">Tweaktown image</a>

I’m not going to write my first post of 2015 on what happened in Paris recently, neither want to introduce a new chapter on my blog post talking about politics but reading the news this morning I felt the urge to write this.

from the news this morning:

> The British prime minister David Cameron has suggested that if his Conservative Party wins the upcoming general election, it will not allow encrypted communications that cannot be read by the security services.
> 
> &#8211; [https://gigaom.com/2015/01/12/uks-cameron-wont-allow-strong-encryption-of-communications/][2]

that was immediately “linked” to:

> Vladimir Putin has promised a “comprehensive piece of legislation” to close the “safe spaces” used by suspected terrorists to communicate online with each other.
> 
> If he wins the election, Mr Putin said he would increase the authorities’ power to access both the details of communications and their content.
> 
> &#8211; [http://speakerschair.com/post/russia-s-snooper-bill-no-means-of-communication-which-the-government-cannot-read][3]

of course they are not the only two who will propose, and unfortunately, in some cases succeed down this path. This is a long time historical behavior as the incipit in this blog post says “consequences give us the pain that motivates us to change…”.

Let me try to put all this in context.

Security of people and as direct relation of nations are related to the capability of control who gets in and who act and how if one (the police) suspect this one may be a potential danger for the nation itself. 

In an old post of mine I used to associate a Swiss regulation date 1200 a.d to manage the common tenure of land ([http://alfweb.com/bg/byoi-bring-your-own-identity-the-curious-case-of-the-cow-the-cheese-makers-and-the-byod-policy/][4]) to the use of BYOD into corporate networks. The post was directly related on how introducing a regulation that was too strict or too loose ended up in a failure.

If we consider this to the public results of the “alcohol prohibition regulation” in US ([http://www.cato.org/publications/policy-analysis/alcohol-prohibition-was-failure][5]) we will notice that an excessive reaction to a problem lead, in the end to the failure of the policy itself.

#### why end-to-end encryption traffic is not the problem

> Let’s take this clear, the issue is not about the traffic itself but who is going to use it, period.

If I have to monitor 1500 suspect every single day in real time, the issue is not about what they use but how many resources I need to establish to be able to control them. It’s not about the volume of data that makes the difference but the quality we may obtain from it so in the very end what we really need is to put things in context and define a different strategy.

In another post I used the fuzzy square to define the risk analysis approach so I’ll make a new use of it to explain my point here.

Let say that monitor a suspect is, in the very end, a binary decision:

  * we will assume the value of 1 if a certain thing is going to happen
  * we will assume the value of 0 if a certain thing is not going to happen

based on this we have the following use cases:

  * the suspect will start offensive action
  * the location is known
  * the suspect will not start an offensive action
  * the location is unknown

as you may see the “provider” of the communication is not mentioned so far.

Our fuzzy square appear like this:

[<img title="Alessandro-Figure-3" style="border-top: 0px; border-right: 0px; border-bottom: 0px; float: none; margin-left: auto; border-left: 0px; display: block; margin-right: auto" border="0" alt="Alessandro-Figure-3" src="http://alfweb.com/bg/wp-content/uploads/2015/01/AlessandroFigure3_thumb.jpg" width="302" height="343" />][6]

we assume that our resources are in a number sufficient to control every single possibility that appears along the line. Now based on this what is&#160; the point below?

[<img title="Alessandro-Figure-4" style="border-top: 0px; border-right: 0px; border-bottom: 0px; float: none; margin-left: auto; border-left: 0px; display: block; margin-right: auto" border="0" alt="Alessandro-Figure-4" src="http://alfweb.com/bg/wp-content/uploads/2015/01/AlessandroFigure4_thumb.jpg" width="302" height="343" />][7]

If I am a you I would say that the most common sense hypothesis maybe:

  * the use of an end-to-end encryption transmission to communicate to the third party the location of the attack
  * the use of a new electronic identity to start the attack
  * the use of a location outside the nation boundaries to start the attack
  * the use of another attacker to start the real action 

may be one of this or even all of them, our square appears this way now:

[<img title="Figure-1" style="border-top: 0px; border-right: 0px; border-bottom: 0px; float: none; margin-left: auto; border-left: 0px; display: block; margin-right: auto" border="0" alt="Figure-1" src="http://alfweb.com/bg/wp-content/uploads/2015/01/Figure1_thumb.jpg" width="323" height="369" />][8]

The easiest path would be to ban all the potential threat like end-to-end encryption with only a small problem.

well let me use one of the most known quotes in the realm of security to explain this:

> <p align="center">
>   “Good luck, I’m behind 7 proxies”
> </p>
> 
> <p align="center">
>   &#8211; <a title="http://knowyourmeme.com/memes/good-luck-im-behind-7-proxies" href="http://knowyourmeme.com/memes/good-luck-im-behind-7-proxies">http://knowyourmeme.com/memes/good-luck-im-behind-7-proxies</a>
> </p>

<p align="left">
  banning a known transmission protocol or software will simply move the point from the perimeter to the center it’s a context shift not a solution.
</p>

<p align="left">
  If we add the variable of the “unknown” status simply restricting this to a specific context like end-to-end encryption transmission our square will appears like this:
</p>

<p align="left">
  <a href="http://alfweb.com/bg/wp-content/uploads/2015/01/context01.jpg"><img title="context01" style="border-top: 0px; border-right: 0px; border-bottom: 0px; float: none; margin-left: auto; border-left: 0px; display: block; margin-right: auto" border="0" alt="context01" src="http://alfweb.com/bg/wp-content/uploads/2015/01/context01_thumb.jpg" width="361" height="340" /></a>
</p>

<p align="left">
  Where the possible variables are:
</p>

  * <div align="left">
      I know the method
    </div>

  * <div align="left">
      I don’t know how to “read” the message
    </div>

  * <div align="left">
      I know how to “read” the message
    </div>

  * <div align="left">
      I don’t know the method
    </div>

<p align="left">
  It exist four context square of&#160; that have as center point the four angles of the fuzzy square. Based on this it’s clear that ban the method does not solve anything if not simply add more variables to control instead of reducing them. Like any “honey pot” if I subtract the attacker will add so my strategy should be not to restrict but to attract the attacker.
</p>

<p align="left">
  Based on the point we just reached we may understand now what we miss in the picture that is not the context but the behavior. I don’t know the method used but I know why an attacker should prefer a method against another. Like for the context a behavioral context square exist and solve the following use cases:
</p>

  * <div align="left">
      I know why the attacker should behave like this
    </div>

  * <div align="left">
      I don’t know why the attacker should behave like this
    </div>

  * <div align="left">
      I know when the attacker will behave like this
    </div>

  * <div align="left">
      I don’t know when the attacker will behave like this
    </div>

<p align="left">
  our square will seems like this now:
</p>

<p align="left">
  <a href="http://alfweb.com/bg/wp-content/uploads/2015/01/context02.jpg"><img title="context02" style="border-top: 0px; border-right: 0px; border-bottom: 0px; float: none; margin-left: auto; border-left: 0px; display: block; margin-right: auto" border="0" alt="context02" src="http://alfweb.com/bg/wp-content/uploads/2015/01/context02_thumb.jpg" width="444" height="380" /></a>
</p>

> <p align="left">
>   What demonstrate this? that it’s not about the number of resource or the level of restriction of the policy that will help, it’s a non solvable problem if approached this way. So our politics should start to look back at the history and learn from the past instead of blindly act in the urge to “fix” things.
> </p>

<p align="left">
  The freedom to communicate has an important value that is double linked to the freedom of expression and ban any free method of communication will simply lead people to find other “ways” like already happen with the various anonymous proxy, browser etc, helping, in the very end, the attacker strategy.
</p>

“We change our behavior when the pain of staying the same becomes greater than the pain of changing. Consequences give us the pain that motivates us to change.”   
― Henry Cloud 

<p align="left">
  &#160;
</p>

<p align="left">
  This quote is about change not restrict…it’s about find a way to change things not damage them.
</p>

<p align="left">
  sorry if this is not a proper post about identity management but just a rant, but in the end this is what about a blog..the freedom to rant sometimes.
</p>

 [1]: http://alfweb.com/bg/wp-content/uploads/2015/01/36288_01_google_begins_encrypting_search_results_especially_in_china_full.jpg
 [2]: https://gigaom.com/2015/01/12/uks-cameron-wont-allow-strong-encryption-of-communications/ "https://gigaom.com/2015/01/12/uks-cameron-wont-allow-strong-encryption-of-communications/"
 [3]: http://speakerschair.com/post/russia-s-snooper-bill-no-means-of-communication-which-the-government-cannot-read "http://speakerschair.com/post/russia-s-snooper-bill-no-means-of-communication-which-the-government-cannot-read"
 [4]: http://alfweb.com/bg/byoi-bring-your-own-identity-the-curious-case-of-the-cow-the-cheese-makers-and-the-byod-policy/ "http://alfweb.com/bg/byoi-bring-your-own-identity-the-curious-case-of-the-cow-the-cheese-makers-and-the-byod-policy/"
 [5]: http://www.cato.org/publications/policy-analysis/alcohol-prohibition-was-failure "http://www.cato.org/publications/policy-analysis/alcohol-prohibition-was-failure"
 [6]: http://alfweb.com/bg/wp-content/uploads/2015/01/AlessandroFigure3.jpg
 [7]: http://alfweb.com/bg/wp-content/uploads/2015/01/AlessandroFigure4.jpg
 [8]: http://alfweb.com/bg/wp-content/uploads/2015/01/Figure1.jpg