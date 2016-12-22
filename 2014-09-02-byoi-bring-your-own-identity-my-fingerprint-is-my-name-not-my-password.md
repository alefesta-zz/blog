---
title: 'BYOI (Bring Your Own Identity): My fingerprint is my name not my password'
author: Administrator
layout: post
date: 2014-09-02
url: /byoi-bring-your-own-identity-my-fingerprint-is-my-name-not-my-password/
wp-to-buffer-success:
  - 1
categories:
  - BYOI
  - Cloud
  - Identity Management
  - Internet of Things
  - IoT
  - Life
  - Security
  - Unicorns
tags:
  - Security; BYOI;Strategy;Identity

---
> <p align="center">
>   Do I contradict myself?…I contradict myself, I am large, I contain multitudes”
> </p>

Whitman (and with the courtesy of a suggestion in the #mobilebiz chat from Steve Wilson [[@Steve_Lockstep][1]])

It was a sort of epiphany. I was blogging about “[http://alfweb.com/bg/byoi-bring-your-own-identityaaaadaptive-authentication-and-authorization/][2]” , chatting in the #mobilebiz tweet chat (please see note at the end of this post) and reading some great papers on the “onion model” by Robin Wilton ([@futureidentity][3]) and I started to think about it.

If password are anymore secure and we need a replacement is there any chance we are failing at it? I’m not going to say that current state of security is failing just wondering are we looking at things from the right point of view.

[<img title="2013_1107_fingerprint-convenience" style="border-top: 0px; border-right: 0px; border-bottom: 0px; float: none; margin-left: auto; border-left: 0px; display: block; margin-right: auto" border="0" alt="2013_1107_fingerprint-convenience" src="http://alfweb.com/bg/wp-content/uploads/2014/09/2013_1107_fingerprintconvenience_thumb.jpg" width="345" height="243" />][4] 

Let me clarify. We use a combination of data in the authentication process: a username and a password. We already know that one single factor of authentication is not anymore secure or, at least desirable, so everyone tend to agree that we need of introduce a (at least) double factor of authentication.

Still we’re going to use combination of usernames and password, at least in one of the two factors of authentication. My opinion? It’s just a workaround mostly done because we (the community of digital users) are not able to define (yet) a better standard. Think at automotive and the use of keys, you don’t have a double key pair to open your car don’t you? And the car keys are not cutting your trousers anymore like they used to do (yes I’m older than what you think…) so the same level of “usability” but with a better “security” is somehow reachable. Okay I’m pity since I’m having a little joke of a complex problem but my thought were directed to a specific factor of authentication: biometrics.

I have a smartphone who allow me to authenticate using my fingerprints, it’s just a way to do it, easier and quicker than typing the “password”. There are many examples of biometrics who make use of different human “parts” from voice to the eye retina, from facial recognition to, as said, fingerprints.

It’s just one of the many ways to authenticate an identity and seemed one of the most secure until these days. No I’m not going to share any leak about some company biometric auth system hacked simply I am considering&#160; the world we are living.

First what is a biometric information. Is it a unique identifier? Let me tell you quietly:

> <p align="center">
>   NO!
> </p>

<p align="left">
  What make you think that your eyes retina or the fingers or any other part of your human body (voice and DNA included) are unique and not clonable?Dolly the sheep anyone (<a title="http://en.wikipedia.org/wiki/Dolly_(sheep)" href="http://en.wikipedia.org/wiki/Dolly_(sheep">http://en.wikipedia.org/wiki/Dolly_(sheep)</a>)?
</p>

<p align="left">
  So what make you think that anyone cannot clone your data with a 3D printer and use it against your secure system? yes I said 3D printer and cloning what? a yes my fingerprint.
</p>

<p align="left">
  “but my dear Alex you have to get my finger print first!”. Do you have a tables, a smartphone anything touchable? do you use some nice screen protection over there, maybe that nice obfuscating screens protection to avoid anyone to read your important data. So if I steal that do you think I may find a good sample of your finger print over that?
</p>

<p align="left">
  Yeah sure chances are that you registered a finger that you’ll not use over the tablet, after all “security is a habit” but well, soon or later, the phone need to be unlock while driving or while your hands are busy so you’ll end up registering your thumb or the index finger and bam! I got them.
</p>

> <p align="left">
>   Eyes? James Bond movies for that.
> </p>
> 
> <p align="left">
>   Voice? I know some 15 y/o kids who may do magic with a recorder and a mix
> </p>
> 
> <p align="left">
>   DNA? Dolly the sheep showed more than 20 years ago that anything is not anymore unique and by the way neither the snow flakes.
> </p>

<p align="left">
  Okay I’ll play fair nothing of the potential attack I described are easily to be done but, in the end, is there any cyber-attack that is “easy” and so has not been tried in the past?
</p>

<p align="left">
  So what’s the point? Well the point is the same with the text password. What makes the text password so successful?
</p>

<p align="left">
  Are those unique? well not exactly but are uniquely chosen and kept (or should be kept) in the best vault ever…your brain. Yes if like me your brain is not smart you’ll probably use a software to keep your password and again, do you trust this company that offer you to store your password? Is is so secure to relay on a third party to get your own password if in the end those must be used anyways? My company and I personally am a specialist of a solution that, manage the password of the so called privileged accounts (aka password safe) but still the question is there? isn’t it just a workaround to not type the password and let something else do it on your behalf?
</p>

<p align="left">
  The text password was and still is so successful not because of its strength but because is easy to remind in other word is an information that stay with us always. In the very beginning of the information tech era the password where a very well know information&#8217;s of our own so isn’t it your fingerprint the same?
</p>

<p align="left">
  Think about it:
</p>

  * <div align="left">
      It is always with you
    </div>

  * <div align="left">
      it does not guarantee or should not guarantee you to log in but just to be recognized: if the fingerprint is recognized that probably is you and you may proceed with the “password”
    </div>

  * <div align="left">
      it is unique (if not when an attacker try to clone it of course)
    </div>

<p align="left">
  Sound like…like..oh well do you have an ATM card? yes a pin code associated to a ATM card works almost the same way:
</p>

  * <div align="left">
      You have the card always (or almost always) with you
    </div>

  * <div align="left">
      the PIN code says that since you have the card and you know the PIN code associated with it you’re mostly who you said you are
    </div>

  * <div align="left">
      it is unique..since nobody else should have your ATM card physically
    </div>

<p align="left">
  it’s a well-known model and it is around since many years so I simply thinking at a similar model but where I won’t use my biometrics for authentication but for authorization.
</p>

<p align="left">
  Let imagine something like this:
</p>

  * <div align="left">
      A user use it’s biometrics to start an auth-N process
    </div>

  * <div align="left">
      A sub-process alert all the apps/services who may be provide federate Auth-N consequently to the correct access (pre-Auth-Z)
    </div>

  * <div align="left">
      User is requested to “create” the token for the temporary access (will post lately a model on this)
    </div>

  * <div align="left">
      The token exchange auth-N metadata with the Auth-N IDP and provide authentication (this could be a local process or a remote one)
    </div>

  * <div align="left">
      The apps combine the token and the “username” and provide a pre-Auth-N (if needed aka the user call the app)
    </div>

<p align="left">
  Biometric is the center of an “onion” and I really need to thank Robin Wilton to share to me his onion model that was revealing.
</p>

> <p align="center">
>   Do I contradict myself?…I contradict myself, I am large, I contain multitudes”
> </p>

Whitman (and with the courtesy of a suggestion in the #mobilebiz chat from Steve Wilson [[@Steve_Lockstep][1]])

<p align="left">
  Note: <a href="https://twitter.com/search?q=%23mobilebiz">#mobilebiz</a> tweet chat is hosted by <a href="https://twitter.com/bmkatz">@bmkatz</a> and <a href="https://twitter.com/PaladorBenjamin">@PaladorBenjamin</a> every Thursday at 1PM EST, 10AM PST
</p>

<p align="left">
  &#160;
</p>

<p align="left">
  &#160;
</p>

<p align="left">

 [1]: https://twitter.com/Steve_Lockstep
 [2]: http://alfweb.com/bg/byoi-bring-your-own-identityaaaadaptive-authentication-and-authorization/ "http://alfweb.com/bg/byoi-bring-your-own-identityaaaadaptive-authentication-and-authorization/"
 [3]: https://twitter.com/futureidentity
 [4]: http://alfweb.com/bg/wp-content/uploads/2014/09/2013_1107_fingerprintconvenience.jpg