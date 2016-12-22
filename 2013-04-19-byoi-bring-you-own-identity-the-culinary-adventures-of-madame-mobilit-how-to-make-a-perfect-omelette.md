---
title: 'BYOI (Bring You Own Identity): The culinary adventures of Madame &ldquo;Mobilit�&rdquo;-How to make a perfect omelette'
author: Administrator
layout: post
date: 2013-04-19
url: /byoi-bring-you-own-identity-the-culinary-adventures-of-madame-mobilit-how-to-make-a-perfect-omelette/
categories:
  - BYOD
  - BYOI
  - COPE
  - Identity Management
  - Security
tags:
  - idam
  - identity management
  - infosec
  - mim
  - mobile

---
_BYOI is a series I’ve decided to create to “talk” about #identitymanagement so it is about #security, #governance, #management and many other aspects of the #IAM realm._

> The difficulty with all written recipes for omelets is that before you even start to make one you must read, remember, and visualize the directions from beginning to end, and practice the movements.
> 
> _Julia Child_

INGREDIENTS

  * 3 large eggs
  * 2 teaspoons whole milk
  * 1/4 teaspoon kosher salt
  * 1/8 teaspoon freshly ground black pepper
  * 1 tablespoon unsalted butter
  * 1 teaspoon finely chopped fresh herbs, such as parsley, chervil, or chives, plus more to garnish

> An omelet should be a pale yellow, fluffy, delicate bundle—not the dry and chewy, massively stuffed piles you’ll find at the diner. Omelets are not difficult to make: All you need is the right pan, enough butter, and some wrist dexterity. Fill this basic omelet with just about anything, and serve it for a satisfying breakfast or lunch with a salad.

chow.com &#8211; Recipe for a Basic Omelette _<span style="color: #000000;">(</span>_[_<span style="color: #000000;">http://www.chow.com/recipes/29547-basic-omelet</span>_][1]_<span style="color: #000000;">)</span>_

Theoretically make omelets for the skilled cook should be a simple factor of mix the eggs with the milk and the other minor ingredients, the result is guarantee and will satisfy the critical palates as the more accommodating giving back to the cook an equal pleasure knowing that he/she get the expected results. Sometimes for some  reasons  often drive the inexperienced cook  will try to add more ingredients to this simple recipe ending up in a different result that could be summarize in the image below:

<img style="display: block; float: none; margin-left: auto; margin-right: auto;" alt="" src="http://api.ning.com/files/p6R5OhkiVDBcmEzX841dbhLKxY3D9V44AZx*59PqE2CW5Y4azhNcRaG37F65Wu-OBRzSfiAHUCWMmFGbRBhMBZ**lZT5yNjH/stephenwildish04.jpg" width="506" height="478" />

<p align="left">
  Image: “ Stephen Wildish” &#8211;<em><a href="http://stephenwildish.co.uk" target="_blank"><span style="color: #000000;">http://stephenwildish.co.uk</span></a></em>
</p>

<p align="left">
  It’s quite obvious that the golden rule of “less is better” it’s applicable to this recipe. Indeed adding some flour will add an extra taste to the eggs but will result in a pancake  as the lack of the eggs will give us lovely pasta totally unusable for the omelette.
</p>

<p align="left">
  It’s a matter of balance: too many ingredients or too less will drive the inexperienced cook to a different result from the one expected.
</p>

<h2 align="left">
  On #IDAM,#MIM and the “secret ingredient”
</h2>

<p align="left">
  Let’s us assume that our ecosystem it’s nothing more than our critical palate to satisfy. It is obvious that we have first of all to understand what our host desire. Thinking that  only the omelette or the pasta or the batter to do some fried vegetable (in example) could not be a choice made only by us.
</p>

<p align="left">
  In the ecosystem exist many actors:
