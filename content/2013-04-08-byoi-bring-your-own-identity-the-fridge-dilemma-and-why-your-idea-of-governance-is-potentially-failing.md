---
title: 'BYOI (Bring Your Own Identity): The fridge dilemma and why your idea of governance is (potentially) failing&hellip;'
author: Administrator
layout: post
date: 2013-04-08
url: /byoi-bring-your-own-identity-the-fridge-dilemma-and-why-your-idea-of-governance-is-potentially-failing/
categories:
  - BYOI
  - Cloud
  - Identity Management
  - Quest
  - Security
tags:
  - BYOI
  - Categorization
  - Classification
  - IAM
  - identification
  - identity management

---
_BYOI is a series I’ve decided to create to “talk” about #identitymanagement so it is about #security, #governance, #management and many other aspects of the #IAM realm._

_<img style="display: block; float: none; margin-left: auto; margin-right: auto;" alt="" src="http://farm3.staticflickr.com/2630/3979885054_5b8daf125d_o.jpg" width="426" height="320" />_

&nbsp;

In 2012 Ponemon Institue, LLC produced conducted a study on  662 companies to better understand the stat of the document-centric security, the results could be read__<a href="http://www.ciosummits.com/media/pdf/solution_spotlight/Ponemon%20White%20Paper%20FINAL.pdf" target="_blank"><em><span style="color: #000000;">here</span></em></a>.

In short what Ponemon Institute found out was that:

  * Ninety percent of organizations represented in this study experienced the leakage or loss of
  
    sensitive or confidential documents over the past 12-month period.
  * Seventy-one percent of respondents say that controlling sensitive or confidential documents
  
    is more difficult than controlling records in databases.
  * Seventy percent say documents accessed by mobile data-bearing devices such as smart
  
    phones and tablets present a significant security risk.
  * Seventy percent of respondents say that employees, contractors or business partners have
  
    very frequent or frequent access to sensitive or confidential documents, even though access
  
    to this information is not a job or role-related requirement.
  * Further, 59 percent say their organization’s controls are ineffective at monitoring employees,
  
    contractors or other insiders who access these confidential documents. An even higher
  
    percentage (63 percent) do not believe they are effective at assigning privilege to employees,
  
    contractors and other insiders whose job or role requires access to sensitive or confidential
  
    documents.

It’s quite impressive, is like if everybody knows that have an issue but feel unable to solve it completely. I am sure that many of you are aware of the risk and that exists software that can somehow avoid the loss of sensitive documents but the real question, that come out from the report is:

**_How much are we exposed? In terms of control we should first know where the “sensitve documents” are and then apply the mitigation controls._**

## The fridge dilemma

Let say that A,B e C are students and decide to share an apartment near the University.They agree to split the rent and the expenses but since all of them follow different courses and consequently different timeframes are not able to eat together at lunch or dinner. The rule is quite simple the fridge is a sharing place where everybody got it’s own space . A sharing space means that, as long as your “things” are identifiable nothing can go wrong but this is not a strict rule but more a common sense way of acting, it’s a fridge and I have my own “sector” so I do not need to place any “Identification” on my stuff if I don’t want. Let say that one day A and B decide to buys the same food from the same shop, let say it’s a salad with walnuts in it. Unfortunately B cannot eat walnuts because of allergy and so ask the shop to substitute them with some other fruit, apparently the two salads have no difference, same box, same brand on it, same “colors” and places in the fridge one near the other are really easy to be confuse one with the other.

Both A and B do not use to place identification on their stuff, after all they have their “place” in the fridge. A is in a rush because she’s running late to a course so open the fridge and grab the “salad”,obviously the wrong one.

So now B is exposed because without knowing it it’s “salad” has gone and if she will not put an adequate attention will get in trouble with his/her allergy. Using an identification label would solve the problem but since we are using a sharing, and consequently open, “space” we cannot guarantee  that everybody will follow the rule exposing themselves and others to a loss of <span style="text-decoration: line-through;">food (</span>information).

