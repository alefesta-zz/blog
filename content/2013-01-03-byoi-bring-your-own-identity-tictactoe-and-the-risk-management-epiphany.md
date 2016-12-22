---
title: 'BYOI (Bring Your Own Identity) : Tic,Tac,Toe and the Risk Management Epiphany'
author: Administrator
layout: post
date: 2013-01-03
url: /byoi-bring-your-own-identity-tictactoe-and-the-risk-management-epiphany/
categories:
  - BYOD
  - BYOI
  - COPE
  - Identity Management
  - Life
  - Security
tags:
  - '#identitymanagement'
  - BYOD
  - BYOI
  - identity management
  - infosec
  - mobile
  - Security

---
_BYOI is a series I’ve decided to create to “talk” about #identitymanagement so it is about #security, #governance, #management and many other aspects of the #IAM realm._

[<img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: block; float: none; border-top-width: 0px; border-bottom-width: 0px; margin-left: auto; border-left-width: 0px; margin-right: auto; padding-top: 0px" title="Untitled" border="0" alt="Untitled" src="http://alfweb.com/blog/wp-content/uploads/2013/01/Untitled_thumb.jpg" width="343" height="278" />][1]

I’m sure everybody knows the game Tic,Tac,Toe (In Italy for, I don’t know which reason, it’s called “Tris”) . This is quite famous for being a typical example of zero sum game where there is often&#160; a no-winner situation, in other words this means that if both the player got the same knowledge of the game rules and, as it is obvious, try to achieve the dominant (winning) position will end up in a endless “no-winning” matches. There are many examples of zero sum like Tic,Tac,Toe in the Economics as in many other fields with the only difference that are not so easy to be immediately understood by the players and sometimes _won’t_ _be_&#160; understood by them.

The wikipedia definition of it says:

> Tic-tac-toe (or Noughts and crosses, Xs and Os) is a pencil-and-paper game for two players, X and O, who take turns marking the spaces in a 3×3 grid. The player who succeeds in placing three respective marks in a horizontal, vertical, or diagonal row wins the game.
> 
> …Despite its apparent simplicity, Tic-tac-toe requires detailed analysis to determine even some elementary combinatory facts, the most interesting of which are the number of possible games and the number of possible positions. A position is merely a state of the board, while a game usually refers to the way a terminal position is obtained.

wikipedia definition of “Tic,Tac,Toe”

I work for a company who’s #identitymanagement solution may, on the many things that the solution itself can do, assign weights to almost everything:employees,resources,rules,policies,etc in order to calculate almost automatically a risk index and consequently help the company to&#160; build a better&#160; risk management model. This is probably&#160; the right way to proceed if you have to handle the “_risk_” in your company, we all know that risk it’s not a fixed model but a variable one who must evolve/change dynamically day by day and adapt to every new change in the ecosystem.

> What I am saying anyway is that the _risk_ in it is to confuse **what is_&#160; risk management_** with **what is_&#160; manage risk_** and please excuse my game of words.

Risk Management got nothing to do with IDentity Management at least when you have to build the models who must be applied in the first instance to your ecosystems, it’s like to pretend that a car for the only fact that got brakes,airbags and safety belt is completely secure. I’ll try to explain the concept better through the last metaphor:

A car is secure because got brakes,airbags and (but not only) safety belts but require that:

  * _The safety furniture&#8217;s are tested and validated before the car is sold_ 
  * _The safety furniture&#8217;s satisfy the local and (in some cases) foreign regulations before the car is sold_ 
  * _The safety furniture&#8217;s are in number and&#160; of type able to protect the driver and the other persons in the car in case of accident_ 
  * _Your are able to evaluate all of the above compare them with your driver requirements and decide if they’re appropriate with “your standards”_ 

This is_&#160; risk management_&#160; and got nothing to do (directly) with the IDentity (the driver) and its behavior. We may said that:

The risk management try to identify the risk associated with the use of a specific device,resource,IDentity presenting to the corporate a “solution” that can guarantee from a security breach. As said “try” because have to use the information at disposal when the model is built.

As defined in ISO 31000:2009:

  1. _**identify, characterize threats**_ 
  2. _**assess the vulnerability of critical assets to specific threats**_ 
  3. _**determine the risk (i.e. the expected likelihood and consequences of specific types of attacks on specific assets)**_ 
  4. _**identify ways to reduce those risks**_ 
  5. _**prioritize risk reduction measures based on a strategy**_ 

A car is secure because got brakes,airbags and (but not only) safety belts but require that:

  * _the driver to pay an acceptable level of attention when is on the road_ 
  * _the driver have the correct knowledge of the driving procedures_ 
  * _the driver pay attention to the scheduled maintenance of the security devices/features of the car in order to be sure that they’ll works in the case of an accident_ 

This is_&#160; management of the risk_ and got almost all in common with the IDentity (the driver) and its behavior. We may said that:

The management of the risk allow the corporate to react in the case of a security breach and build its models on the analysis of the use made by the IDentities of the data,resources,apps etc..

_Risk Management_ is NOT a zero sum play because there are no players in it that try to achieve a dominant position. It is about to predict the behavior of users/resources in certain circumstances and can be done only through the knowledge of the&#160; variables in the game. _Management Risk_ is a cooperative n-player game where both the corporate and the employees try to achieve a dominant (winning) position with the intent of be more productive, work in a, apparently, better work environments, etc.. and so may end up in a _potential_ no-winning position (zero sum) like in Tic,Tac,Toe.

How this can happen? Let’s talk about enabling a user for #mobile work.

Let’s start with the first point:

“_identify, characterize threats”_ 

**What do we know?** User is going to use devices (not necessarly smartphones) out of our networks to access to _data_ **in** our networks.

**What do we expect?** Traditionally we tend to solve the challenge with a “VPN access” but this is not #mobile working since the concept behind it should be _“enable a user to access data without the need to be on the corporate network”_&#160; because you’re using a “device” that not necessarily is provided with a VPN application_._ I’m not saying that the VPN connection is not one of the solutions but since we are _building a risk management model_ we have to consider every variable and decide upon it.

This is an X somewhere in the 3&#215;3 grid of our Tic,Tac, Toe

[<img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: block; float: none; border-top-width: 0px; border-bottom-width: 0px; margin-left: auto; border-left-width: 0px; margin-right: auto; padding-top: 0px" title="1" border="0" alt="1" src="http://alfweb.com/blog/wp-content/uploads/2013/01/1_thumb.jpg" width="244" height="204" />][2]

_“assess the vulnerability of critical assets to specific threats”_

**What do we know?** Users are smart, more than what you may even think and they “talk”, a lot, tips&tricks got the same speed of Star Trek starship at warp speed. What does this means? if you try to lock them in they’ll find an escamotage to avoid security and try to get in the network corporate. You don’t believe me?google for “Shadow IT” and you’ll easily find out, on a more serious point of view it’s in the natural human behavior: we try to solve challenges finding alternative ways and if #security is not one of your habits then you’ll end up in troubles quickly.

**what do we expect?**We just said, “my corporate users are going to use devices that are not directly under my control” because of the privacy of a personal owned device, because of the Shadow IT,etc.. So how you may define what to expect? two main options:

  * Define a strict policy that allow you to implement a “control” over devices (only supported devices with a specific way to identify them are allowed on the corporate network) 
  * Define a more open policy that work on users “would like to have” request to avoid the use of un-controlled apps 

Still if the user is using a third party app for personal use can you control/predict to which data will access and how? You can continue to look at this from every angle but for every X there is an O on the grid for sure.

[<img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: block; float: none; border-top-width: 0px; border-bottom-width: 0px; margin-left: auto; border-left-width: 0px; margin-right: auto; padding-top: 0px" title="3" border="0" alt="3" src="http://alfweb.com/blog/wp-content/uploads/2013/01/3_thumb.jpg" width="244" height="214" />][3]

&#160;

_“determine the risk (i.e. the expected likelihood and consequences of specific types of attacks on specific assets)”_

**What do we know?**honestly what do you know about an un-managed device who allow a user to access to your corporate data?&#160; The challenge is not if you can control the end point but who is using it. It’s like to pretend to have control over the **bad** behavior of some users to talk loudly at the phone in public places about strategies and corporate reserved information’s.

**What do we expect?** It depends on the approach, my takes is that more you’ll be strict in terms of policies and controls more you’ll find a growing number of un-managed devices in your corporate network.So again if you sign an X you’ll get a O in return.

"_identify ways to reduce those risks” & “_prioritize risk reduction measures based on a strategy”__

I summed the last two points just to not bother you with an excessive long post.

**What do we know?** We know that our model is too variable to predict all the potential threat and so we have to accept and disclose it’s “lack of knowledge” with our company. Why? Because the old way to “hide our errors to management” doesn’t work at all and you should know it. Your C-level need to know you are able to react and&#160; you’re working of a strategy that leverage the “potential failure” to build a stronger model.

**what do we expect?** It’s a long play done match after match so as we seen before if both players are learning to play will end up in a zero sum game but is this a such a **bad thing?** honestly not, if my users are learning the game what they are learning is to manage the risk of making irresponsible moves and how this reflect on their working career , let say that is a learning path toward a better #security habit.

So in this case we see that our “first model” will be not a zero sum game since we knows already the moves of our users: they want us to help them providing:supported apps that make their work easier; they want to get into the network without over-complicated procedures : federated social login are there for this; they want apps not old-style web based application that doesn’t work on a 4-inch monitor device.

But what happen when from the _risk management_ we move to the_&#160; management of the risk_ model? We adapt to the changes but our challenger seems faster then us but as said before :

> my users are learning the game what they are learning is to manage the risk of making irresponsible moves and how this reflect on their working career , let say that is a learning path toward a better #security habit.

So every X is followed by an O and we got our zero sum game again..

[<img style="background-image: none; border-right-width: 0px; padding-left: 0px; padding-right: 0px; display: block; float: none; border-top-width: 0px; border-bottom-width: 0px; margin-left: auto; border-left-width: 0px; margin-right: auto; padding-top: 0px" title="6" border="0" alt="6" src="http://alfweb.com/blog/wp-content/uploads/2013/01/6_thumb.jpg" width="244" height="208" />][4]

To conclude_&#160; risk management_ is an helper to decide the best strategy for your IDentity management ecosystem and not only but cannot survive if not followed by a _management of the risk_ strategy who accept its potential breaches and who&#160; embrace the old Japanes proverb:

> Failure is the basis of success. (Meaning: Failure teaches us what actions should we change in order to achieve success.)(Jp: Shippai-wa seikou-no moto. 失敗は成功のもと。)

 [1]: http://alfweb.com/blog/wp-content/uploads/2013/01/Untitled.jpg
 [2]: http://alfweb.com/blog/wp-content/uploads/2013/01/1.jpg
 [3]: http://alfweb.com/blog/wp-content/uploads/2013/01/3.jpg
 [4]: http://alfweb.com/blog/wp-content/uploads/2013/01/6.jpg