</p>

  * <div align="left">
      The cooks : it’s those who setup the recipe, who choose the ingredients and decide how to mix them to gain the result requested
    </div>

  * <div align="left">
      The waiters: those are the frontend of the restaurant ecosystems, they monitor the <em>customers</em>  to understand if the delivered food is at the expected level, they understand the the <span style="text-decoration: line-through;">business</span> customer request, they suggest options, side dishes and <span style="text-decoration: line-through;">add-on’s</span> beverage to customers in order to make their experience pleasant.
    </div>

  * <div align="left">
      The customers: those who choose from the menu, reading between the lines of it making in their head a list of expectation that vary from the experience of the whole dinner or simply in the choice of a single dish. Some of them will accept the waiter suggestion other will simply request a specific mix of <span style="text-decoration: line-through;">features</span> food and drink .
    </div>

<p align="left">
  Some LOB look at <em>the cooks</em> as a <em>simple</em> bunch of operators who put together technology and offer a, more or less, solution. <em>The cooks, </em>too often, look at the <em>customers</em> like if they are some <em>tasteless</em> individual unable to understand the complexity and beauty of the technological ecosystem. Let say we look at the #BYOD wave or at the #dataclassification discussions (<a href="http://www.ascrewsloose.com/2013/04/10/being-eaten/" target="_blank"><em><span style="color: #000000;">here</span></em></a>) and we will immediately get the picture:
</p>

> <p align="left">
>   if we give too much <em>freedom</em> to a<em>  non-technological</em>  approach the risk is to get in a endless loop made by: understanding the information, design the right process to manage it, define the boundaries of the process,etc..
> </p>
> 
> <p align="left">
>   if we give too much<em>  freedom</em> to a <em>technological</em> approach the risk is to get a working rule that do not satisfy our customers in terms of: usability,scalability,etc..
> </p>

<p align="left">
  and then there is the<em>  <strong>data and the many ways to  access to it</strong></em><strong>.</strong>
</p>

<p align="left">
  In a recent conversation  between me, Brian Katz (<a href="https://twitter.com/bmkatz" target="_blank"><em><span style="color: #000000;">@bmkatz</span></em></a>) and Paul Madsen (<a href="https://twitter.com/paulmadsen" target="_blank"><em><span style="color: #000000;">@paulmadsen</span></em></a>)  on #dataclassification and the ways to use #IDAM and/or #MIM to manage the data a simple question raised a bigger problem. The questions/statements were:
</p>

> <p align="left">
>   <span style="color: #000000;">Employees identity (and keys) should drive a) what apps they can have b) what data they can access and c) protection of stored data &#8211; @paulmadsen</span>
> </p>
> 
> <p align="left">
>   <a href="http://twitter.com/paulmadsen"><span style="color: #000000;">@paulmadsen</span></a><span style="color: #000000;"> true : a) & c) are easily done if b) is known, but if b) is not structured/known you have to use</span><a href="http://twitter.com/search?q=%23IDAM"><span style="color: #000000;">#IDAM</span></a><span style="color: #000000;"> (MIM) . </span><a href="http://twitter.com/search?q=%23new"><span style="color: #000000;">#new</span></a><span style="color: #000000;"> </span><a href="mailto:-@festaatdell"><span style="color: #000000;">-@festaatdell</span></a><span style="color: #000000;"> (me)</span>
> </p>
> 
> <p align="left">
>   <a href="http://twitter.com/FestaAtDell"><span style="color: #000000;">@FestaAtDell</span></a><span style="color: #000000;"> but IDaM =\= MIM but rather a necessary component</span><a href="http://twitter.com/bmkatz"><span style="color: #000000;">@bmkatz</span></a><span style="color: #000000;"> </span><a href="mailto:-@paulmadsen"><span style="color: #000000;">-@paulmadsen</span></a>
> </p>
> 
> <p align="left">
>   <a href="http://twitter.com/paulmadsen"><span style="color: #000000;">@paulmadsen</span></a><a href="http://twitter.com/FestaAtDell"><span style="color: #000000;">@FestaAtDell</span></a><span style="color: #000000;"> Agreed &#8211; although if you follow the example, all the elements are there for MIM &#8211; @bmkatz</span>
> </p>
> 
> <p align="left">
>   <span style="color: #000000;">…</span>
> </p>
> 
> <p align="left">
>   <a href="http://twitter.com/FestaAtDell"><span style="color: #000000;">@FestaAtDell</span></a><span style="color: #000000;"> what role does MIM play for browser apps? Are we done with them? </span><a href="mailto:-@paulmadsen"><span style="color: #000000;">-@paulmadsen</span></a>
> </p>
> 
> <p align="left">
>   <span style="color: #000000;">…</span>
> </p>
> 
> <p align="left">
>   <a href="http://twitter.com/FestaAtDell"><span style="color: #000000;">@FestaAtDell</span></a><span style="color: #000000;"> &#8216;answer&#8217; is to redefine MIM so includes rules over a) release of data (whether to browser/app) & b) protection of stored data </span><a href="mailto:-@paulmadsen"><span style="color: #000000;">-@paulmadsen</span></a>
> </p>