The fridge dilemma is not solvable because the only way to solve is to force “users” to label their documents based on standards and avoid them to “place” those documents on sharing “spaces” . The question is simple: how many of you have or know of a sharing space (ftp,sharepoint site,cloud folder,etc..) where everyone in the company can access without a real control?

My point is those “places” are the reality response to the excess of security. As  a customer of mine, recently in a discussion said:

> More often then one would like to think security is a  compromise

And he’s right..

## 

## Classification is not segregation

What do you know about your documents? Let me show you an extract from the Ponemon Institute report:

[<img style="background-image: none; padding-left: 0px; padding-right: 0px; display: inline; padding-top: 0px; border: 0px;" title="image" alt="image" src="http://alfweb.com/bg/wp-content/uploads/2013/04/image_thumb.png" width="644" height="406" border="0" />][1]

Ponemon Insitute, LLC &#8211;__[_<span style="color: #000000;">http://www.ciosummits.com/media/pdf/solution_spotlight/Ponemon%20White%20Paper%20FINAL.pdf</span>_][2]

The figure above shows what the respondents believe are the groups who really manage documents in the company but is even more impressive this graph:

[<img style="background-image: none; padding-left: 0px; padding-right: 0px; display: inline; padding-top: 0px; border: 0px;" title="image" alt="image" src="http://alfweb.com/bg/wp-content/uploads/2013/04/image_thumb1.png" width="639" height="255" border="0" />][3]

Ponemon Insitute, LLC &#8211;__[_<span style="color: #000000;">http://www.ciosummits.com/media/pdf/solution_spotlight/Ponemon%20White%20Paper%20FINAL.pdf</span>_][2]

This means that you  have no real control over what happen in your companies, especially if “this” happen outside the company boundaries like in the case of the mobile workforce. What we can do then? The answer is again in my  customer suggestion: compromise. One solution apparently would be &#8220;**segregation**” that means I do not allow users to download/upload any document when outside the company etc..but this would mean that I am not able to work anymore. Another rule would be to “**fully trust**” my users since as I often say “security is an habit” and so they are fully aware of the damage that placing a sensitive document may generate to the company.

> Ok I live in the real world too…

Here’s the compromise, stop thinking that governance must come always first, you cannot control what you don’t know and so, you have first of all to**  classify** what is on your network.

> **Document classification** or **document categorization** is a problem in library science, information science and computer science. The task is to assign a document to one or more classes or categories. This may be done &#8220;manually&#8221; (or &#8220;intellectually&#8221;) or algorithmically. The intellectual classification of documents has mostly been the province of library science, while the algorithmic classification of documents is used mainly in information science and computer science. The problems are overlapping, however, and there is therefore also interdisciplinary research on document classification.
> 
> The documents to be classified may be texts, images, music, etc. Each kind of document possesses its special classification problems. When not otherwise specified, text classification is implied.
> 
> Documents may be classified according to their subjects or according to other attributes (such as document type, author, printing year etc.). In the rest of this article only subject classification is considered. There are two main philosophies of subject classification of documents: The content based approach and the request based approach.

Classification definition (WIkpedia) &#8211;__[_<span style="color: #000000;">http://en.wikipedia.org/wiki/Document_classification</span>_][4]

**_The fridge dilemma cannot be solved because our student in a rush will continue to grab the wrong salad but at least we will know, before it happens, that there are two “similar” salad in our “fridge” and that it is important to maintain them separated and well labeled._**

&nbsp;

Now are you curious to know more about classification and how it works? just give me the time to write the next post.

 [1]: http://alfweb.com/bg/wp-content/uploads/2013/04/image.png
 [2]: http://www.ciosummits.com/media/pdf/solution_spotlight/Ponemon%20White%20Paper%20FINAL.pdf "http://www.ciosummits.com/media/pdf/solution_spotlight/Ponemon%20White%20Paper%20FINAL.pdf"
 [3]: http://alfweb.com/bg/wp-content/uploads/2013/04/image1.png
 [4]: http://en.wikipedia.org/wiki/Document_classification "http://en.wikipedia.org/wiki/Document_classification"