---
title: 'BYOI (Bring You Own Identity): nuclear identities'
author: Administrator
layout: post
date: 2015-11-04
url: /byoi-bring-you-own-identity-nuclear-identities/
categories:
  - BYOI
  - Identity Management
  - Life
  - Security
  - Unicorns
tags:
  - BYOI
  - idam
  - identification
  - identity management
  - IRM
  - unicorn

---
> You look at the floor and see the floor. I look at the floor and see molecules.
  
> Read more at  &#8211; Dan Aykroyd | Commedian

I’m actually using daily more than 10 digital identities, those are not my only ones but what I use most. I would claim that I have much more digital identities that I use so rarely that  are somewhat orphaned even if still attached to my persona.

There’s indeed a relationship between all these identities at some level, a relationship that vary from the number of links between them (the reason why the relationship exist),the force of attraction (the reason why the link is supposed to exist), the direction of the attraction (the reason why the identities are related each other).

If I look at this trying to draw a spatial representation of my identity relationship ecosystem I would have in first instance a probably define a set of particles of different size where the dimension define the utility of the identity itself.

[<img style="display: inline;" title="Presentation1" src="http://alfweb.com/bg/wp-content/uploads/2015/11/Presentation1_thumb.jpg" alt="Presentation1" width="516" height="427" />][1]

The identities would be attracted one to another by the utility exposed, as example: a social login authenticator link my primary identity to my social identity to allow me to proceed in the login authN/authZ process. The social login identity attract the primary identity in terms of direction but it is attracted back in terms of force of attraction (the needed in the end is to being authorized as primary identity ).

This define a better representation where the relationship is expressed in terms of nucleus containing  identities who “rotate” around each other based on the attraction force expressed.

[<img style="background-image: none; padding-top: 0px; padding-left: 0px; display: inline; padding-right: 0px; border: 0px;" title="CH4" src="http://alfweb.com/bg/wp-content/uploads/2015/11/CH4_thumb.gif" alt="CH4" width="510" height="421" border="0" />][2]

If I have a linked identity, one I link to my persona for a reason, I am instantiating a relationship with the identity and the services that this identity expose. The link produce invariably a force of attraction that is expressed by the main direction of the attraction, what the relationship is made of, how it was started. Let’s try to define a simple list of these possible combinations:

  * **persona to digital identity** : I create a new digital representation of myself to consume a service
  * **digital identity to persona**: a new digital representation of me is created and forced into link to my persona to consume the service
  * **digital identity to digital identity to persona**: the relationship in place between two different identities is transferred to my persona-to-identity new link to allow me to consume the service

I admit that the first two definition may fall into a sort of blurry line where is not clear which one is one case and which one fit the other. To explain I would assume that the direction is based on the attraction strength that the service that is going to be consumed will produce.

The strength is defined by any scale where the values are given by the inference of the following aspects:

  * **need** : The value vary based on the necessity of having the digital identity created to consume the service. More the service is “needed” greater the strength of the attraction between the person and the digital identity will be.
  * **desire**: we define “digital desire” as the need of link the digital identity to the persona because of the desire of have the service at disposal. Greater is the desire and greater will be the strength of attraction from digital identity to the persona.

It seem obvious that both of the strength indicators will exist in any combination digital identity/persona, to provide a simple example of this we may look at the follow use case:

As employee (persona) of company XYZ I am in the need of subscribe a federated service that allow me to use a mobile native app to manage my travels. The app require me to register my persona (digital identity). The need in a hypothetic scale from 1 to 5 will be probably between 3 and 5 due the fact that the app itself will offer me some advantages (link from persona to digital identity). The desire of have this app related to the same scale may subjectively move from persona to persona based on many other factors. i.e.:the app allow me to link my newly digital identity to my favorite social identity (relationship digital identity to digital identity) making  my life easier in terms of authN.

_The desire of having the app is determined by what my colleagues said about it, what I know about the app and any other subjective analysis I’ll do related to the desire of register myself._

Overall the direction and the strength between persona and digital identity will be clearly identified plus we will be able to identify  a second relationship that will be produced with an opposite strength (digital identity toward social login identity toward persona).

This second relationship will have indeed a lower strength because of the nature of the first relationship being consequently driven by the first and in the position where an explicit consent should be expressed in order to make the relationship continue to exist or, even better, to continue to exist in case of a dismissal of the first relationship.