<p align="left">
  So here’s my doubt is through a redefinition of a single <em>ingredient</em>  that we will find the “answer”? Do we have to focus on the single<em>  ingredient</em> or we have to better understand what the combination of more than one will give us as a result?
</p>

<p align="left">
  Let see my  point of view on the omelet.
</p>

<p align="left">
  <a href="http://alfweb.com/bg/wp-content/uploads/2013/04/Presentation1.jpg"><img style="background-image: none; padding-left: 0px; padding-right: 0px; display: block; float: none; margin-left: auto; margin-right: auto; padding-top: 0px; border: 0px;" title="Presentation1" alt="Presentation1" src="http://alfweb.com/bg/wp-content/uploads/2013/04/Presentation1_thumb.jpg" width="500" height="425" border="0" /></a>
</p>

So the _ingredients_  are:

> _Users:_ because they must be managed. CRUD activities are something you cannot avoid..it’s not a matter of what you use or what they need ..it’s a matter of YOU have to manage them somehow.
> 
> _Device:_ Like the users you have to manage them and what is worse is that the world is now more complex. What is a device after all? a tablet? a phone? a browser app? a cloud service? the boundaries are thinner day after day
> 
> _Data:_ I already posted about_  data classification_ and will do again. The point is _data_ is again something you got in your ecosystem and you have to manage them too but there are many approaches and many ways to get them.

&nbsp;

So let’s mix a bit the ingredients:

> #IDAM: I placed IDAM between devices and users. My opinion is that could stay in the middle of the Venn diagram but it is even correct that #IDAM itself cannot manage some specific kind of combination (like browser app data access cases).

So the recipe is simple but what if you decide to add a little bit of #DATA in it?

Well if the DATA is  device agnostic so probably you obtain some #IAG but if you need to discriminate if the #DATA must be access from a #DEVICE or another then…well…here’s the second recipe:

> #MIM: I have some Users who access to their data from a mobile device or a cloud/app service..and somehow I have to manage them. My approach is DATA centric but I am aware of the device…what I consider as marginal is the user. this is not wrong or right is just a different way to look at the things.Different ingredients, different results or maybe same results.

&nbsp;

The point is what I have to use when I’m in a situation where I want to use all the ingredients at the same time?

_My “answer” is…don’t try to mix the recipes, you don’t have to redefine the results neither you have to change the ingredients, you just have to use the right recipe with the right mix of ingredients. And please, listen to the customers they know what they want  and some of them are really well schooled on food and wine…after all even cooks must eat sometimes._

&nbsp;

The difficulty with all written recipes for omelets is that before you even start to make one you must read, remember, and visualize the directions from beginning to end, and practice the movements.

_Julia Child_

 [1]: http://www.chow.com/recipes/29547-basic-omelet