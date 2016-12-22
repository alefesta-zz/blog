---
title: 'BYOI (Bring Your Own Identity) : What @bourdain knows about cloud that you don’t know'
author: Administrator
layout: post
date: 2012-10-30
url: /byoi-bring-your-own-identity-what-bourdain-knows-about-cloud-that-you-dont-know/
categories:
  - BYOI
  - Cloud
  - Identity Management
  - Security
tags:
  - '#identitymanagement'
  - cloud
  - governance
  - identity management
  - infosec
  - Security

---
_BYOI is a series I’ve decided to create to “talk” about #identitymanagement so it is about #security, #governance, #management and many other aspects of the #IAM realm._

I’ll be very straight on this if you’re asking me who’s the best chef on the entire universe I’ll answer [<font color="#000000">@Chef_Keller</font>][1] and I’m quite sure that [<font color="#000000">@Bourdain</font>][2] will not complain (too much) on my choice (in the remote case he will read this post).

But if you’re asking me about the only author that is able to give you the exact feeling of cooking in a professional cuisine (yes I did it even if I’m definitely far from being a cook)well that’s [<font color="#3e372b">@Bourdain</font>][2] (aka Anthony Bourdain). For those who don’t know Mr. Bourdain I strongly suggest to read “Kitchen Confidential”&#160; and all the other books he wrote but for the “simple” minds who simply desire a quickie I’ll share this :

> “Do we really want to travel in hermetically sealed pope mobiles through the rural provinces of France, Mexico and the Far East, eating only in Hard Rock Cafes and McDonalds? Or do we want to eat without fear, tearing into the local stew, the humble taqueria&#8217;s mystery meat, the sincerely offered gift of a lightly grilled fish head? I know what I want. I want it all. I want to try everything once.”   
> <font size="1">―</font> <font color="#000000"></font>[<font color="#000000" size="1">Anthony Bourdain</font>][3]<font color="#000000" size="1">, </font>[<font color="#000000" size="1">Kitchen Confidential: Adventures in the Culinary Underbelly</font>][4]

<font color="#000000">But what a chef-writer may know about Cloud that you don’t ? Let me rephrase my question: what do you know about a restaurant before get in and order from the menu? What do you know more after? What do you know about the same restaurant that make you decide to safely come back in and have another meal?</font>

<font color="#000000">Ok you’ll start to get the point I’m sure, yes it’s another post on #identitymanagement and #audit, #infosec but now, seriously, let me expplain my point:</font>

<font color="#000000">first of all let me give you an high level description on the organization of a restaurant related to a Cloud Ecosystem :</font>

