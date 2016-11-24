---
layout: post
title: The economics of domain names
tags: [economics, domains, domain names, udrp, cybersquatting, ICANN, dns, singularities, bargaining, uncertainty, anonymity, negotiation, policy, game theory, network effects, trust, psychology, search costs, judgement devices, market value, seller motivation, allocation, auctions, auction theory, acpa, endowment effect, ethereum, whois, whois privacy, domain industry]
excerpt_separator: <!--more-->
---

**Thomas Clowes, 2016.**

This paper looks at the domain name system in its current form (July 2016), and investigates the relevant economics.

An overview of the system is provided, details of relevant economic theory are outlined, important literature is considered, and proposals for the development of the system going forward are discussed.

<!--more-->

## Contents

* [Introduction](#introduction)
* [What are domain names?](#what-are-domain-names)
* [The domain name market](#the-domain-name-market)
  - [Mediums of exchange](#mediums-of-exchange)
  - [Allocation](#allocation)
  - [Recent developments](#recent-developments)
* [Economics, Sociology, and Behavioural Economics](#economics-Sociology-and-Behavioural-Economics)
* [Economic considerations](#economic-considerations)
  - [Market value](#market-value)
  - [Seller motivation](#seller-motivation)
  - [Bargaining for domain names](#bargaining-for-domain-names)
  - [Lets play Chicken](#lets-play-chicken)
  - [Auction theory](#auction-theory)
  - [Network Effects](#network-effects)
  - [The Endowment Effect](#the-Endowment-Effect)
* [Valuing a domain name](#valuing-a-domain-name)
  - [Singularities](#singularities)
  - [Judgement devices](#judgement-devices)
  - [Search costs](#search-costs)
  - [Uncertainty](#uncertainty)
  - [Get a broker](#get-a-broker)
  - [Speculation and ignorance](#speculation-and-ignorance)
  - [Comparing domain names](#comparing domain names)
* [Game Theory](#game-theory)
* [Trust](#trust)
* [Policy and practice](#policy-and-practice)
  - [The requirement for law](#the-requirement-for-law)
  - [Does it work?](#does-it-work)
* [Fixing the domain name system](#fixing-the-domain-name-system)
* [Moving forward](#moving-forward)
* [Replacing the domain name system](#replacing-the-domain-name-system)
  - [Decentralise](#decentralise)
  - [Ethereum](#ethereum)
  - [The Bandwagon Effect](#the-Bandwagon-Effect)
* [Conclusions](#conclusions)
* [References](#references)

## Introduction

The development of the Internet over the past 30 years has resulted in things that no-one would have considered possible becoming commonplace, and ‘normal’ aspects of modern day life. In 1985 one would have never imagined that 30 years later we would be sharing photographs with people on the other side of the planet. Likewise, the idea that you could ‘crowdsource’ funding for your fantastic invention, ‘Google’.. anything, or purchase a job lot of used hard drives from a stranger in Camden would have seemed completely alien.

Whilst the Internet has created a number of fascinating areas for economic research and analysis (crypto economics for example), this paper will focus on one particular market - the market for domain names. In the grand scheme of things domain names.. and their market are relatively unknown. Unless you have had a particular need to purchase a domain name it is highly likely that you were not even aware that such a market exists. You may not even be aware as to what a domain name is.

This paper will look at the market for domain names and consider the economic phenomena that relate to it. How does one purchase a domain name from its owner? To what extent do game theoretical negotiation practices create a new and unique market?
I will consider as to whether domain names (and their market) are ready for a more widespread public adoption (and understanding), or if domain names have in fact had their heyday without ever hitting the primetime. Is something new going to replace domain names, and if so what, and why? What can web 3.0 learn from the domain name system?

## What are domain names?

A domain name is a string of characters, which map to a particular Internet Protocol (IP) address and which are easier to remember then a string of numeric characters. For example http://google.com is a domain name which maps to the IP address 216.58.213.110. 

The domain name system is managed by the Internet Corporation for Assigned Names and Numbers (ICANN) which delegates registration responsibilities to domain name registrars such as GoDaddy.com, Uniregistry.com, and Moniker.com. 

The format of a domain name is a series of alphanumeric characters followed by a Top Level Domain (TLD). TLDs can be broken down further to generic TLDs (.com, .net, .org) and country code TLDs (.uk, .cn, .tc). 

More recently (over the past three or so years) a large number of additional gTLDs have been released covering all sorts of different categorisations and industry areas. For example, you can now register a .link domain name, a .accountant domain, or even a .sexy domain name.

Domain names are scarce, because they are unique. In a given TLD domain, a given combination of characters (be it a brand name, or an acronym) can only be registered once. 

If a domain name has not been registered, an individual or business can register the domain (through a registrar), for a registration fee (this fee varies for different extensions); for example the .com TLD is approximately $10, whereas a .accountant domain name costs $100 per year. An annual maintenance (renewal) fee is then required to maintain the registration. 

If the domain name is already registered, one must approach the current owner and negotiate a deal. It is generally possible to discern who owns a domain name by looking in the WHOIS database which is a database that lists the registration information pertaining to a particular domain name registrant.


Domain names are a form of intangible asset (“assets which have long term value but no physical identity”) which materialised in 1985, when the domain name nordu.net was registered for usage as the first root server. Over the past 30 years, with the growth of the Internet, the significance and relevance of domain names has changed dramatically. 

Originally a company named Network Solutions was the sole administrator of domain registrations, however over the years, the creation of ICANN introduced competition into the registration process by separating the registry (central database), and registrar (registration) businesses. In 1999, ICANN began providing accreditations for new registrars. This eliminated the previous monopolistic position of Network Solutions (Chander (2003)), by allowing the development of competition within the registrar side of the business.

With the release of the new gTLDs there has been further development in the registry and registrar space. A small number of new registrars have popped up including for example 101domain.com which has carved out a niche targeting the sale of registrations in the large number of now available gTLDs. 

One further prominent example of the differentiation between registry and registrar is that of Uniregistry and Uniregistrar. The former is the registry that manages a number of new gTLDs (for example .link), whilst the latter is a registrar providing registration services for those new extensions (as well as those managed by other registries).

I wrote in 2012 for a piece entitled “Developing a new system for the economically efficient allocation of domain names” (from which parts of this introduction are taken) that “there is an active market for the purchase, sale, and resale of domain names for the intrinsic value which they can add to a business”. In 2016 this is still the case. More-so in fact as a result of increased interest in the market from investors in China (to be discussed), and the release of thousands of new gTLDs (as mentioned above).

Back in 2012 ex-ICANN chairman Peter Dengate Thrush stated that the domain market 

> “is worth about $12bn” and “will expand by some $3-4bn with the new gTLDs”. 

Four years on it is unclear as to exactly the value of the new gTLD market but data taken from [ntldstats.com](http://ntldstats.com) (on 5th February 2016) suggests that **12,048,313**  new gTLD domain names have been registered in over **899 different extensions**. That is not an insignificant amount (although it pales in comparison to the **124,000,000** plus .com domain names that were registered as of January 2016)11.

Given these considerations, like many asset classes (for example stocks, bonds, and foreign exchange) a market has developed to facilitate domain name exchange. In 2012 the [IDNX](http://idnx.com) index of domain valuations as was listed on Bloomberg and Reuters respective financial index web pages – domains were serious considerations financial investment. The IDNX index had not been updated since the end of 2014 (when checked on 5th February 2016) which begs the question “Does a market for domain names still exist in 2016?”

## The domain name market

The domain name market is a catch all term for the market that exists for the resale of previously registered domain names.

Unlike many other asset classes, the domain name marketplace is not regulated per se. As a result some domain names have been registered by individuals in an attempt to profit from others who value the domain more highly. For example 'cybersquatters' register domain names containing brand names and/or trademarks and then attempt to sell them back to the companies in question at highly inflated prices. The cost of cybersquatting is (according to the Coalition Against Domain Name Abuse (CADNA)):

> “over $1 billion U.S. dollars every year as a result of diverted traffic, the loss of hard-earned trust and goodwill, and the increasing enforcement expense of protecting consumers from Internet-based fraud.”.

This aspect of the domain name market is one reason why many consider the release of new domain name extensions to be a bad thing [49](#Reference49) - it *“is a headache for IP holders that are burdened with the task of protecting their brand by defensively registering domains”*.

Whilst often times domain names are purchased to develop a website on or to resell for an assumed profit, there is also another reasoning - parking. Domain name parking refers to the situation whereby a domain name owner displays advertisements on their domain name from which they earn an income should any visitor visit and click. Online advertising is a massive topic in and of itself - revenues can be yielded per click, per impression, or per sale. The latter has the potential to generate significant revenues. Should you own a domain name like insurance.com on which you display adverts for insurance companies, a single click could yield a significant sale (of which which you get a percentage).


### Mediums of exchange

There are many mediums through which sales can be completed, as outlined below.

*List 1: A summary of the mediums of exchange present in the current domain name market.*

* **Direct contact**

A traditional barter transaction where an interested buyer contacts the owner of the domain, and they negotiate a suitable price for the domain on the basis of the relative willingness to pay/accept of each respective party.

* **Drop markets**

Whereby a previously registered domain is allowed to expire by its registrant. The moment the domain is deleted from the central registry’s database, companies running very powerful computers repeatedly query the registry to attempt to 'instantly' register the deleted domain. If *caught*, the domain is then sold via an auction process, or kept. An oligopolistic market has developed for drop catchers whereby a few large companies control the industry. Snapnames, and Namejet, two large players in the industry have recently combined offerings.

* **Forum markets**

A traditional barter transaction which occurs through online forums. A seller quotes how much they want for a particular domain, and buyers haggle around that price until a deal is agreed. One particularly popular forum through which many transactions occur is [NamePros](http://namepros.com). 

There are other smaller and no longer active forums such as [DNForum](http://dnforum.com), and [Domain State](http://domainstate.com) where a large number of transactions occurred. 

Localised forums also exist, for example [Acorn Domains](http://acorndomains.co.uk) which serves the .uk market.

* **Auction markets**

The sale of a domain through an auction based process organised through a broker. For example SeDo.com

* **Live auctions**

The development of the ‘domain name industry’ over the years has resulted in the development of a number of domain name conferences. [Namescon](http://namescon.com) for example holds a live auction at their event each year.

Likewise, large auction houses (for traditional assets) such as [Heritage Auctions](http://ha.com) have entered the space, semi regularly auctioning off premium domain name assets in live auction events.

### Allocation

As the market for domain names grew, it became important to consider their allocation, to try to prevent acts of *cybersquatting*, and *typosquatting* (the process by which typos of a popular domain are registered to try and profit from visitors who inadvertently mistype a website address).  

In 1999 the World Intellectual Property Organization (WIPO) introduced the Anti Cybersquatting Protection Act (ACPA), and The Uniform Dispute Resolution Policy (UDRP) systems to aid in the efficient allocation of domain names to those with suitable property rights. 

Sharrock (2001) outlines the development of the ACPA in 1999 as *“...statutory protection developed to protect mark holders from cybersquatting”*, as it was felt that the specific framework for dealing with trademark dilution cases was not suitable. She also outlines the creation of the UDRP as a contractual provision for mandatory arbitration down the line should a ‘rights holder’ complain about a registration.

### Recent developments

As of the end of 2015 the domain name market has had one other significant boost - China. With the volatility of the Chinese stock market, a lot of money has been flowing from China into domain names. On December 19th 2015 the first “Domain Day of China” took place. At that event $24.1 million was invested in domain names (yao.com, and banana.com sold to name a few). Events like this do not however emphasise the significance of domain name transactions that occur as a result of direct contact/negotiation. In that same period a large volume of short domain names (two/three/four letter .com domains) have been sold to Chinese investors at vastly increased prices relative to those being attained one year previously.

## Economics, Sociology, and Behavioural Economics

During this same 30 year period (over which the Internet has developed), there have been a lot of developments within the fields of Economics and Sociology. So as to make this essay as accessible as possible, I have briefly outlined the nature of each respective subject matter below.

**Economics** is the oldest of the aforementioned social sciences. It pertains to the study of economic actors and how they act in relation to *"the production, distributions, and consumption of goods and services"* (Wikipedia). 

**Sociology** is *younger*. Whereas Economics focusses on *how* resources are allocated, Sociology considers the effect of that allocation on the individual, and society as a whole. It is also broader in its nature - that is to say, it considers all social relationships, and asks a wider range of questions. For example, *How does the way that women are portrayed on television affect the way women are seen in society?* Cain (2008)

Economics often applies statistical analysis to problems based on assumptions made about the sociological world. In their nature, there is a large crossover between both disciplines. 
Whereas Sociology is often happy to qualitatively analyse a particular subject, Economics is more likely to ask questions such as *Given the following assumptions, what happens to X when we manipulate Y*. One of these assumptions tends to be that of *rational actors* - the suggestion that the actors involved will always inherently act rationally. As will be seen below, this is not necessarily always the case.

**Behavioural Economics** is a sub discipline of Economics that has risen to prominence over the past decade. It relaxes the assumption of rational actors. It is patently apparent that in reality there are situations whereby one may not necessarily act rationally - impulsive buying for example. Behavioural Economics investigates *the effects of social, cognitive and emotional factors on the economic decisions of individuals and institutions and the consequences for market prices, returns and the resource allocation”* (Wikipedia).

Behavioural Economics is a more recently developed subject area. It is in my opinion easily definable as *a more realistic and all encompassing approach to the analysis of economic problems*.

This author highly recommends the work of both Dan Ariely and Daniel Kahneman for anyone interested in reading further into Behavioural economics, its development, and its applications.

## Economic considerations

This section will briefly outline some economic concepts/theories that in this authors view are relevant to any discussion on the economics of domain names.

### Market value

Her Majesties Revenue and Customs (HMRC) here in the UK state in statute (that relates to tax submissions) that in a number of situations it is appropriate that *things* be transferred at *market value*.

It is this authors view that HMRC bases these requirements off of the universal assumption of economic actors being representable as *Homo economicus* as opposed to *Homo singularis* or something different.

Homo economicus refers to your stereotypical human who is self interested and always acts rationally. As alluded to previously, in reality homo economicus does not exist, yet when it comes to defining terms such as market value some simplifying assumptions must necessarily be made.

As will be seen throughout this paper, different economic theories have a basis in different economic schools of thought. Not all these theories or schools are compatible, and often times a number of contradictory explanations are put forward to explain different phenomena.

Economics is not a science with easily definable and verifiable answers to questions. As such one must accept and appreciate the simplifications made when defining terms.

The line that HMRC takes as regards market value (at least as it relates to capital gains valuations) is that outlined by Lord Justice Hoffman in the case of IRC v Gray (1994) STC 360. He states 51:

*“the theme which runs through the authorities is that we assume that the hypothetical vendor and purchaser did whatever reasonable people buying and selling such property would be likely to have done in real life. The hypothetical vendor is an anonymous but reasonable vendor, who goes about the sale as a prudent man of business, negotiating seriously without giving the impression of being either over-anxious or unduly reluctant. The hypothetical buyer is slightly less anonymous. He too is assumed to have behaved reasonably, making proper enquiries about the property and not appearing too eager to buy. But he also reflects reality in that he embodies whatever was actually the demand for that property at the relevant time. It cannot be too strongly emphasised that although the sale is hypothetical, there is nothing hypothetical about the open market in which it is supposed to have taken place. The concept of the open market involves assuming that the whole world was free to bid and then forming a view about what in those circumstances would in real life have been the best price reasonably obtainable.”*


### Seller motivation

This author defines seller motivation as the extent to which a seller is prepared to entertain any and all offers for a given domain name asset.

In a 1995 paper entitled “Selling price and selling time: The impact of seller motivation”, Glower et al looked at how seller motivation affects selling prices within the market for real estate. 

The domain name market draws a number of parallels with the real estate market in that there is a limited supply of *good* domain names in *good* areas (popular and well respected namespaces).

There is also the similarity in that often real estate is marketed and sold utilising the services of a broker - an individual with market experience who knows how to find the right buyers, at the right price level. Domain brokers are a prominent part of the domain name sales market, and will be discussed in more depth below.

They posit that sellers who are motivated to sell will be indicated by a lower point on the time/selling price schedule. That is to say that as motivation to sell decreases, and time to sale increases, the selling price trends upwards. They verify this suggestion using statistical regression based analysis. 
One could perform a similar statistical analysis of the domain name market but due to a lack of data and an interest in keeping this paper purely qualitative I have chosen not to. It is also the case that a large proportion of domain name sales go unreported (although the exact number is impossible to discern), and as such any statistical analysis would be extremely restricted in its validity.

It is however not simply a case of seller motivation that leads to the outcomes that we see within the domain name market. A lack of obviously discernible valuation criterion for domain names, and a lack of *real* expertise means that one cannot utilise statistical analyses appropriately and that past a point guesswork is required. Rationality is necessarily impossible.

One respect in which the domain market and the real estate market diverge significantly is costs. Owning a domain name has negligible costs associated with it (a single annual registration fee is the only necessary cost), whereas holding real estate can incur significant costs - the costs of maintaining multiple mortgages, the emotional and physical cost (i.e stress) associated with the complexities involved in property sales and so on.

Glover and Haurin outline four hypotheses from which we can draw equivalents within the domain name market. They are:

<table>
<tr>
<th>Real estate</th>
<th>Domain names</th>
</tr>

<tr>
<td>Sellers with a definite move date will sell sooner and at a lower price.</td>
<td>Domain owners who need to release capital will sell sooner and at a lower price.</td>
</tr>

<tr>
<td>Sellers who have listed their house for sale due to a job change or who have made an offer on another house will list lower and sell faster and for a lower price.</td>
<td> Domain owners looking to purchase an alternative domain will list lower and sell faster and for a lower price.</td>
</tr>

<tr>
<td>Sellers with over-priced houses will sell less rapidly and for more.</td>
<td>Domain owners with over-priced domains will sell less rapidly and for more.</td>
</tr>

<tr>
<td>Sellers with atypical houses will sell more slowly and at a higher price.</td>
<td>Domain owners with atypical domains will sell more slowly and at a higher price.</td>
</tr>
</table>

Given the insignificant costs of domain name upkeep, one would postulate that subject to the irrelevance of the former two hypotheses, domain names will be inherently over-priced, and as a result sales would take a longer time to complete. That is to say, a domain name owner who is not in need of money would rationally over-price their domain name and simply wait.

Notice that I do not necessitate an equivalence between a *house seller* and a *domain seller*, but rather a *house seller* and a *domain owner*. The reason for this linguistic difference is that it seems reasonable to suggest that the entities who bought domain names back in the early 90s did not purchase them with the intention of selling them on at vast profit. It is likely that they were purchased with the intent of building a web presence on a cool, quirky, memorable domain name utilising a new and relatively unknown technology.

Given these parallels with the domain name market, perhaps domain name owners can take further insight from other papers on the topic when developing their sales strategies. 

Angline, and Webe (2011) investigated houses that have been sold twice by different sellers to investigate how listing price effects selling prices. They found that overpricing by 1% increased sales price by around 1% ceteris paribus. 

Whilst not necessarily pertaining to overpricing, [NameBio](http://namebio.com) (a service which reports historical domain name sales) reports on domain names that have been sold twice (or more) in a section of its blog entitled ‘[Domain Discoveries]( (https://namebio.com/blog/category/domain-discoveries/))'.
Many realise significant short term (depending on your definition) profits *reselling* domain names whilst others have taken significant losses. Whilst one can not definitively state the reasoning behind these cases, it seems highly plausible that it comes down to the sellers *motivation* to sell (personal situation etc) at the time.

Yavas, Miceli and Sirmans (2002) found that *“higher initial bid price by a buyer or a
higher initial asking price by a seller raised the final selling price*. As a seller it is easy to see that you would not wish to start too low and have your initial offer instantly accepted. As a buyer this discovery introduces some interesting behavioural considerations - exactly how high do you start?

This more generally opens the door for the game theoretical considerations associated with negotiating for domain names. This is discussed below.

### Bargaining for domain names

Wikipedia defines ‘bargaining’ as *a type of negotiation in which the buyer and seller of a good or service debate the price and exact nature of a transaction*. It is obviously apparent that for a domain owner to sell their domain name a bargaining process must occur.

Muthoo (2001) defines a bargaining situation as a situation in which *“two or more players have a common interest to co-operate, but have conflicting interests over exactly how to co-operate”*.
If for example a domain seller were to value their domain name at $5,000 and the potential buyer valued the domain name at $6,000, then any deal whereby the price is between $5,000 and $6,000 would be mutually beneficial. Independent of that however Muthoo points out that often in pursuit of a bargaining position that is in their own favour some deals often fail. 

She notes that a players bargaining power is higher the less impatient they are. Poverty is often correlated with impatience, and as such poverty can weaken ones bargaining position.

A further consideration within a bargaining situation is the availability of *outside options* which Cunyat (1998) describes as *the best option available elsewhere*. In relation to the domain name market a seller may have an *outside option* in the form of another offer. Their *inside option* may be the revenues yielded from *parking* the domain name. 

Cunyat also discusses the credibility of outside options which is of course an important consideration. Given the anonymity often associated with transactions conducted through the Internet it is important that you can *believe* what the other party is telling you.

Compte and Jehiel (2000) have written an interesting piece on *‘bargaining with obstinate parties’* which again has relevance when either party to a transaction can hide behind an email service and thus be as obstinate as they wish without damaging their reputation. The takeaway is that *“outside options are quite effective at cancelling out the effect of obstinate types in bargaining”*, yet these papers do not consider the behavioural aspects associated with anonymity.

A lot of the issues that domain name bargaining situations encounter pertain to *information asymmetry*. This refers to a situation whereby the balance of power within a negotiation is affected by the amount of knowledge that each party to a potential transaction has. If a potential domain buyer could verify that a domain owner had previously received offers in excess of theirs (outside options), it would surely affect the way in which they negotiate. On the other side of the coin, the fact that normally other offers can not be verified results in less trustworthy buyers altering their negotiation strategies.

Weber (1978) outlines how *“Action is instrumentally rational when the end, the means, and the secondary results are all rationally taken into account and weighed*. The problem however is that in reality the availability of information does not permit one to consistently act rationally. Furthermore (as alluded to previously) it is not to be taken for granted that even with all of the information available one would choose to act rationally.

### Lets play Chicken

A very basic application of game theory is the game of chicken whereby two cars drive towards one another. Each driver has the option to swerve away and avoid a collision but should they do so they are declared a chicken.

During negotiations for a domain name one or both parties can refuse to swerve. That is to say that they will not increase their offer/decrease their asking price respectively even if they are currently in a mutually beneficial bargaining position.

The problem with the domain name market is the lack of information asymmetry. *Ownership* of a domain name is to all extents and purposes simply indicated by the presence of the owners contact information within the WHOIS database. This information can be incomplete, completely falsified, or hidden by a domain name owner.

On the other end of the negotiation is the buyer - an entity who has the power of anonymity bestowed upon themselves by the very technology which resulted in the creation of the market - the Internet. Should I (as a perspective buyer) want to purchase a domain name, I can contact the *owner* via email or phone and be as anonymous as I wish to be. This is relatively unique to the domain name market. Disney can now become a poor student from a poor area looking to acquire a domain name for *their* personal blog.

This fact alters the game of chicken because optimal strategy within a game of chicken can be affected by knowledge of the other player. As outlined by Butts (2010) you can ‘win’ a game of chicken against a powerful opponent who is trying to strong arm you by utilising knowledge of them to your advantage.

As such, the level of asymmetric information effects bargaining position quite significantly within the domain name market.

### Auction theory

One way to reduce the issues associated with information asymmetry is the auction. An auction format can be utilised which allows for any/all potential buyers to have an opportunity to purchase a given domain name in the context of relatively complete knowledge of the characteristics that make the domain name valuable.

I will outline four prominent auction formats that have been developed by economists. The formats are:

* **Ascending bid auctions**

Participants place bids in an open and transparent environment. The highest bidder wins.

* **Descending bid auctions**

The bidding starts at a high level (where no-one will bid). The price is then decreased until it reaches a point at which someone is prepared to pay.

* **First-price sealed bid auctions**

Participants make a sealed bid. The winner (highest bidder) pays the price of their bid.

* **Second price sealed bid auctions (Vickrey auctions)**

Participants make a sealed bid. The winner (highest bidder) pays a price equivalent to the second highest bid.


From a strategic point of view, first price sealed bid auctions can be shown to be strategically equivalent to descending bid auctions (Karni et al (1988)), whilst second price sealed bid auction are strategically equivalent to ascending bid auctions (Levin (2004)).

There is however a further consideration for a given auction outcome, namely as to whether it is a *common value* auction or a *private value* auction. The domain name market is interesting in that a particular auction for a domain name can be either. 

The former represents the case when all bidders involved have the same information available to them that is pertinent for developing their own individual valuation. In the case whereby all the bidders are *investors*, information that will allow them to value the domain name (for example search counts, the extension, and the length) are all freely available. Furthermore tools such as Estibot collate a large number of relevant data points such that the *cost* of acquiring such data is negligible.

If however one bidder in an auction is an *end user* the auction could take on a *private value* nature. In this case the end user has additional private information that affects their own personal valuation. If for example they are purchasing the domain name to build a business or a brand upon, they may value the domain name further. They may consider the value of brand protection, the value of future potential revenues and so on.

The problem with common value auctions is the *Winner’s curse* which is the name given to the phenomenon whereby in an auction the winner will tend to overpay. This occurs because of imperfect information as well as (extremely prevalently in the domain name market) emotions and ego.

Because of the difficulty in assigning a valuation to a domain name (to be discussed further below) it is highly plausible that a bidder could overpay in a domain name auction. Take for example the following situation:

A bidder in an auction notices that Mr Successful (a highly successful domain investor) has placed a bid that was higher than their initial reservation bid within the final few minutes of the auction. The auction is extended for a further ten minutes. Noting that Mr Successful values the name at such a value makes you reconsider your own valuation - in the heat of the moment, under the pressures of time you decided to increase your bid once again. In reality Mr Successful had no additional information, and was constructing a valuation based on the same available information. Perhaps the only fundamental difference was the fact that Mr Successful can afford to be less risk averse - *“risk-aversion makes bidders bid more aggressively in first-price auctions”* (Klemperer (2004)). Unfortunately you have now overpaid.

### Network Effects

Network effects are an interesting economic phenomenon whereby the value of something is effected by the number of users utilising it.

In the case of ‘The Internet’ one could generally state that it is a valuable resource because a lot of the world population use it (and as such a lot of useful information etc. can be found on it).

Likewise, at a lower level domain names only have value because people use them. Dot com domain names have the highest values because it is the extension most widely known, understood, and accepted.

The market for domain names only appeared as a result of the positive externality created by mass adoption of the Internet. If people did not use domain names then logically they would have little value.

Network effects are extremely significant in the context of changing or replacing the domain name system simply because there will necessarily be a ramp up period for any new or updated technology. Until people transition to a new or updated system, it does not provide value for the masses.

To draw comparisons, if a new social network were to be developed to compete with Facebook it is unlikely that you would use it if none of your friends did - it would not be very social. That said, Facebook itself managed to essentially replace MySpace within the social network space, and thus it is certainly possible that significant change **can** occur.

The problem that arises here is that the consumers of the Internet (the general public) significantly outweigh the producers of content, and providers of resources on the Internet. Any changes to the ways in which we provide information online may well provide benefits to providers (and better economic allocations), but if it is the consumers that create the value in any given system such changes may not be successful.

### The Endowment Effect

A number of the explanations for this effect are incompatible with explanations that suggest that bargaining should always *work* and yield good economic outcomes. It is for this reason that often times we see negotiations that should *on paper* work break down.

The endowment effect (or status quo bias) describes the situation whereby someone values an item significantly more highly as a result of their ownership of the item. That is to say that even though they may only be prepared to pay $100 to acquire a given item, once owned they would not be prepared to sell the item at such a price. This phenomenon was developed and discussed by Kahnemen et al (1991).

A number of explanations have been put forward as to why this phenomenon occurs, one of which is an aversion to loss which can clearly be seen when transacting for domain names. Given an inability to accurately discern who one is negotiating with a seller will often times be averse to selling a domain name because they do not potentially want to ‘leave money on the table’. Likewise, from personal experience it is plausible that psychological attachment to the domain would suffice to make a seller demand significantly more than it may justifiably be worth. A domain which you have spent numerous months perhaps even years) trying to acquire may result in an attachment requiring significant (perhaps unreasonable) financial compensation for you to consider selling.

List (2003) conducted experiments into the endowment effect and concluded that market experience results in a reduction in the effect (which he terms a market anomaly). This seems logically consistent with the concept of ‘domain name investors’ whose business is to extract profit from their ‘stock’. Hoarding, or holding onto domain names whilst demanding exorbitant prices is clearly not a good way of running a profitable business.

Oster, Morton (2006) note that *“one could imagine markets that are very large, such as those for freezers, cars, houses, and sofas, in which consumers do not typically engage in dozens of transactions in a single year”*, implying that experience is not easily gained. This author sees the other side of the equation in that the domain name market is sufficiently small and niche that apart from the ‘domain name investors’ discussed above, experience is not easily gained. The domain name owner who bought a great domain name for a personal website back in 1992 (and only owns that domain) will unlikely have any experience that would reduce the endowment effect bias.

These papers and discussions do not also consider the situation whereby a domain name owner has a vast ‘stock’ of domain names. Entities such as Telepathy, Name Administration, Another Ltd etc own hundreds of thousands of top quality domain names. There is a bias (although perhaps it should not be considered under the umbrella of the endowment effect) whereby the volume and quality of owned ‘stock’ disincentives sales. That is to say, if you own great domain names in such volumes you likely have quite a lot of money. You do not need the money and as such you can afford to wait (as discussed in the comparison of the domain name market with the housing market). You will be loss (the loss of the domain) averse as a result of vast wealth -  a fantastic negotiation position.. and a fantastic position to be in more generally.

The endowment effect is another phenomenon which relates to both the domain name market and the housing market (Bao, Gong (2015)) (as discussed above).

## Valuing a domain name

Given the context of the explanation of the concepts above one can more generally tackle the subject of domain name valuation.

Domain names are inherently difficult to value because they are incommensurable. That is to say that they are *“Impossible to measure or compare”*.

Whilst historically a number of different economic theories have been developed (some rising to prominence more than others) none have been developed that can be appropriately applied so as to simplify the task of domain name valuation.

One may argue that a combination of the ‘best bits’ of a number of theories could be utilised so as to develop an appropriate theory that can be applied to domain names. Unfortunately however the presence of flaws, as well as unrealistic (and incompatible) simplifying assumptions means that in practice this is not possible.

Domain name valuations are premised on personal interpretations of a number of evaluation criteria which are not mutually exclusive. A company CEO may give weighting to completely different factors when compared with the valuation of a domain name investor. It is for these reasons that domain name valuation is so difficult.

### Singularities

In his book *The Economics of Singularities*, Lucien Karpik describes the foundations of neoclassical economic theory as being:

>*“a rational actor endowed with stable, ordered preferences and exclusively oriented towards profit or utility maximisation; the regulation of supply and demand by price variations; and market equilibrium states that are determined by the conditions of competition”*.

The topic of his book (from which significant influence has been taken in developing a valuation methodology for domain names) is *singularities*, a term that this author would describe as referring to products that are incomparable unique.

Karpik outlines how such ‘singularities’ (art, and fine wine for example) can not fit into the framework of neoclassical theory. I believe that domain names are similarly ‘singularities’ and cannot be described by neoclassical theory. That is to say that in this authors opinion that domain names are incommensurable - they are (as Karpik puts it) *“uncommon, incomparable, unique, singular”*.

The most common appraisal methodologies for domain names are *expert* opinion, and automated statistical analysis. Both to some extent rely on consideration of characteristics of domain names that can be quantified (for example their length and TLD). These characteristics are not however necessarily easily discernible. For example the amount of type-in traffic a domain name receives daily is impossible to know unless you own the domain name (and declare said information), and have actively monitored the traffic that it is receiving. Not only that, but these characteristics (and the valuations assigned to a domain name based on them) are uncertain and open to individual interpretation. In this regard domain names are a multidimensional product prone to the risks associated with uncertainty as regards *quality*. They exist in a relatively opaque market whereby information is not necessarily readily available and as such as described by Karpik:

>“When products are singularities, when the actors give more weight to qualities than to price ... choice takes the form of judgment”.

The nature of domain names as a product differs from that of traditional physical goods that one would purchase in a store. Whilst one could ask a store assistant for advice, or visit a showroom to browse available offerings, this is not possible with domain names. You can visit a registrar and take stock of any promotions that may be available on a specific domain extension but this pertains solely to the situation whereby one wants to register a new domain name. Given the ‘one of a kind’ nature of domain names, and the length of time the domain name system has been around it is highly likely that most domain names that could generally be considered *good* (even considering human subjective evaluations) have already been registered.

### Judgement devices

Showrooms, marketing, and personal networks are examples of what Karpik defines as *judgement devices* to aid in valuing singularities. He notes that the *“merchant is a principal judgement device and the outcome of his intervention varies with the clients’ competencies and reactions”*. In that regard the lack of such judgement devices within the domain name market could be considered a good thing - there is no opportunity for opportunism on the part of the merchant (domain seller).

Karpik divides ‘judgement devices into five categorisations outlined below:

<table>
<tr>
<th>Categorisation</th>
<th>Explanation</th>
<th>Relevance to domain names</th>
</tr>

<tr>
<td>Networks</td>
<td>the people you know</td>
<td>experts’, friends, and colleagues</td>
</tr>

<tr>
<td>Appellations</td>
<td>brands and product identity</td>
<td>brands and product identity</td>
</tr>

<tr>
<td>Cicerones</td>
<td>critics, guidebooks etc</td>
<td>bloggers, and news sources</td>
</tr>

<tr>
<td>Ranking</td>
<td>rankings </td>
<td>previous sales charts</td>
</tr>

<tr>
<td>Confluences</td>
<td>marketing, sales, and means of advertising </td>
<td>the sales pitch</td>
</tr>
</table>


In relation to domain names ‘judgement device’ categorisations take certain forms. These devices include *expert* opinions, previous sales lists, and the availability of specific pertinent information (such as traffic data).

*“Judgment devices ... dissipate the opacity of the market”* and in and of themselves emphasise the incommensurability of domain names because of the different values given to judgement devices by different people.

There are a number of reasons for buying things. For example some individuals choose food products based on ethical considerations. When it comes to fashion, decisions are often made based on aesthetics. In some situations a purchase may be made purely due to arrogance. As outlined by Karpik, *“The consumer is one of many and one who should not be confused with anyone else”*.

Lancaster (1966) outlines that the price of a product is equivalent to the sum of the prices of its characteristics. This is useful and reasonable in the situation where all the characteristics are known and separable. Unfortunately however not all characteristics are divisible - a value can often not be attributed to a characteristic taken on its own. The value of type in traffic to a domain name may add value dependent on the source of that traffic. Likewise the domain name ‘Z.com’ has significant value because it is one letter and not because a search for the term ‘Z’ on Google yields nearly eight billion results. At least for me.. 

One must also consider that a valuation, and the weighting given to a particular characteristic is an extremely personal consideration. That is to say the additional value attributable to domain length is dependent on the views of the interested party.

### Search costs

Considerations of such nature may however be jumping the gun. To even be able to compare alternative domain names one must be able to discern who owns the domain name such that they can contact them and enquire about further information that may influence their decision. The nature of the WHOIS system means that there are additional search costs involved in even discovering what your options are. The WHOIS information might be outdated or incorrect, or the owner my simply not pick up the phone or reply to emails. They may pick up the phone only to inform you that the domain is not for sale..
In the case of the .co.uk/.uk namespaces (operated by Nominet), their WHOIS database does not even provide contact information. As a result, to obtain a domain owners email address or phone number people have taken to posting on public forums topics with subject lines such as ‘Does anyone one know how I can contact Joe Bloggs?’. It is clear to see (without any form of statistical analysis) that the aftermarket for domain names in the .co.uk/.uk namespaces is barely existent. Sales are few and far between, and the prices involved are insignificant compared to those in the .com namespace. This author would put this down (in a significant part) to the ‘cost’ of search associated with contacting a domain owner.

### Uncertainty

Many of the concepts discussed above can be equated (or related) to *uncertainty*.
 
Karpik specifies two types of uncertainty: Strategic uncertainty and Quality uncertainty.

Strategic uncertainty is uncertainty that *“arises from the intersection of two processes of interpretation”*. In the context of domain name valuation this refers to the idea that a domain valuation is not definable because different people use different processes and considerations to reach their own individual valuation. The buyer may for example place a higher value on the “radio test” than the seller, yet sentimentality (by proxy of the endowment effect) will certainly have a bigger effect on the sellers price valuation than the buyers.

Quality uncertainty on the other hand is uncertainty that arises because knowledge is imperfect. When purchasing a domain name it is nigh on impossible to discern all of the information that could influence your purchase. When buying a domain name you very much rely on information that is publicly available to you, and information that is provided to you. Sadly (it is the way the world works) often times a seller will not provide you with information that is going to negatively influence your valuation.  Williamson (1981) outlined how opportunism and self interest is a significant consideration in uncertain markets, and alludes to how there must be additional checks in place (regulation for example) to allow markets to function efficiently. 

Then there is Akerlof's (1970) infamous ‘lemon problem’ which relates to how self interest can lead to complete market failure. It states that a market will move towards a point whereby all of the products available are of a below average quality. Given that a buyer cannot accurately discern quality the owners of above average quality products are disincentivised from selling their wares whilst the owners of lower quality products (lemons) are.

One could thus say that the direct communication market for domain names is an example of market failure because the economically ‘correct’ price valuations are more often than not not realised.

Even in the circumstances whereby information asymmetries are minimised (for example using open auction platforms) there are still issues with quality uncertainty. Even after a transaction has closed there is an “evaluation lag” that in *“reality can remain ambiguous to the very end, even for experts”*. In the context of domain names you might value a domain highly based on the assumed ‘brand’ value it might afford you. This in itself is extremely difficult to quantify - you may simply not be able to discern how much purchasing a domain name really helped your business.

Given the problematic nature of transacting for domain names it is reasonable to consider retrospective disappointment as an indicator of how ‘good a deal’ a particular purchase was. Disappointment *“does not rely on personal measurement or comparison but involves an experience”*. If after the fact the buyer attains further information that disappoints him it may be the case that he/she has overpaid.

Disappointment is somewhat analogous with regret. Another way of looking at an individuals decisions in relation to a particular negotiation is by considering the extent of their potential regret prior to putting their offer on the table. Regret theory (Loomes, Sugden (1983)) is interesting in that the potential for regret is situation dependent. That is to say that (applied to domain names) if you choose not to improve your offer, your regret will potentially differ in the situation whereby upon sale to the ‘outside option’ the sales price is disclosed. If you can see (or know that you will be able to see) exactly how much perceived surplus you have left on the table your regret may well be more. 
This can also be considered from the other side. Should you accept a particular offer and at a later date see that the domain in question has been resold for significantly more you would likely be filled with regret. Anticipation of this potential regret could affect the way in which you act as a seller. 

The risk inherent in domain name transactions is “radical uncertainty” as outlined by Knight (1921). He distinguishes between “risk” and “radical uncertainty”. Whereas with risk you can calculate the most rational decision, with  radical uncertainty you can not - risk can be quantified, radical uncertainty can not.

### Experts

Within the domain name industry there is no one individual or group that is influential enough to universally discern valuations for domain names.

Whilst there are a number of self titled domain name experts, in reality they do not command the universal authority required to be influential. There is for example no individual who has the ‘power’ to influence the uptake of a particular new gTLD. This is because the experts in question represent an extremely small cottage industry of sorts. Whilst an ‘expert’ opinion might influence a newcomer to domain name investment it is highly unlikely that such an opinion would even be visible to a more general audience.

There are a number of industry blogs which cover topics pertaining to domain name valuation but these are written from the viewpoint of members of an industry whose main prerogative is to attain large returns from their investments. Their valuations are subject to specific interpretations of the value added by specific criterion that are not universally reasonable. As a result of this, utilising the contents of a blog as a judgement device for valuing a domain name is a prime example of a device to which different weightings would be given dependent on the individual in question.

Furthermore, if an outsider were considering a domain name purchase there is no guide that one can refer to, nor is there a universally available ‘top 10’ list of domain names available to you within your price range. There is a resource entitled DNJournal (http://dnjournal.com) which documents weekly sales reports, however on the basis of the reasonings outlined above it is not necessarily reasonable to equate a valuation for your domain name to the sales price of one which you deem to be similar.

Estibot.com is a product which tries to quantify characteristics of domain name valuation and utilising a complex algorithm produce an appropriate valuation. The premise is that Cognitive artefacts (Norman (1991)) of this nature help to increase the *“actors’ cognitive capacity”*  for making a decision. Given the explanation above it is patently apparent that such an approach is not appropriate because of the inherently personal nature of domain name valuation. Karpik notes that *“specific linguistic and interpretive practices were enough to over qualify or dequalify goods and services”*. That is to say that by ‘simplifying’ a singularity in such a manner you take away a lot of what makes it valuable. In reality, whilst a valiant effort Estibot falls short of providing any real utility to a potential buyer. Is the eye of a human (namely the actual interested party) the only good judge of domain name value?

Karpik invests a lot of time in a discussion of the differences between judgement and calculation (and the ways in which they are interconnected). He notes that judgment is a *‘modality of choice’* where calculation is an *‘instrument of action’*. In addition to that difference it is certainly the case that judgement hinges on trust in that ones interpretation of a particular device is based on the assumption that the information is accurate and honest. As such utilising historical sales data for example presents an issue in that it is not verifiably accurate - there are a number of reasons why one might want to inflate the perceived sales price of a domain name. Likewise this author is of the viewpoint that a significant number of domain name sales are simply not reported (again for perfectly valid reasons) and thus this particular device needs to be considered with a pinch of salt.
It is also fair to allude to the imbalanced nature of judgement devices. Amazon and TripAdvisor (and their review systems) are a prime example of such a situation whereby there are significant imbalances. Human psychology often dictates that one will only submit positive reviews for products that they like. Poor products and experience are forgotten as quickly as is possible.

In relation to domain names the large sales are the ones that get the publicity and are the ones that are utilised by sellers and brokers as presentable judgement devices for future sales. Presentation of such information is selective and somewhat manipulative - it gives the impression that what could potentially be an outlier is in fact the norm, and ignores the potentially numerous sales of similar domain names at significantly lower values.

Wendy Nelson Espeland summarises the market for singularities well, stating that *“mainstream economists cannot offer a satisfying answer to this question because their usual subjects—scarcity, demand, differentiation, utility—do not capture how such markets work.”*

### Get a broker

Rather than playing a game of chicken which can lead to a breakdown in negotiations, why not get a broker? Sundem (2012) outlines the negotiation considerations of a situation whereby a buyer and a sellers views of ‘fairness’ do not overlap. He notes that *“Self-serving bias makes us both likely to agree to arbitration.”*

It is for this reason that ‘negotiators’ are used in ‘pirate negotiations’. Both parties want to get the situation resolved as quickly as possible (Ambrus et al (2014)) because of the costs involved in ongoing negotiations.

Not only can a broker aid in getting your domain name in front of potential buyers but he/she can also aid in reducing the significance of information asymmetries within a normal negotiation process.

A good domain name broker should convert a product into a *qualified product* by attaining and collating the necessary information (judgement devices) on behalf of the seller (and for the viewing of the potential buyer) so as to allow an informed decision. This is especially important in the situation whereby a potential buyer is somewhat ignorant of the complexities associated with domain names (and their valuation) - the idea that business.com is worth $7 million may be extremely difficult for a member of the public to comprehend without the reasoning behind such a valuation being presented.

It is fair to say that if someone offered you a metallic box for $1,000 without any context or clarification as to what it was (or what it did) you may be somewhat apprehensive about a purchase. If however they qualified the product by explaining that it printed legal tender your interest might be peaked, and a purchase considered (although in reality you should probably contact law enforcement). 

Sentiments are common on the Internet of the domain name owner who has received a ‘ridiculous offer’ from an ‘idiot’. It bemuses this author (who himself has a vested interest in the value of domain names) that sellers can themselves be so ignorant to the fact that different people are using different judgement devices (and different interpretations of them) when reaching a valuation.

On the other side of the equation this author has historically contacted a large domain name brokerage to enquire about purchasing a high value domain name. When questioned as to why a particular domain name was valuable the broker in question paused (whilst one assumes he logged onto estibot.com) and then began reciting quantitative statistics pertaining to the domain name. One must be careful when hiring a broker that they are not simply a middleman relaying inappropriate or unsuitable judgement devices.

Hiring a broker is in and of itself a judgement device. The logic is that that the cost associated with hiring a broker is less than the additional value the broker can attain by increasing the availability of/presenting judgement devices to a perspective buyer. One outstanding issue again pertains to trust. This author has significant experience working with domain name brokers to be able to note that many operate purely as businesses (to some extent understandably so..). That is to say a broker will only take on a sale when they believe it to be an easy sell. When they believe that the information needed to sell the domain name will be easy to attain (low search costs) and/or the network of potential buyers already exists. 
‘Brokerage’ is not a universally available judgement device but rather a device available to the fortunate few. In the same way that ‘showrooms’ are not devices available to perspective buyers of domain names, brokers are not devices universally available either.
Perhaps one should develop a judgement device for judgement devices in the form of a ranking table for domain name brokers.

### Speculation and ignorance

One extremely interesting aspect of the market for domain names is the fact that a significant number of transactions occurring do not occur with a potential buyer who values a domain name more highly than the seller. Rather, they occur between ‘resellers’ one of whom *thinks* that there exists *another* buyer who values the domain name more highly than the current seller.

Caves (2002) considered “creative goods” (under which domain names could be classified) as experience goods. Experience goods are goods for which an accurate value cannot be ascertained prior to purchase. True value can only be garnered from experience. In this case from 'seeing' the type in traffic that the domain receives, the revenue it generates, and the amount of interest it receives from other perspective buyers (down the line).

Caves suggests that asymmetry of information is not a consideration but rather *“symmetry of ignorance”*. This author believes this to be the case with the reseller market for domain names. 

Whilst a vast majority of ‘domain name investors’ are candid and pragmatic in their investment decisions, it seems to be the case that a large number simply get drawn into unqualified speculation. For example at the end of 2015/the start of 2016 there has been unprecedented demand for LLLL.com (four letter .com domain names) containing certain desirable letters by Chinese buyers. The desirable letters are those considered to be important within Chinese culture - a prime example of a situation whereby personal interpretation and judgement allows for different valuations to be placed on different attributes of a domain name. The result has been an explosion in transactions for such names amongst Westerners for no other reason than the fact that the Chinese like such domain names.
There will of course be a real problem if Chinese buyers stop liking these kind of names. 

Note: Over the course of the period in which this paper has been written it does in fact seem that this has been the case. The market for such domain names is now significantly less liquid, and the prices being attained have gone down significantly. It is possible that this market could by cyclical and we could see further development over time.

### Comparing domain names

Neoclassical theory states that to realistically compare two domain names it is required that they be ‘dequalified’. One must generalise characteristics of a given domain name. 

The requirement for such dequalification means that *“ignorance and ambiguity are inherent to the commerce of incommensurable products”*. Writing this, it seems plausible that the domain name resellers mentioned previously may in fact simply be neoclassical economists. That said, one can see that this is not an appropriate platform for fair comparison.

Domain names can not be valued simply based on price competition because they are **all** different. They cannot be valued based simply on ‘qualities’ or ‘characteristics’ because of that outlined above.

Given that knowledge requirements are so extensive and varied, and considering the fact that there is such a diverse range of preferences (in relation to what characteristics affect a domain names valuation) one must look elsewhere for guidance. 

Karpik introduces the concepts of personal and impersonal judgement devices and elucidates that they have to be credible. The usefulness of a judgement device depends on the trust placed in it.

Whereas neoclassical economics takes for granted the availability of information, the economics of singularities does not allow this to be considered a reasonable assumption. 
Utilising ‘judgement’ (by proxy of devices) does not rely on calculation but yet can still be considered just as rational. Judgement relies on knowledge which depends on context and interpretation. Whilst judgements cannot be universal they *“can be more or less general, according to whether the judgement is more or less shared”*.  Furthermore, for *“a judgement to be valid, it must marshal sufficient knowledge of reality”*.

Judgement devices are a medium to which we delegate decisions. They *“reduce the cognitive deficit”* and *“they authorise the comparisons without which consumers would be limited to random choices”*.

At this point in proceedings I would like to focus on the ‘networks’ judgement device categorisation as they have particular significance within the domain name industry. 

The networks Karpik refers to are outlined below.

* **Personal networks** - *“family members, friends, work colleagues, and contacts”*

* **Trade networks** - “sellers or their delegates and of buyers”*

* **Practitioner networks** - “professionals"*

The Internet and the development of the domain name market has created a relatively unique form of personal network. This network takes the form of a network of entities with whom you converse, discuss, and conduct business, yet have never met. The reality is that your hybrid personal network could be made up of people pretending to be other people or otherwise hiding their identities. Once again we come back to the notion of trust. Every aspect of the domain name market seems to be supported by an assumed trust amongst actors.

One must also be careful when considering trade networks and practitioner networks. One must be somewhat cynical in their approach and as with many industries and forms of business be wary of the incentives of others. 

A broker for example is inclined to say what you want to hear if it means that they retain your business in the longer term. They might state an inflated price expectation in the knowledge that at a lower level they would not grab your attention.

A colleague or member of a professional community might deflate their valuation of a given domain name if they themselves are interested in purchasing it. In principle they could appraise the domain name at a lower than realistic valuation, then create an anonymous email account and engage you in  negotiation.

In reality an exercise in comparison of domain names is an exercise in comparison of the levels of trust involved in the various aspects of the relevant transactions.

## Game Theory

Game theory is a subject matter that has been developed and applied to many subject areas including (but not limited to) Biology and Economics. Its application within Economics is relevant in the discussion of domain names.

One main underlying assumption of theoretical game theory is the suggestion that all actors behave rationally. Once again however, in reality, this is not the case. There are a number of empirical studies into various game theoretical concepts (for example the centipede game, and the ultimatum game) which indicate that in practice actors do not act rationally.

Rationality in relation to game theory is a self perpetuating problem because rational action is only appropriate in the case where all other players are also acting rationally. Common Knowledge of Rationality (Aumann (1995)) is often however not the case. From this authors experiences within the domain name industry, anonymity and behavioural phenomenon such as the endowment effect mean that rational behaviour is often not enacted.

Both homo economicus and homo singularis (as described by Karpik), the rationally self-interested individual, are constrained by this reality that is often overlooked by economists.
More recently the subject of Behavioural Game Theory has developed. This subject area takes game theoretical concepts, tests them through experimentation, and discusses/develops theories based around what actually happens in reality.

Game theory is the theoretical premise behind a number of previously discussed concepts that pertain to domain names. It underpins auction theory, as well as the decision making processes involved in negotiations.

A Nash equilibrium point (Nash (1950)) is a point at which two actors (in for example a negotiation) who make their decisions independently cannot change their respective strategies to produce a better outcome. In the case of a negotiation such a situation would arise where the seller can not extract any more money from the perspective buyer, and the buyer can not get the seller to reduce their price any further. Whilst it may not be ideal, a Nash equilibrium point in not analogous to an optimal outcome. That is to say that given the context and nature of the game (giving consideration to the economic phenomena outlined in this paper) the position may not maximise utility for both parties.

Negotiations are sequential, zero-sum games, meaning that if the prospective buyer is paying less than they are willing to pay, they are getting a ‘good’ deal whilst the seller is getting a counterbalancing ‘bad’ one.

Game theory has considerations in relation to the law (discussed below in relation to domain names), namely that in cooperative games with legal considerations one is bound by their promises. That is to say that one must do what they say they will do or face legal repercussions.
As a result of this, the way one approaches a game (and as a result, its outcome) is affected by the legal environment surrounding it.

Randal J Picker (1994) gives a succinct and clear explanation of these topics in his paper entitled *“An Introduction to Game Theory and the Law”*.

## Trust

Trust is a concept which spreads itself across many disciplines. The nature of, and the extent of trust varies from person to person but as outlined by Evans, Krueger (2009), it comes down to an acceptance of *“risk because they believe they can avoid a negative outcome.”*

Trust is context dependent in that contrary to the neoclassical suggestion that trust does not play a part in economic decision making, various experiments (including those outlined by Krueger) show that in fact it does. Discussion of ‘ingroup’ and ‘outgroup’ cooperation shows that the level of trust can be affected (or trust can be non-existent) premised on what external observers may subjectively describe as arbitrary considerations. For example shared social identity - trusting someone because they also like cats.

In addition to this, experimentation has shown that biological considerations do have effects on trust. For example Kosfield et al (2005) show that Oxytocin increases trust within humans, whilst Bosch-Domènech (2009) expressed an interest in conducting similar experimentation on the effects of alcohol on trust. From personal experience this author can qualitatively state that alcohol does have an effect on trust.

Finally one should consider the extensive research that has gone into the subject of ‘trust across borders’ as reviewed by Hajidimitriou, Sklavounos (2008). The takeaway is that one contextual consideration which results in different trust considerations is location and culture. This is a significant consideration in relation to the Internet which in its very nature facilitates transactions across borders.

As a result of the nature and size of the domain name market there are no large brands whom one might inherently trust. One must remember that the domain name industry is extremely small and niche. 

Coca-cola is well known for the extent and level of its brand awareness. Almost everyone in the US knows what Coca-Cola is, and what they do.
In the domain name industry however the only real market segment which has the potential to be of interest to a more general public is the registrar segment. Within the registrar space there are well known intra-industry names (for example GoDaddy and Uniregistry) yet their reach does not stretch much further.

GoDaddy have recently launched television adverts within the UK yet this author is still of the view that if one were to ask a random sample of people who GoDaddy were and what they did, very few would know.

Even amongst industry participants, trust is not to be assumed. The aftermarket (bargaining amongst buyers and sellers) does not have the fortune of any inherent trust mechanisms. The aftermarket auction platforms are in and of themselves subject to very complex and unpleasant histories. For example the Halvarez ‘scandal’ at Snapnames back in 2009/10, and the number of publicly posted ‘complaints’ about platforms such as SEDO. 

The market for domain names is again somewhat unique in that judgement devices (positive or negative) can easily be shared online. Whilst nowadays you can post an opinion about anything online (companies have large departments dedicated to online reputation management) the domain name industry has an additional intricacy - the tech savvy nature of its participants.
 
Given that the business is an online business, and that most users of the Internet have knowledge of the workings of Google, a damaged reputation can cause long lasting effects.

Were one to create an artificial textbook economic market for domain names one might argue that only ‘experts’ should be allowed to take part. Apart from artificially constraining the supply of potential buyers/sellers, such a situation would not resolve the trust issues associated with information asymmetry.

Karpik notes that *“In the face of uncertainty trust creates predictability and therefore the possibility of continuing exchange”*. The problem however is that trust can be destroyed significantly more quickly than it can be created. 

Take for example the case of Adam Dicker, a (previously) prominent Canadian domain name investor. He had built a reputation based trust with hundreds of individuals he did not personally know through the proxy of his ownership of the DNForum.com domain name discussion forum. Unfortunately however it came to light that he had been less than honest regarding ongoing business relationships with these members of his network. Discovery of these issues led to a mob-esque discussion of the issues on the NamePros discussion forum, the result of which has been a forever tarnished reputation within a rather small community of businessmen/women.

One could argue the sentiment that if it sounds too good to be true, it probably is. As noted by Granovetter, *“we expect good behaviour of others in spite of their incentives”*.

The case of Adam Dicker is essentially a micro example of happenings to which the majority of the population are more aware. For example the Financial crisis of 2008. Michael Lewis’ *“The Big Short”* (now a blockbuster movie) is a mid level explanation of some of the integral causes of the crash. It is interesting to note a general viewpoint that “bankers are evil” is premised upon (in many cases) the low level sentiment that bankers should not be trusted as opposed to a high level understanding of why they shouldn’t be trusted. Furthermore the financial crisis has resulted in a catch all cynicism towards the banking industry. This author has observed audible groans when an individual states that they work in banking, independent of the fact that they are a cashier in a small rural British village..

There is a game theoretical game entitled the ‘Trust game’ 37 in which:

* a player chooses how much of a given pot to pass to the second player

* a third party to the game triples the amount passed

* the second player is offered the opportunity to return a proportion of this increased amount to player 1

Experimental implementations of the game [38] by Brulhart and Usunier (2010) have shown that trusting player 2 with an allocation of funds is a worthwhile thing to do as they will almost certainly reciprocate by returning more than you sent. This author however would be intrigued as to whether this effect would be seen in an anonymous domain name transaction where there is the potential for no information to be available about a party to a transaction. The separation provided by anonymity over the Internet it is felt would result in more selfish actions by the second player.

Similar experimentation by Fetchenhauer and Dunning (2010) clearly emphasises the cynicism of individuals investing in trust transactions. Their results suggest that the only way to reduce the cynicism associated with trust is to provide accurate information about the trustworthiness of the counterparty. Given that such information is not freely available or accessible, is one to presume that text book optimal economic transacting simply cannot occur?

To take the relationship between trust and inherent anonymity one step further one can consider the trust capital concept. This concept essentially states that one has to earn trust and can then ‘spend’ said trust working with entities who would otherwise not. The issue with domain name negotiations is that because of the transaction medium one does not have the metaphorical ‘pot of trust’ because such a pot has to be associated with ones identity, and the Internet allows for a lack of identity.

*“The potential for difficulties in establishing the authenticity of the identity of a consumer or
online business is one of the characteristics that distinguishes trust issues in electronic
environments from most other contexts.”* Guerra et al (2003)

The work by Bohnet et al (2008) on *“betrayal aversion”* is particularly pertinent to such anonymous transactions especially given the prominence of *issues* such as reverse cybersquatting (as discussed above). You will be averse to transacting when you are unsure who you are dealing with, but you may be more averse to transacting when there is the possibility of being entrapped in a manner that has been regularly documented and publicised by industry constituents.

## Policy and practice

Throughout this paper I have alluded to concepts such as cybersquatting, and policies such as the UDRP. It has been implied that there is a requirement for some sort of legal regulation of the domain name industry. This section will collate view points on the subject and discuss the reasons why legal considerations are important.

### The requirement for law

Mueller (1998), noted that the economic value of a domain name is *“...not primarily a function of the operational costs of registering users and running servers”*. He stated that domain names are not scarce in terms of the quantity available. Thus it can be argued that for the most part domain names are **not** in demand as there is an almost infinite number of combinations available. However, those that match an organisation’s name, trademark, or product are scarce, and therefore in demand. 
As such it is important to note that the following analysis pertains to the allocation of *high demand* domains. It is noted that ‘typo domains’ and domain names coming under the 'reputational politics' categorisation (discussed below) are also 'high demand' as entities want them to protect their brands.

Kamath (2001) highlights the need to protect rights holders as an *“economic incentive to creativity”* and supports the general consensus that incentives stimulate entrepreneurship. This suggests that through private property rights (patents, trademarks, or copyright), individuals are prepared to take risk, and be creative knowing that they will be able to reap the rewards of their successes. He also states that consumer protection is required to prevent *“deception in advertising”* and to maintain the *“integrity of the market system”*.

One significant factor leading to the development of cybersquatting is the growth of WHOIS privacy. The WHOIS database is the publicly available database through which individuals can identify who owns a domain name. Many registrars now allow the purchase of a 'privacy' product which places blanket details into the database such that the real owner is not identifiable. When a 'private' domain is queried in the database a generic company name and address is displayed rather than the real owners details. Cybersquatting has therefore increased under the naive assumption that anonymity will protect a registrant from legal recourse. It is then significantly more complicated for a company to pursue an amicable discussion with an offending registrant and so may prompt their unnecessary use of legal options. Counterintuitively the law may well be needed so as to stop (or minimise) the need to utilise the law as recourse when trying to discern a domain name owner.

If a domain name similar to a brand name is registered, the individual or entity who has registered the domain may benefit from the inherent brand value of the mark holder (as outlined by Kamath). However, the problem in terms of distribution is that the owner may, in principle, have just as much right to the domain name themselves. 
For example Uzi Nissan was the owner of Nissan.com - to the dismay of the Nissan car company. They unfairly utilised their financial position to attempt to take the domain from its owner without just reason. An act known as 'reverse cybersquatting.'

Ramello (2005) has explored reputational considerations, specifically looking at market efficiency, and how trademarks prevent market failure by aiding the establishment of reputation. Goldman (2005) however states that *“Without limits, trademark law has the ability to counter productively destroy the Internet’s utility for everybody”*. This statement was made in reference to internet search engines, but is directly relevant to domain names. He later points out that the domain name system was developed from ‘search’, and notes that consumers assume that a ‘trademark’ appended with .com will get them to the trademark holder’s website. He is quick to note that the “relevancy algorithm” of domain names is in fact a weak one. Due to the ‘first come, first served’ nature of the domain name system it is **not** necesarily the case that appending .com to a trademarked term will get the consumer to where they expect. This often leads to what Oram (1997) refers to as the *“costs of confusion”*. He cites a specific example of the additional economic costs to consumers associated with an inability to find a website where one expects to – the “search costs” outlined by Stigler (1961) in his paper *‘The Economics of Information’*.

These issues are not independent of one another. It is highly plausible that a number of individuals **do** visit Nissan.com expecting to find the Nissan car company. That does not however mean that the current owner has any less right to the domain name. Furthermore there are multiple companies with the same (or similar) names across multiple industries. This is the reason as to why trademark applications require one to specify the industry to which the trademark pertains. As a result it is fair to suggest that there will be search costs for someone regardless of who owns the domain name.

A company that does not own its 'CompanyName.com' experiences a cost associated with utilising an alternative domain name and the need to advertise it. In addition to this economic cost, there is an externality imposed on consumers who associate a given name with a given brand. They will have additional search costs imposed when searching for a company’s web presence. These additional search costs are a consideration when businesses are evaluating the potential benefit of transacting to purchase a domain name (in order to reach a Pareto optimal position) (Bakos, Nault, 1997). A Pareto optimal position being one whereby *"it is impossible to make any one individual better off without making at least one individual worse off"* (Wikipedia).

Litman (2000) however outlines the development of trademark holders’ rights with regards to domain names, concluding that the economic cost associated with consumer confusion on the internet is negligible, especially when compared to the transaction costs associated with the legal system. She also notes a possible remedy to the anticompetitive ‘trademark exclusivity’ mentioned above in relation to domains, suggesting that although trademark holders should have rights to ‘trademark-dot-something’ other non-trademark holders should be able to own ‘trademark-dot-something-else’ if they have legitimate reasons or rights. Examples of such legitimate rights holders include the ‘twins’ who have “legitimate claims to using the same name in the brick-and-mortar world” as outlined by Nathenson (1997). For example Merck, the American and German pharmaceutical companies. He suggests that legal remedies for dispute resolution are important because of three broadly similar classifications of domain name holders, namely cybersquatters, parasites (those who do not intend to sell but rather profit off the confused), and poachers (synonymous with reverse cybersquatting; as described above).

Kratzke (1991) clarifies the economic efficiency benefits attainable with trademarks, and looks at how they can be beneficial as regards allocation efficiency and aiding consumers to navigate inter-brand competition. He does however note that over-protection may stifle this benefit for consumers – suggesting that exclusive rights to trademarks and overprotection are detrimental.

The above discussion suggests that there is a role for the use of law to protect rights holders within the current system; in particular with regard to brand protection. However it does highlight other considerations and anomalies for which other systems of allocation and regulation may be preferable and through which an efficient market system has the potential to reduce cost and negate the need for legal recourse.

### Does it work?

Assessing the development and success of attempts to resolve the inefficient allocation of domain names, namely through the introduction of the UDRP and ACPA, requires consideration of the extent to which these policies have affected and influenced allocation, noting that the economics of law play a significant role in this discussion.

Respected authors have a number of opinions on as to whether the UDRP and ACPA have worked. These opinions vary both in their position and extent. A number of these opinions are outlined below.

White (2001) further breaks down the cybersquatter category (defined by Nathenson earlier) into “cyber-piracy” and “typo-squatting”. So too, Moore and Edelman (2010) have calculated insightful statistics on the occurrence of “typosquatting” on the web, and “passive warehousing” stating that the initial version of the UDRP is suitable in its “speed, simplicity, and cost” but needs further development to serve best interests with regards to “passive warehousing”. Hancock (2001) likewise notes that the UDRP has allowed domains to be returned to rightful property rights holders, but still has its shortcomings. 
Parchomovsky (2001) outlines how he believes that the UDRP and ACPA processes do **not** guarantee the efficient allocation of domain names under **any** circumstances and proposes the utilisation of auction mechanisms to allocate domains. He suggests that the ‘good faith’ nature of the processes, (which states that if a domain registrant has registered it in good faith, for a legitimate use (an inherently subjective point)) is not suitable for efficient resource allocation.

This author is of the view that given the previous discussion on the nature of personal opinion and interpretation (in relation to judgement devices) one could not feasibly attempt to justify any individual or group defining and executing a definition of what is and is not 'good faith'. On that basis it is felt that the UDRP and ACPA can **only** be of use in clear cut cases (of which there are very few). Given this, this author is of the view that they do **not** achieve the objectives which they set out to. This is a view echoed by Cortés (2008) who discusses the success of the UDRP since its inception a decade prior, stating that it has worked in some respects, yet it is still in need of reform such that the correct rights holders are getting the correct domain names, and the process is not being abused.

One of the cases that one could potentially argue has been an 'abuse of process' is that of Nissan Motor Co. v Nissan Computer Corp (mentioned previously). Whilst in some cases, the UDRP process is not required (Sharrock (2001) notes that multiple trademark cases have been “settled peaceably”) this case was not one of them. The case has already run for over a decade without the expected Coasean bargaining outcome. The UDRP has been used (arguably) incorrectly to attempt to 'take' the domain, and still as of today there are entities who feel that the domain is not controller by the appropriate party. Whilst this shows that the UDRP process is open to abuse (which is surely a failure), the case is more generally indicative of the allocation issues outlined throughout this paper. The details of the case are discussed further in Piontkowski (2004), outlining it as a case of trademark dilution. 

Based on the above, it is clear that the mechanisms in place, although often successful, are not suitable and have not allowed the efficient resolution of all cases – further development, or alternatives are needed.

Resolution of the sub-optimal outcomes presently shown by the allocation of domains is possible through market transactions, however many potential and worthwhile transactions are not taking place. Current market structure poses many inhibitors to trade. Given that there are numerous auction websites, and brokers competing to sell domain names, it becomes very difficult for a party interested in a domain name to discern if, and where a domain name is for sale. It is this market confusion and inefficiency that requires change such that process like the UDRP and ACPA are simply not needed.

Were such fundamental changes to be implemented it would be an appropriate time to give significant consideration to the initial discussions pertaining to domain name valuation and as to how one could maximise trust and minimise information asymmetries (areas in which there would be significant overlap) in the process.

### Fixing the domain name system

Many alternatives to the domain name system have been proposed over the past twenty years yet the fact that the domain name system still exists largely unchanged indicates that none were a success. I have outlined a number of these below prior to outlining and detailing my proposed methodology for 'fixing' the domain name system.

**Singular homepage**

Deveci (2003) proposed a singular homepage such that any trademark holder with a particular mark could have an image, blurb, and link to a different domain on the ‘trademark.com’ domain. This fits in nicely given the fact that numerous companies exist across numerous industries with the same name (as discussed previously).
This has debatable advantages for the consumer, and given the value in domain names (that has been discussed) it is clear to see why large scale lobbying by domain name holders might act to stop any such idea from getting past the planning stages. For example it is difficult to imagine Coca Cola being prepared to *share* coke.com with a vegetable seller in Durham who also happens to be called 'Coke'.

**Smart Browsing**

Kamath (2001) pointed out a similar pre-emptive mechanism in the form of Netscape’s SmartBrowsing feature (way back in the late nineties) where rather than utilise domain names, a term or mark is entered into the address bar and the user is directed (based on trademarks) to a directory of potential sites. Again, the system we see today is indicative of why in this authors opinion SmartBrowsing never took off. It is very rare that you see a domain name holder who also owns a trademark matching their domain name (although you do often see this in reverse). Furthermore the utilisation of trademarks over multiple product categorisations would make this a somewhat laborious process for the end user. That is to say a user looking for a particular well known trademarked brand operating in a particular industry would likely have very little interest in seeing websites pertaining to other brands using the same mark within other industries. SmartBrowsing had the potential to increase search costs for the consumer, when any possible resolutions should seek to reduce such costs. The fact that it no longer exists is surely indicative of it **not** being a good resolution.

**New gTLDs**

Kamath was however a proponent of the introduction of additional TLDs such that multiple mark holders can have a suitable domain names. Through acceptance by rights holders, the ability to take advantage of the system will be reduced by an ‘across the board’ decrease in domain name values. This is in essence what we see today with the new gTLD program and the prominence of Google. One might however argue that no ‘across the board’ decrease in domain name values has or will occur. 

A significant number of domain industry professionals are of the view that the new gTLDs simply increase the dominance of .com as the ‘best’ TLD. Whilst a brand that is not prepared to purchase their .com from its current owner may well purchase a domain in a different extension. The suggestion is that the .com is still a better option. That said, should such a brand go with a non .com alternative one could argue that unless other significant potential end user buyers of the .com exist the .com could be of significantly reduced value.

Additional TLDs do allow multiple entities to hold suitable domains, however this proposal does not add anything to the debate as to whether the most valued entity owns the .com for example. If an entity owns trademark.net, and is happy (in that they don’t value the .com more), then they are not relevant to this problem.

**Advanced search engines**

Alongside his suggestion of new gTLDs, Kamath suggested that if the scarcity of domain names is no longer a factor, a system whereby users utilise “advanced search-engines” could gradually become the norm.

Google as an example of an 'advanced search engine' is an interesting topic of discussion. Recently Google have been integrating more different result types - widgets of sorts. For example you can see cinema times, flight details, and currency conversions all from directly within Google. The volume of data that Google has access to and the speed of technological development suggests that we could plausibly see a transition to 'one-stop' resources for our information requirements. If one considers *how* they utilise the Internet domain names could plausibly stay around in the periphery whilst we transition to these sort of products for the majority of our data consumption.

Whilst the initial suggestion was for new gTLDs to work alongside advanced search engines it would seem that search engines are trying to do as much as possible by themselves. That said, Google have invested heavily in the new gTLD program (having applied for 101 new extensions), and have also opened their own registrar offering.

**Social media**

Thomas (2011) suggested that the growth of social media is reducing the dependence on domain names as-is. As such a movement towards such a system is in her view plausible – a domain name is not required if a company’s Facebook page is the first online access point for a consumer.
Five years on from when these sentiments were put across it is apparent that people do spend a lot of time on Facebook. People do engage with brands on other social platforms, and people do oftentimes head straight for social platforms to attain the latest happenings relating to a particular business or brand. That said, this author does not believe that this diminishes the value of an appropriate domain name. Coca Cola for example utilises social platforms for more engaging content to draw its customers into purchasing its products. It’s coke.com website serves as more of a corporate overview. Even so, this usage serves a purpose. If nothing more it prevents a competing brand from taking their market share. Furthermore, the content being shared on social media has to point to somewhere. Until Facebook has replaced ‘The Internet’ as a singular content source there is still clearly a necessity for a mechanism of naming content online.

###Moving forward

The domain name system has been used since the inception of the Internet. People understand it, and thus such a dramatic change to the public side of the workings of the Internet (one could argue) is complex and unnecessary. 

If there were to be a significant change to Internet infrastructure, there would be a significant ramp up time - first developers and technology evangelists would have to get on board, and then there would need to be a significant investment in public education over a period of many years. It is easy to see why we have not seen any fundamental changes to the system over the past ten years.

When one looks at new technologies that have been disruptive online over the past decade, Bitcoin (and blockchain more generally) is a prime example. Whilst Bitcoin has gained a lot of traction in its seven year existence, and has generally been considered a success, one could quite easily argue the exact opposite. It has (as of the time of writing) a $10 billion market cap, and is highly volatile as a currency. Its usage in commerce has increased significantly, but put into perspective its market capitalisation is negligible when compared to Visa (in excess of $160 billion). Whilst an interesting and well received technological development, realistically, without general public knowledge and acceptance one could not call Bitcoin a success. This is exactly the issue that would face a ‘new’ domain name system.

The work of Coase (1937) relates to the idea that independent of initial allocation, bargaining results in an efficient outcome in a world where there are no transaction costs (for more on transaction costs one can read Williamson’s seminal article on the matter). The theorem states that independent of initial property allocation or property rights, bargaining will occur such that the entity who can reap the highest economic benefit from an asset will attain ownership. This invariance proposition suggests that if the initial allocation is not efficient, bargaining will move the economy towards efficiency, without the need to consider the legal implications of any allocation.

With the domain name market in its current state, the market is not competitive – each transaction is a bilateral monopoly transaction (as outlined above). Furthermore, there are obvious transaction costs in the current market. As such a redevelopment of the market system requires the removal of transaction costs. 

Medema and Zerbe (1999) state that *"the goal of the legal system should be to establish a pattern of rights such that economic efficiency is attained"*. 

It is our view (given the previous discussion) that legal monitoring and organisation inherently imposes a cost without necessarily yielding universal results. I thus propose removing the legal coverage of the domain name market (as it currently exists). 

Kesan and Shah (2001) argue that during the privatisation of the DNS system, competition was not allowed to prosper by the management of ICANN (who were directed by the US government). This paper supports the assertion that in the development of the Next Generation Internet (NGI) government should focus on transparency and user input. Kesan and Shah’s quote that *“the U.S. government must ensure that ICANN is accountable to the Internet community as a whole rather than to business interests alone”* is one which can be achieved through interconnection of the DNS management systems with the aftermarket.

As of the time of writing ICANN are currently in the process of working with the United States Department of Commerce to decentralise its oversight and operation. ICANN is moving towards a multi-stakeholder model of oversight. This is a fantastic first step which would allow for a platform upon which any further significant changes could be developed. Unfortunately having attended ICANN conferences, and kept up to date with their operations it is of concern to this author the level of complexity and bureaucracy associated with decision making within the organisation. It is difficult to see such fundamental changes being implemented in the short term giving consideration to the fact that the new gTLD program took over 10 years to fully implement. The concern/benefit (depending on how you look at it) is that new technologies (as outlined below) may take advantage of this lag-time to cement their positions within the future technological landscape.

Within the context of the current landscape one must consider incentives to negotiate. The development of the UDRP process may be considered to have decreased the amount of transactions occurring which result in more efficient allocation. The reason for this belief is first hand experience. Given the inconsistency and questionable outcomes of many UDRP cases, such of those resolved based on 'bad faith' registrations, many refuse to transact at all. The UDRP has held that entering into negotiations with another party implies 'bad faith' – the idea that one has registered the domain name simply to profit from it. This is not necessarily true, as one may have registered the domain for a website, but later valued the offered financial compensation more highly. Such a reallocation is the aim of such a market system, yet the current system penalises the development of such transactions from the outset. Negotiations are also often negatively affected by the current market structure, and the prevalence of brokerage fees and/or commissions. This study’s proposals will effectively remove these, and as a result remove the impact they have on negotiation.

As regards WHOIS ‘privacy’. If a company has costs imposed on it trying to find out who owns a domain name, they are less likely to do it (as discussed previously). Situations like this do not aid purchase negotiations, rather, they may cause the incorrect and unnecessary use of the UDRP process to try and forcibly take domains off their owners in some cases without due cause. This 'force' refers to the legal requirement to give up ones domain if directed to by the panel in a given case. The only redress is to take the case further into the legal system, by taking it to an external court of law – this obviously comes at further cost. Awareness of this exacerbates the problem of people (domain owners) withdrawing from the market completely. The resolution to this is simple -  the abolition of WHOIS privacy services, imposed by ICANN in their registrars’ agreement. 
Further to this, in the registration agreement, it should be required that complete, and accurate data of ownership be provided. This data should then be verified. On paper this requirement has in fact already been implemented. This author receives contact from his registrar on a regular basis requiring he check and verify the contact details contained within the database. Unfortunately however this verification goes no further - there is no ‘actual’ check that the inputted address actually exists or that the domain owner lives there. This, one assumes, is because of the additional cost associated with doing such complete verification. It however seems reasonable that this kind of verification should be the kind of thing funded by the ICANN fee attached to every domain name registration/renewal.

A correct, and complete database of domain ownership will immediately reduce information asymmetries between potential buyer, and seller. Even if any additional costs were added to the registration fee, and paid by domain registrants they would be exogenous to the problem of Coasean marketing efficiency.

The current domain name system is setup with a natural monopoly manager of the central database, ICANN. There is then competition in the market for registrars. The reason why the central database is run by a natural monopoly is because of the complexities in coordination, and cost associated with the alternative. In the same vein, this could be applied to the aftermarket for domains – a centralised auction medium for their reallocation. Once again, the centralised nature of such a structure would minimise the costs of information gathering – people would know who they were dealing with, all parties would have an equal opportunity to acquire a given domain name, and the transaction could be conducted in a secure and organised manner. A setup such as this could also reduce the complexity and cost of the transition period. 

Rather than go 'all in' and enforce valid WHOIS requirements for example, the aforementioned body could enforce the updating of the WHOIS data for a particular domain name once an interested party has expressed interest in it. Essentially the proposal would target reducing information asymmetries and incentivising economically efficient transactions **only** for domain names which are not optimally allocated as is.

By moving the market in-house, and implementing contractual obligations to registrants on registration you create an appropriate environment for a more economically efficient domain name system. This setup certainly complies with the HMRC viewpoint on attaining ‘market value’ for an asset (as discussed previously) which notes that market value:

> *“must be the price on the day which it would be possible to obtain in a sale which was open to all corners”*.

By taking the market in-house, you open it up to everyone. You make it transparent and fair whilst removing the fear and potential for manipulation present in the current system.

Parchomovsky (2001) has written extensively on the idea of redeveloping the nature of the system. He does not explicitly propose removing the need for private auction houses, but rather suggests that dispute resolution should be centralised in-house. Parchomovsky's redevelopment of the system  does not remove the transactions costs, which this study proposes are the cause of sub-optimal allocations. He notes the screening of eligible entrants in a given auction, ignoring the cost of such an action. Likewise he notes eligibility on the basis of those who can *“add independent value”* - something that is inherently subjective (just like the interpretation of judgement devices).
His proposals consider the allocation of bargaining surpluses, developing a complex second price sealed bid process whereby a domain name owner *“is capped by the fear”* when submitting her valuation on the basis that if she wins the process *“she will have to pay the amount of her bid to the trademark owner”*. It is our view that these proposals are completely inappropriate.

We propose an auction process whereby any interested party can place a bid, and assuming it is greater than the registrants private valuation the registration is transferred to whoever comes out on top in a normal auction outcome. If an entity expresses their interest in a domain, the owner is then required to submit a private valuation for the domain. A first price sealed bid auction process can then occur, which as outlined by Molho (1997) will result in revenue equivalence between alternate auction formats. By collecting data on an owner’s willingness to sell prior to revealing the identities of bidders, the outcome which will arise will always be optimal. If any bidding party bids in excess of this amount, then both buyer and seller are made better off. This format intends to emphasise the 'private-value' nature of domain names as opposed to the 'correlated value' nature of transacting with a huge corporation for example. Competition amongst bidders means that the seller gets the highest surplus in excess of his willingness to sell. We feel that this is fair because the owner got there first.

One may note from the proposal above that this does not explicitly remove the problems associated with cybersquatting and the UDRP/ACPA. Moore (2009) makes the point that prevention is better than cure as regards preventing cyber squatting referencing the introduction of ‘sunrise’ periods whereby entities with intellectual property rights have first right of refusal. 

Within the context of the new gTLD launch process, a number of registries did implement such Sunrise programs. Donuts for example (the largest single applicant for new gTLDs) implemented a sunrise process whereby mark holders could apply for their domains prior to a general public release. In the cases whereby multiple ‘valid’ mark holders applied for such a registration, a closed auction process would occur to allow for its correct allocation. In addition to this they implemented the Domains Protected Marks List (DPML) which allows for an appropriate mark holder to ‘block’ the registration of their mark in any of Donut’s gTLDs without the (costly) requirement for them to personally register their mark in every extension. Finally they implemented their Early Access Program (EAP) which was a seven day period prior to the general availability of a given extension in which actors who placed a higher economic value on any particular domain name had an opportunity to register it at a significantly increased cost. On Day 1, the registration may for example be priced at $12,000 USD while on Day 7 (assuming no-one has registered the domain in question) it would be reduced down to $100. Whilst this does allow for the entity that values a domain name most highly to ‘get it’, a cynic would argue that such a process was merely implemented to (understandably) line the pockets of Donuts. 
It is certainly a positive thing that we are not simply repeating the same mistakes, that we are learning from history, and that we are implementing improved approaches to allocation within the new stages of the Internet. That said, this does bring to the forefront of our analysis the issue of the public/private nature of the Internet - should the network have ever been developed in such a manner so as to allow private business to (in any capacity) influence who accesses online resources, and how they do it? Surely the Internet is inherently a public good and as such should be managed like one?

Gilwit (2003) notes that the ACPA and UDRP do provide a mechanism to protect a mark once a registration occurs, but there is no mechanism in place to prevent it happening in the first place. She suggests a connection with the Patents and Trademarks office such that trademark holders get notice, and can respond to potential infringements before the registration is successful. Obviously the domain name system is relatively mature now and such as is described above can not be retrospectively implemented. It is however proposed that such a consideration should be added moving forward. This does however introduce a number of additional transaction costs - time, and administration costs being the most apparent. These place an unnecessary constraint one the free flowing nature of information online.

The UDRP process should be simplified, costless, and consistent. The UDRP process is excessively costly meaning that an individual, or small business with legitimate rights to a domain may not be able to fight for the rights to his/her domain. On the flip side, large companies are not inhibited by the costs of the process and can essentially throw their weight around fighting for domains to which they have no rights. This is why we have proposed removing the UDRP in its current form.

By implementing the proposals put forth thus far, the direct transaction cost is instantaneously removed. To 'cure' the problem of cybersquatting already prevalent within the domain name system, we propose (aptly perhaps) the use of crowd sourcing knowledge from those knowledgeable on the subject, namely those academics, policy makers, and industry insiders whose previous work these proposals have been based upon. Such a costless and powerful tool (see Kittur et al (2011)) again gets suitable results at negligible cost. Whilst this is seemingly contradictory to the sentiment of this paper that explicitly notes the differing nature of opinions and interpretation of judgement devices, it is feel that crowd-sourced information somewhat resolves this problem. By using a crowd sourced decision making process you essentially average out the outlying views. One would hope that across the board a clear decision would be discernible from such a process. This is similar in nature to the current UDRP except at scale. Some UDRP decisions are currently made on the basis of a single panellist, whilst others are based on the view of three. We believe that there should be more stakeholders in these important decision making processes.

As suggested by Baum (2001), the UDRP process should only be used *“in exceptional cases where bargaining between the parties fails due to a bilateral monopoly and asymmetric information a transfer might be socially efficient because of reductions in search costs”*. In the context of our proposals such misallocations will be resolved by preventing them from happening in the first place.

It is quite understandable that one would want all of the answers up front prior to implementing such significant changes to a market. In reality however it is often the process of implementation, the experience, and the real world utilisation of a system which allows one to discern what needs more thought, and where things need improving. The proposals thus far suggest that in an idealised outcome UDRP and legal recourse would not be required at all. It is however worthwhile considering those edge cases where independent of our efforts legal remedies are needed. What if for example a domain name owner cannot engage in the process as a result of having died? What if a domain owner simply does not respond to a request for their 'willingness to sell'?

Our proposed policy requirements and the development of an in-house auction platform seek to minimise the costs of reallocating (both contentious and non-contentious) domain names.
In the few cases where the system simply does not allow for this to occur we again propose the utilisation of crowd sourced information to discern as to if the case should be taken further, and if so how it should be done. This process could only be utilised when a predefined level of contention is noted, and abuse of it would be met with contractually enforced fines (within the process agreement).

By coordination with the proposed centralised system, many of the legal uncertainties associated with current UDRP processes would be eliminated as all the information regarding transaction negotiations would be held in-house. Uncertainty and the subjective nature of the current 'rules' which have in the past lead to questionable decisions would be removed. As regards the logistics of the system, at this present time the details and rules which panellists follow are long and complex, yet UDRP results are inconsistent and questionably fair. If an individual named 'Jack Benson' owns benson.com, he should retain his right to its usage over 'Benson Corp' because he got there first. Through crowd sourcing decisions, these outcomes will arise.

To apply this study’s proposals to a particular example, the case of Octopus.com will be considered. The domain was registered in 1986 – it is one of the oldest domain names on the Internet. Although the domain name has been resold since, one can assume that such a generic name sold for a significant amount. Although 'Octopus' may be trademarked in relation to particular industries, it is a generic word. It is an animal. As such when it was taken from its owner on the basis that it showed adverts relating to travel, an industry in which there is a company named 'Octopus travel', there was serious debate as to the extent to which this was 'bad faith' usage. The case was further complicated by the fact that the domain owner provided a fake name.
Our proposal would avoid identification problems from the outset. The owner would define a value, independent of potential buyers, and then any bidders would submit sealed bids. The highest sealed bid in excess of the valuation would win the domain, and the transaction would be completed in house as a co-ordinated, and automated process. If, as cited in the case, the owners connection to the travel company did constitute bad faith, our new look UDRP process could be utilised and a crowd sourced decision could be made. The complainant would need to duly consider the fine that would be imposed should the case not go in their favour.

**Table 2**. A summary of our proposals, and their effects.

<table>
<tr>
<th>Problem</th>
<th>Transaction costs</th>
<th>Resolution</th>
<th>Result</th>
</tr>

<tr>
<td>
UDRP removes incentives to negotiate – 'bad faith' is subjective, and abuse is possible. 
</td>
<td>
The direct costs of the UDRP.
</td>
<td>
Reduce the significance of legal options within the system.
</td>
<td>
Remove reliance on subjective judgement. More worthwhile transactions will occur.
</td>
</tr>

<tr>
<td>
Anonymity inhibits negotiations - domain owners are not easily identified.
</td>
<td>
Costs of discerning ownership. 
</td>
<td>
Remove the option for WHOIS privacy, and collect and verify registrant identity information.
</td>
<td>
Removal of transaction inhibitors will mean legal options are used in a more suitable manner.
</td>
</tr>

<tr>
<td>
Decentralised, and overcrowded aftermarket setup introduces complexities into the system. e.g. those associated with the bilateral monopoly nature of independent negotiations.
</td>
<td>
Costs of commission and/or brokerage.

Endowment effects, and risk aversion.
</td>
<td>
Centralise the aftermarket alongside the administration aspect of the domain name system.
</td>
<td>
Economies of scope can be achieved. Improved coordination through minimisation of information asymmetries aids efficient transacting. Consistent competition for domain names as opposed to bi-lateral monopoly transacting.
</td>
</tr>

<tr>
<td>
Lack of fair protection for rights holders.
</td>
<td>
Direct costs – lost profit, damaged reputation, trademark dilution.

Costs of confusion and search costs.


</td>
<td>
Introduce verification procedures for potential infringements before acceptance of a registration. Provide crowd sourced resolution of current disputes.
</td>
<td>
Less requirement or need for ex-post reliance on legal options. Resolution of current misallocations in a cheap, efficient manner.
</td>
</tr>

</table>


It is felt that the summary of the proposals outlined in table 2 (above) demonstrates how this work has sought to minimise or remove the transaction costs of the current system such that all worthwhile transactions occur through an open and inclusive auction process which extracts the highest willingness to pay (that of the highest bidder) for the seller. The outcome is Pareto optimal and provides the seller with the bargaining surplus benefits associated with these improved proposals.

This amounts to what Karpik describes as ‘capture’ which *"aims to replace choice by lock-in*. Such proposals essentially amount to the creation of a ‘singular service’, something that given the context this author believes to be a good thing.

## Replacing the domain name system

In the previous section reference is made to the decentralised nature of the domain name aftermarket (in its present form). It is proposed that a resolution to the problem could be to centralise the aftermarket so as to make it accessible and costless to all.

At the time of writing decentralisation is a buzzword often associated wth Blockchain technology. An alternative resolution to the issues with the current situation would be to embrace new technologies (such as Blockchain).

### Decentralise

Bitcoin and Blockchain technology was previously mentioned (in passing) above. These technologies have bought to the forefront of peoples minds a number of pertinent issues, namely those of trust and autonomy.

As discussed in the previous sections, a number of issues have arisen in the current domain name system as a result of private entities having what this author deems to be to much authority and control of a system that is meant to aid in the utilisation of a public good. As such, whilst we have proposed a ‘best possible’ resolution for the issues in the context of not throwing the current system in the bin and starting again, perhaps it is time that we did exactly that, and started again.

### Ethereum

The Ethereum project is one relatively new Blockchain project which has recently garnered a lot of attention. Conceptually it offers a generic platform that allows for the completely decentralised execution of smart contracts. 
Whereas Bitcoin is essentially nothing more than a currency, Ethereum implements similar technology in such a manner that any programmer can write a ‘smart-contract’ that will be executed on the Blockchain. For example, companies such as slock.it are writing contracts that allow physical objects to be connected to the Ethereum network - a lock for example could be connected to the network such that on receipt of a payment by a user the lock automatically opens.
One reason as to why Ethereum has a lot of merit is because it is *trustless*. Millions of users around the world run Ethereum ‘nodes’ on their computers which verify the transactions that are occurring.
In relation to currency, you can manipulate the node running on your computer such that it believes that you have 1,000,000 Ether (the main currency of the network) but because no other computers on the network agree with this, the correct consensus agreement will be reached echoing the fact that in reality you have 0 Ether.

The relevance of this to the domain name system is that by running the domain name system on the Ethereum network or by completely replacing the domain name system, one to all extents and purposes can reduce all of the transaction costs associated with the current system, whilst allowing for the implementation of better economic allocation considerations.

Guerra, Zizzo et al outlined back in 2003 that *“the growth of e-commerce could be inhibited by particular approaches to enhancing trust”* and sought to find *“an appropriate framework that balances the need to offer consumer protection while maintaining e-commerce growth”*. Whilst one can certainly state that in the thirteen years that followed e-commerce has grown significantly, it surely has more potential should these very constraints be removed. Ethereum could plausibly do that.
It is further interesting to note that these authors stumbled upon the concept of “digital tokens” and “e-cash” as a potential ‘trust enabler’ many years before even Bitcoin had been developed.

Given the nature of the Ethereum network, anyone can create a ‘name registrar’. That is to say, I can create a smart contract which maps ‘names’ to.. anything. Given this, an Ethereum based domain name system would amount simply to a smart contract mapping domain names to IP addresses.
There is currently a proposal (and discussion) ongoing about how a ‘default’ name registrar could be implemented on the Ethereum network. Whilst this is intended as a methodology for linking to user accounts and smart contracts on the network it is plausible that a separate smart contract could be developed to allow DNS to co-exist with/run off the Ethereum network. From the outset, one of the main considerations is as to how one can assure that the initial allocation, and the allocation going forward is appropriate and fair. The current proposals aim to discern the optimal price for a given name, provide a transparent market for the purchase/sale of names, and disincentivise squatting. Careful consideration has also been to developing the system over time such that current participation yields no advantage over future participation in respect of making sure that the entity who places the most economic value on a domain name can own it over any given registration period. The proposals further extend to a democratic voting process which allows for the rules of the ‘game’ to develop over time.

It is clear to see from the proposals that specific attention has been paid to historical implementations of naming systems (like the domain name system) when putting them together. They are starting with a clean slate (of sorts) and are looking to 'get it right' first time.

The problem of network effects and the value instilled in a system based upon mass adoption is also resolved by the Ethereum network. Resolutions for name registration (such as that outlined above) allow for economically efficient allocation of resources amongst providers. The Ethereum network also provides utility to consumers in terms of its potential for universal identification systems, reputation systems etc. That is to say it offers incentives for consumers and providers to use it whilst providing better mechanisms for economic allocation of resources - it is the best of both worlds.

Here in the UK, services like Experian allow for identity verification for utilisation of various services. If for example you want to take out a mobile telephone contract or sign up for a credit card, your identity can be checked and your ‘credit-worthiness’ discerned utilising one of these services. Similarly HMRC have now implemented various software integrations with services like Experian and the Post Office to allow/require identity verification prior to utilising their online services. That is to say that identity verification is feasible, and integral to secure and trustworthy utilisation of services on the Internet. An implementation of identity and reputation management services on the Ethereum network would allow for a universal system that services (such as our proposed 'new' DNS system) could integrate with. Whilst there might be initial costs associated with development and adoption of such a service, there are clearly already extensive costs associated with the current systems. A government supported Ethereum based system would admittedly have significant sunk costs but its marginal costs of operation would be relatively insignificant.

### The Bandwagon Effect

Ethereum, at the time of (initial) writing (the first quarter of 2016) is currently experiencing a speculative bandwagon effect. This is similar in nature to that which occurred with Bitcoin (on numerous occasions). 

In reality for a technology to be successful, a speculative bandwagon effect will not suffice. General uptake of a technology is required. If a technology hits the mainstream as a result of a bandwagon effect then intriguingly it may become self sustaining in nature.

That is to say that even though this author suspects that a lot of people are taking note of Ethereum because other people are, the sentiment that all publicity is good publicity applies. If more people are using the Ethereum network and/or telling others about it (regardless of whether they appreciate the promise of the technology) then its uptake will continue to increase. As its uptake increases we will likely see the development of network effects (as discussed previously) which will further increase interest in the technology.

As of late July 2016 there have been a number of complex happenings within the Ethereum ecosystem. This paper pertains to the domain name system and as such I will avoid going into the details of the intricacies. What I will note is that not all of the happenings have been ideal or positive yet Ethereum is still growing and showing extremely positive signals. As a consensus driven piece of software the Ethereum community has demonstrated how a community of stake holders can work together to reach consensus on tough and contentious issues (thefts, attacks, and market manipulations). These are the very premises upon which a number of my proposals are based. As such it follows that if humans can work alongside software ('code') in such a manner then a combinatory implementation of my proposals could occur on or alongside the Ethereum network to take DNS to the next level.

On April 26th 2016 the British government hosted its first ‘blockchain partnership event’ where specific note was made of Ethereum and its potential. It is difficult not to take note of Ethereum when governments of large economies are. One must appreciate that the reason that the UK government are looking at Ethereum is because it is an exceptional technological concept/development.

As Ethereum has been conceptually developed there has been a lot of discussion as to whether Ethereum will displace Bitcoin. This is somewhat of a naive question in that Bitcoin and Ethereum are different things - Bitcoin is in essence a currency whereas Ethereum is a technological ecosystem.

Whilst Bitcoin does have network effects (of sorts), the nature of the speculative bandwagoning that have occurred mean that many simply do not take it seriously. Some would argue that it is not a currency, but rather nothing more than a speculative medium that exists purely for manipulation.

In the interest of avoiding any potential biases it is important to note that Ethereum has also experienced a similar (albeit much smaller) bandwagoning effect over the first half of 2016. 

The argument that Bitcoins ‘size’, and network effects are such that it would never be displaced are also exceptionally naive. One can draw comparisons with the VHS tape that was the preferred medium through which one could watch ‘recorded’ television/movies in the 1980s/90s. Park (2004) discussed how and why VHS rose to dominance in the 80s, yet 25 years on a VHS tape is nowhere to be seen.

It is this authors view that whilst both will continue to develop into the future Ethereum has a first-mover advantage in that it does what is required for a new age DNS system to be implemented out of the box. Bitcoin protocols require complex adaptations to allow it to work as anything but a currency.

These technologies are still in their infancy and are still going through development iterations. It is however plainly obvious that they have **a lot** of potential.

## Conclusions

For a domain name system to work ‘perfectly’ we require that all actors are perfectly rational, and that domain name valuations be a science. In reality, this is not the case.

The optimal domain name system requires that we minimise any possibility that economically sub optimal allocations of domain names occur. To do this we need to provide a system through which information asymmetries are non-existent (or at least minimised).

It is apparent that putting any public good  under the control of private entities will result in poor economic outcomes - private entities have different economic incentives. That said any system will still encounter issues if not built in such a manner that pre-emptively considers reallocation.

The proposals put forward previously answer a number of questions, but present a number of others. Whilst the author attests that a centralised domain name aftermarket would be better than the current system he is also amenable to the fact that the effort involved in implementing such proposals would perhaps be better spent implementing a more fully fledged resolution on the Ethereum network.
Whilst doing so would be a slow and arduous process (requiring further development of the product, further uptake by technology evangelists, and down the line mass adoption by the general public) the end result would be much better and would leave far fewer (perhaps no) unanswered questions.
The domain name system has ‘worked’ in its current form for 30 years without significant changes. Whilst it could be better, at this stage of the day this author believes it to be worth waiting a few more years and replacing it with a resolution that is absolutely fit for purpose.

## References

* Ambrus, A., Chaney, E., & Salitskiy, I. (2014). Pirates of the Mediterranean: An Empirical Investigation of Bargaining with Asymmetric Information. Retrieved from http://papers.ssrn.com/sol3/papers.cfm?abstract_id=1954149

* Anglin, P., & Wiebe, R. (2011). Pricing in an Illiquid Real Estate Market. Retrieved from http://pages.jh.edu/jrer/papers/pdf/forth/accepted/pricing in an illiquid real estate market.pdf

* Berkens, M. (n.d.). The Number of .Com Domains Top 124 Million For The First Time. Retrieved from http://www.thedomains.com/2016/01/05/the-number-of-com-domains-top-124-million-for-the-first-time/

* Butts, C. (2010). The Chicken Game. San Antonio Lawyer. Retrieved from http://c.ymcdn.com/sites/www.sanantoniobar.org/resource/resmgr/imported/ChickenGame.pdf

* Cain, C. (2008). Sociological Questions. Sociological Questions. Retrieved from http://www.slideshare.net/cainc3/sociological-questions-269288

* Glower, M., Haurin, D., & Hendershott, P. (1995). Selling price and selling time: The impact of seller motivation. Retrieved from http://www.nber.org/papers/w5071.pdf

* Huang, E. (n.d.). China’s newest investment craze is short domain names. Retrieved from http://qz.com/581248/chinas-latest-investment-craze-is-short-domain-names/

* Karni, E. (1988). On the equivalence between descending bid auctions and first price sealed bid auctions. Theory and Decision, 25(3), 211–217. Retrieved from http://link.springer.com/article/10.1007%2FBF00133162

* Klemperer, P. (n.d.). Auctions: Theory and Practice. Retrieved from http://www.nuff.ox.ac.uk/users/klemperer/VirtualBook/07_Chapter1.pdf

* Muthoo, A. (2001). The Economics of Bargaining. Retrieved from https://www2.warwick.ac.uk/fac/soc/economics/staff/amuthoo/publications/unesco.pdf

* Sundem, G. (2012). A Fun DIY Science Goodie: The Behavioral Economics of Agreement (and Why Negotiations Fail). Retrieved from http://blogs.scientificamerican.com/guest-blog/a-fun-diy-science-goodie-the-behavioral-economics-of-agreement-and-why-negotiations-fail/

* Bargain like a Somali. (2012). The Economist. Retrieved from http://www.economist.com/news/finance-and-economics/21567077-how-negotiate-pirates-horn-africa-bargain-somali

* Sunrise Overview. (n.d.). Retrieved from http://www.donuts.domains/services/sunrise-overview

* Domains Protected Marks List. (n.d.). Retrieved from http://www.donuts.domains/services/dpml

* Early Access Program. (n.d.). Retrieved from http://www.donuts.domains/services/early-access-program

* ERC: Default Ethereum Name Registrar. (n.d.). Retrieved from https://github.com/ethereum/EIPs/issues/26

* Levin, J. (2004). Auction Theory. Retrieved from http://web.stanford.edu/~jdlevin/Econ 286/Auctions.pdf

* Lancaster, K. (1966). A New Approach to Consumer Theory. Journal of Political Economy, 74(2), 132–157. Retrieved from http://sites.psu.edu/scottcolby/wp-content/uploads/sites/13885/2014/07/Lancaster1966_A-New-Approach-to-Consumer-Theory.pdf

* Williamson, O. (1981). The Economics of Organization: The Transaction Cost Approach. American Journal of Sociology, 87(3), 548–577. Retrieved from https://www2.bc.edu/~jonescq/mb851/Feb19/Williamson_AJS_1981.pdf

* Caves, R. (2002). Creative Industries: Contracts between Art and Commerce. Retrieved from http://www.hup.harvard.edu/catalog.php?isbn=9780674008083

* Knight, F. (1921). Risk, Uncertainty and Profit. Retrieved from https://books.google.co.uk/books?hl=en&lr=&id=LFsVFS3OG_gC&oi=fnd&pg=PP1&dq=knight+radical+uncertainty&ots=pM6Ytec3XS&sig=QHxOxOOF3IW1JbdQIQmK-pVqobI#v=onepage&q=knight radical uncertainty&f=false

* Norman, D. (1991). Cognitive Artifacts. Retrieved from http://hci.ucsd.edu/10/readings/norman_cognitiveartifacts.pdf

* Weber, M. (1978). Economy and Society. An Outline of Interpretive Sociology.

* Incommensurable - definition. (n.d.).

* Cunyat, A. (1998). Strategic Negotiations and Outside Options. Retrieved from http://147.156.1.4/~acunat/surveyengl.PDF

* Compte, O., & Jehiel, P. (2000). On the Role of Outside Options in Bargaining with Obstinate Parties. Retrieved from http://www.enpc.fr/ceras/jehiel/opt000621b.pdf

* Akerlof, G. (1970). The Market for “Lemons”: Quality Uncertainty and the Market Mechanism. The Quarterly Journal of Economics, 84(3), 488–500. Retrieved from http://www.econ.yale.edu/~dirkb/teach/pdf/akerlof/themarketforlemons.pdf

* Allemann, A. (2010). “Halvarez” Caused $2M Loss to SnapNames Customers. Domain Name Wire. Retrieved from http://domainnamewire.com/2010/02/16/halvarez-caused-2m-loss-to-snapnames-customers/

* Develgas, T. (2012). Why I removed my entire domain portfolio from Sedo. Acro.net. Retrieved from http://acro.net/blog/why-i-removed-my-entire-domain-portfolio-from-sedo/

* Beale, C. (2016). US government to surrender control of internet administrator ICANN. The Independent. Retrieved from http://www.independent.co.uk/news/world/americas/us-government-to-surrender-control-of-internet-administrator-icann-a6829466.html

* Loomes, G., & Sugden, R. (1982). Regret Theory An Alternative Theory of Rational Choice Under Uncertainty. The Economic Journal, 92(368), 805–824. Retrieved from https://www.jstor.org/stable/2232669

* Nash, J. (1950). Equilibrium Points in n-Person Games. Retrieved from http://web.mit.edu/linguistics/events/iap07/Nash-Eqm.pdf

* Picker, R. (1994). An Introduction to Game Theory and the Law. Retrieved from http://www.law.uchicago.edu/files/files/22.Picker.IntroGame_0.pdf

* Aumann, R. (1995). Backward induction and common knowledge of rationality. Games and Economic Behaviour, 8(1), 6–19. Retrieved from http://www.sciencedirect.com/science/article/pii/S0899825605800156

* Berg, J. (1995). Trust, Reciprocity, and Social History. Games and Economic Behaviour, 10, 122–142. Retrieved from http://dibartolomeo.comunite.it/courses/ee/Berg et al 1995.pdf

* Brulhart, M., & Usunier, J.-C. (2010). Does the trust game measure trust? Retrieved from http://www.hec.unil.ch/mbrulhar/papers/trustnote02.pdf

* Guerra, G., & Zizzo, D. (2003). Economics of Trust in the Information Economy: Issues of Identity, Privacy and Security. Retrieved from http://www.hec.unil.ch/mbrulhar/papers/trustnote02.pdf

* Evans, A., & Krueger, J. (2009). The Psychology (and Economics) of Trust. Social and Personality Psychology Compass, 3, 1003–1017. Retrieved from http://files.clps.brown.edu/jkrueger/journal_articles/krueger-2009-thepsychologytrust.pdf

* Bohnet, I., Greig, F., Herrmann, B., & Zeckhauser, R. (2008). Betrayal Aversion: Evidence from Brazil, China, Oman, Switzerland, Turkey, and the United States. American Economic Review, 98(1), 294–310. Retrieved from https://www.nottingham.ac.uk/cedex/documents/publications/bohnet-etal.pdf

* Fetchenhauer, D., & Dunning, D. (2010). Why So Cynical? Asymmetric Feedback Underlies Misguided Skepticism Regarding the Trustworthiness of Others. Retrieved from http://pss.sagepub.com/content/early/2010/01/08/0956797609358586

* Kosfield, M., Heinrichs, M., Zak, P., Fischbacker, U., & Fehr, E. (2005). Oxytocin increases trust in humans. Nature, 673–6. Retrieved from http://www.ncbi.nlm.nih.gov/pubmed/15931222

* Bosch-Domènech, A. (2009). The effects of alcohol on trust, trustworthiness and risk. Retrieved from http://www.wine-economics.org/aawe/wp-content/uploads/2013/07/35-Reims2009-Bosch-Domenech.pdf

* Hajidimitriou, Y., & Sklavounos, N. (n.d.). The Trust Dimension in International Business Systems. Retrieved from http://mibes.teilar.gr/ebook/ebooks/Hajidimitriou-Sklavounos 43-57.pdf

* Denton, L. (2016). Let’s talk Blockchain. Government technology. Retrieved from https://governmenttechnology.blog.gov.uk/2016/04/27/lets-talk-blockchain/

* Park, S. (2004). Quantitative Analysis of Network Externalities in Competing Technologies: The VCR Case. The Review of Economics and Statistics, 86(4), 937–945. Retrieved from http://www.mitpressjournals.org/doi/abs/10.1162/0034653043125275#.VyIeR-aDGko

* Kahneman, D., Knetsh, J., & Thaler, R. (1991). Anomalies: The Endowment Effect, Loss Aversion, and Status Quo Bias. Journal of Economic Perspectives, 5(1), 193–206. Retrieved from https://www.aeaweb.org/articles?id=10.1257/jep.5.1.193

* Sanders, J. (2016). ICANN’s generic top-level domain rules cause major headaches for online businesses. TechRepublic. Retrieved from http://www.techrepublic.com/article/icanns-generic-top-level-domain-rules-cause-major-headaches-for-online-businesses/

* Jackson, R. (2016). The Lowdown. DNJournal. Retrieved from http://www.dnjournal.com/archive/lowdown/2016/dailyposts/20160411-2.htm

* SVM10090 - Share Valuation Manual: The Statutory Open Market. Retrieved from http://webarchive.nationalarchives.gov.uk/+/http://www.hmrc.gov.uk/manuals/svmanual/svm10090.htm

* Bao, H., & Gong, C. (2015). Endowment Effect and Housing Decisions. Retrieved from http://www.crerc.landecon.cam.ac.uk/files-and-documents/rerc-wp-2015-1.pdf

* List, J. (2003). Does market experience eliminate market anomalies? The Quarterly Journal of Economics. Retrieved from http://users.nber.org/~rosenbla/econ311/syllabus/listendowmenteffect.pdf

* Oster, S., & Morton, F. (2006). Does the Endowment Effect Exist in a Real Market? Retrieved from http://else.econ.ucl.ac.uk/conferences/consumer-behaviour/scottmorton.pdf

* Sharrock, L. (2001). The future of domain name dispute resolution: Crafting practical internation legal solutions from within the UDRP. Duke Law Journal, 51(817). Retrieved from http://scholarship.law.duke.edu/cgi/viewcontent.cgi?article=1145&context=dlj

* Economics. (n.d.). In Wikipedia. Retrieved from https://en.wikipedia.org/wiki/Economics

* Behavioural Economics. (n.d.). In Wikipedia.

* Yavas, A., Miceli, T., & Sirmans, C. (2001). An Experimental Analysis of the Impact of Intermediaries on the Outcome of Bargaining Games. Real Estate Economics, 29(2), 251–276. Retrieved from http://onlinelibrary.wiley.com/doi/10.1111/1080-8620.00010/abstract

* Mueller, M. (1998). The battle over Internet domain names: Global or national TLDs? Telecommunications Policy, 22(2), 89–107. Retrieved from http://www.sciencedirect.com/science/article/pii/S0308596197000621

* Kamath, N. (2001). The Game of the Name - Personal Name Domain Names and Applicable Law. Retrieved from http://www.bileta.ac.uk/content/files/conference papers/2001/The Game of the Name - Personal Name Domain Names and Applicable Law.pdf

* Pareto Efficiency. (n.d.). In Wikipedia.

* Ramello, G. (2005). Intellectual Property and the Markets of Ideas. Review of Network Economics, 4(2). Retrieved from http://www.degruyter.com/view/j/rne.2005.4.issue-2/rne.2005.4.2.1071/rne.2005.4.2.1071.xml

* Goldman, E. (2005). Deregulating Relevancy in Internet Trademark Law. Emory Law Journal, 54. Retrieved from http://papers.ssrn.com/sol3/papers.cfm?abstract_id=635803

* Oram, J. (1997). The Costs of Confusion in Cyberspace. Retrieved from http://heinonline.org/HOL/LandingPage?handle=hein.journals/ylr107&div=33&id=&page=

* Stigler, G. (1961). The Economics of Information. The Journal of Political Economy, 69(3), 213–225. Retrieved from http://home.uchicago.edu/~vlima/courses/econ200/spring01/stigler.pdf

* Bakos, J., & Nault, B. (1997). Ownership and Investment in Electronic Networks. Retrieved from http://pubsonline.informs.org/doi/abs/10.1287/isre.8.4.321

* Litman, J. (2000). The DNS Wars: Trademarks and the Internet Domain Name System. Retrieved from http://heinonline.org/HOL/LandingPage?handle=hein.journals/jsebl4&div=12&id=&page=

* Nathenson, S. (1997). Showdown at the Domain Name Corral: Property Rights and Personal Jurisdiction Over Squatters, Poachers and Other Parasites. Univeristy of Pittsburgh Law Review, 58(4). Retrieved from http://papers.ssrn.com/sol3/papers.cfm?abstract_id=1473884

* Kratzke, W. (1991). Normative Economic Analysis of Trademark Law. University of Memphis Law Review, 21(2). Retrieved from http://papers.ssrn.com/sol3/papers.cfm?abstract_id=1702386

* White, J. (n.d.). ICANN’s Uniform Domain Name Dispute Resolution Policy in Action. Retrieved from http://scholarship.law.berkeley.edu/cgi/viewcontent.cgi?article=1309&context=btlj

* Karpik, L. (2010). Valuing the Unique: The Economics of Singularities. Retrieved from http://press.princeton.edu/titles/9215.html

* Moore, T., & Edelman, B. (2010). Measuring the Perpetrators and Funders of Typosquatting. Retrieved from http://www.benedelman.org/typosquatting/typosquatting.pdf

* Hancock, D. (2001). An Assessment of ICANN’s Mandatory Uniform Dispute Resolution Policy in Resolving Disputes Over Domain Names.

* Parchomovsky, G. (2001). On Trademarks, Domain Names, and Internal Auctions. Retrieved from http://scholarship.law.upenn.edu/faculty_scholarship/569/

* Cortes, P. (2008). An Analysis of the UDRP Experience: Is it Time for Reform? Computer Law and Security Report, 24(4). Retrieved from http://papers.ssrn.com/sol3/papers.cfm?abstract_id=1010088

* Piontkowski, B., & Kenefick, M. (2005). Nissan Motor Co. V. Nissan Computer Corp.: The Point at Which Fame Is Determined under the Federal Trademark Dilution Act.

* Deveci, H. (2003). Domain Names: Has Trade Mark Law Strayed From Its Path? Internation Journal of Law and Information Technology, 11(3). Retrieved from http://dl4a.org/uploads/pdf/DOMAIN NAME LAW.pdf

* List of new gTLDs Google applied for. (n.d.). Retrieved from https://domaintyper.com/new-gTLD/applicant/Google

* Thomas, J. (2011). FIFTEEN YEARS OF FAME: THE DECLINING RELEVANCE OF DOMAIN NAMES IN THE ENDURING CONFLICT BETWEEN TRADEMARK AND FREE SPEECH RIGHTS. Retrieved from http://repository.jmls.edu/cgi/viewcontent.cgi?article=1268&context=ripl

* Coase, R. (1937). The Nature of the Firm. Retrieved from http://www3.nccu.edu.tw/~jsfeng/CPEC11.pdf

* Medema, S., & Zerbe, R. (1999). The Coase Theorem.

* Molho, I. (1997). The Economics of Information: Lying and Cheating in Markets and Organizations. Retrieved from http://eu.wiley.com/WileyCDA/WileyTitle/productCd-0631206663,subjectCd-EC10.html

* Moore, M. (2009). Cybersquatting: Prevention better than cure? Internation Journal of Law and Information Technology, 17(2). Retrieved from http://ijlit.oxfordjournals.org/content/17/2/220.short

* Gilwit, D. (2003). The Latest Cybersquatting Trend: Typosquatters, Their Changing Tactics, and How to Prevent Public Deception and Trademark Infringement. Washington University Journal of Law & Policy, 11. Retrieved from http://openscholarship.wustl.edu/law_journal_law_policy/vol11/iss1/11/

* Kittur, A., Smus, B., Khamkar, S., & Kraut, R. (2011). No Title. Retrieved from https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/39980.pdf

* Octopustravel Group Limited v. Alexander Rosenblatt aka Yana Belkova (2011). Retrieved from http://www.wipo.int/amc/en/domains/search/text.jsp?case=D2011-0417