Our first draw represented a set of particles that were not linked to each other but the above use case just showed us as if it exist a web of relationships that link one identity to the other pulling and/or pushing those particles.

This continuous movement produce invariably new relationships who modify the strength and the direction of every relationship. As example I am using nowadays a specific social login authenticator because of the fact that:

  * It’s what I use most (count you’re favorite social identity in the last 5 years and see if they are still the same)
  * It’s what is allowed to be used today (the service does not support another digital identity I’d like to use)
  * The digital identity I’d like to use to authenticate still not exist

We may represent this new combination of identities as the draw below.

[<img style="background-image: none; padding-top: 0px; padding-left: 0px; display: inline; padding-right: 0px; border: 0px;" title="pt-tl-complex" src="http://alfweb.com/bg/wp-content/uploads/2015/11/pt-tl-complex_thumb.gif" alt="pt-tl-complex" width="520" height="329" border="0" />][3]

One would be tempted to look at the persona as the center of this set of digital identities and consider it as the starting point of every single spin of the particles but this would be wrong. We may, indeed, assume that the persona is invariably the starting point of the other digital identities but than we have to look better at the direction and strength of the relationships. If we do so we will soon see that the “outer” relationship is usually driven by an “inner” relationship that define the set of initial identities that may be the persona itself or anything else.

> This nucleus produce a strength that attract other digital molecules of identities making possible for the nucleus itself to aggregate more identities and use/re-use them for different services.

A simple use case is the extension of our previous example:

The employee from XYZ company leave the company to move on on another job, the relationship between the persona and the digital identity defined by the app is broken but eventually will be transferred to the next company digital identity (changing the relationship direction from the need to the desire of having the same app). The authenticator used will be eventually dismissed in favor of another one  based on the fact that:

  * The app digital identity is producing a force of attraction that is greater than the need produced by the persona and from the capability of the social login identity.
  * If the app digital identity will introduce a new service (as use it to consume other services from other vendors) it’s force of attraction will probably establish new relationships between itself and the other digital identities.

What we should expect will be that in some of this identities will produce so much attraction force that will quickly collapse other digital identities in favor of themselves. This movement will always have as result that:

The nuclear identity will attract other identities till when it’s eventual force will be so great that invariably will start to implode in favor of a more distributed model. This behavior may be caused by different factors:

A new identity of the same force come in a collision course with the one we just described, the opposite force of attraction will produce a stall between the two nuclear identities and in the very end will let implode one of the two (i.e.: I’m decide to dismiss a service and all of its relationship in favor of another that seems more \_____ (insert your favorite choice)

The two identities do not produce any value in be used together and soon I’ll stop use both of them since I’ll be not able to recognize anymore their effective value. Even if I recognize that this explanation may sound a bit childish I have to remember that we as humans act more based on subjective decisions than through objective thoughts, and if you’re disagreeing with my last sentence please answer this simple question: Would you use Twitter or a PIN code to authenticate yourself to the online game platform? No matter what you’ll answer it will be anyway based not on data but on the perception of what I’ve just asked you, based on your knowledge of the three things I’ve mentioned, the background you have, etc.. (yes means even for you that answered “I would not log in”).

Where all these lead us? Well we just described a raw model that help use to define a map of  the relationships between us (persona) and all the other digital identities. We define the set of our digital identities as a nuclear identity that generate a self-inducted force of attraction that may be of help to describe our digital behavior. If I am able to define the, let’s call it” elements of the nuclear identities that compose my persona I’ll be likely in the position to define the expected behavior against certain combination of factors.

Exactly like  a sort of digital anthropologic study  I’ll be in a position to understand before hand what digital behavior will more impact a certain set of nuclear identities an  how to react in order to modify it (mitigation).

A simple but effective cognitive identity analysis

> You look at the floor and see the floor. I look at the floor and see molecules.
  
> Read more at  &#8211; Dan Aykroyd | Commedian

 [1]: http://alfweb.com/bg/wp-content/uploads/2015/11/Presentation1.jpg
 [2]: http://alfweb.com/bg/wp-content/uploads/2015/11/CH4.gif
 [3]: http://alfweb.com/bg/wp-content/uploads/2015/11/pt-tl-complex.gif