[<img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: inline; border-top-width: 0px; border-bottom-width: 0px; border-left-width: 0px; padding-top: 0px" title="cloudrest" border="0" alt="cloudrest" src="http://alfweb.com/blog/wp-content/uploads/2012/10/cloudrest_thumb.jpg" width="497" height="296" />][5]

**Yourself/Customer:** The simple question is how power you have on what you’re going to eat? Basically you choose what you’d like to eat directly from the offered services (sometimes called Menu) and order them to the Waiter who will provide (lately) them to you.

**Menu:** as every restaurant/service provider you are “free” to choose what you want to eat/how/when/how often etc. The reality start to be a little foggy here since the question is: What do you know about the ingredients used in the meal preparation? what do you know about hygiene in the kitchen restaurant? Let me answer these questions later.

**Waiter:**The waiter is your transport, your connection point between the resources (food preparation in the kitchen) and what you ordered. If you are in a self-service food kind of of restaurant, you are the waiter of yourself and what you get is the sum of what you decided to put in your plate but, if you are in a Michelin 3 stars restaurant what you get is just the sum of the choices you did it through the menu and everybody there probably get the same kind of result. I’ll describe the correct mapping with the Cloud models later in this post.

**Kitchen:**What do you know about what is going to happen in the kitchen while you’re quietly waiting for your food? Are you aware of any regulation that prevent the restaurant to serve you a specific kind of food or a give quantity in a given time?

Let use going a little more into deep and start to map our example with our reality in cloud ecosystems.

First of all, **what do you know about your SP?** In terms of security certifications I’m sure your service provider will be always more than happy to share with you all the information regarding: level of certifications, when they get it and how are applied the phsical architecture, etc. but the point is:who may access to my data(food)? Can you, as SP, provide me a full audit report made by me or any other third party? it’s a legal question I know but not only, often the problem is more of, let me say, on the security technical side.The SP won’t let you “see” how is organized and how he manage your data for..for many reasons that I won’t to discuss now.

So back to our restaurant the question is the same: What do you know about your SP(Restaurant)? Let me share some example of things you should know and for sure [<font color="#000000">@bourdain</font>][2] knows about eating food in restaurants:

> The law in California states that for raw shell eggs that are prepared in response to a consumer&#8217;s order and for immediate service, the eggs must be heated to a minimum internal temperature of 145° F, or above for 15 seconds.&#160; If not for immediate service, such as for those sauces and dishes noted above, raw eggs and foods containing raw eggs must be heated to a minimum internal temperature of 145° F for three minutes, or 150° F for one minute, or 158° F for < 1 second. The other option the law allows is for pasteurized eggs to be substituted for raw eggs for these sauces and dishes.

[<font color="#000000" size="1">http://www.foodpoisoningprevention.com/Eggs.html</font>][6]

And

> This meat quality grade is given based on a combination of marbling and maturity. [Marbling][7] (or flecks of fat within the meat) adds flavor, and younger beef produces the most tender meat.   
> Therefore, the "prime" grade will be given to meat that comes from the youngest beef with the most abundant marbling.
> 
> Prime Meat: The Highest Quality
> 
> Less than two percent of all beef produced in the United States will earn the prime designation. You will probably never see prime meat for sale at the grocery store; rather, it tends to be purchased by high-end restaurants and hotels.

[<font color="#000000" size="1">http://culinaryarts.about.com/od/beefporkothermeats/qt/primebeef.htm</font>][8]

So my question is: how many of you control the real quality of the meat before eating and/or order? I mean I live in Italy and terms like “chianina”, “bue grasso di cavour”, etc.. denote a great meat but who guarantee me that what I’m going to eat is what is written on the menu? yes again we are into the legal question of trust my vendor/service provider but I am not into the position to obtain any answer to my query if not deferring the subscription and asking for an ombudsman to intercede for me.

I personally do not agree with the use of an ombudsman figure in identity management but this will be discussed in the next post.

> So the question is even with a third party are you able to get a full audit on the SP or simply you’ll have to relay on the certification and the legal agreement you have with it?

<font color="#000000">now again… how many of you got mayonnaise or food with eggs in it at a restaurant? how many of you may be sure on how these are being prepared? </font>

<font color="#000000">The thing is that between the tenant environment and the SP environment there is a clear separation that makes almost impossible to the tenant to know what happen “there” and who have “access” to the “eggs”, how are made or if some of them is&#160; not healthy. This is what I call “the restaurant dilemma” :</font>

> <font color="#000000">as in a restaurant I have to trust the SP based on legal agreement (the restaurant stays open if after a third party inspection everything is compliant with local regulations), the technical details that the SP decide to share with me (the menu details and what the restaurant decide to give me as details on food preparation) and the appeal derived by others recommendation. </font>

<font color="#000000">If I am a “customer” and I have to decide I should be in a position where I can ask at any time to “enter” to SP kitchen and check if everything is made as I desire.</font>

<font color="#000000">as <a href="https://twitter.com/Bourdain"><font color="#3e372b">@bourdain</font></a> says in “Kitchen confidential” </font>

> I never order fish on Monday, unless I&#8217;m eating at a four-star restaurant where I know they are buying their fish directly from the source. I know how old most seafood is on Monday &#8211; about four to five days old!
> 
> I don&#8217;t eat mussels in restaurants unless I know the chef, or have seen, with my own eyes, how they store and hold their mussels for service. I love mussels. But, in my experience, most cooks are less than scrupulous in their handling of them. It takes only a single bad mussel, one treacherous little guy hidden among an otherwise impeccable group &#8230; If I&#8217;m hungry for mussels, I&#8217;ll pick the good-looking ones out of your order.

[<font color="#000000" size="1">http://www.guardian.co.uk/books/2000/aug/12/features.weekend1</font>][9] 

<font color="#000000">And you? do you eat your cloud fish on Monday?</font>

 [1]: https://twitter.com/chef_keller
 [2]: https://twitter.com/Bourdain
 [3]: http://www.goodreads.com/author/show/1124.Anthony_Bourdain
 [4]: http://www.goodreads.com/work/quotes/4219
 [5]: http://alfweb.com/blog/wp-content/uploads/2012/10/cloudrest.jpg
 [6]: http://www.foodpoisoningprevention.com/Eggs.html
 [7]: http://culinaryarts.about.com/od/glossary/g/marbling.htm
 [8]: http://culinaryarts.about.com/od/beefporkothermeats/qt/primebeef.htm
 [9]: http://www.guardian.co.uk/books/2000/aug/12/features.weekend1