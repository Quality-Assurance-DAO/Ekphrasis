---
description: Blockchain Governance Principles
---

# Blockchain Governance Principles

{% embed url="https://youtu.be/QEoQFesgUnc" %}

## Blockchain Governance Principles

![](<../.gitbook/assets/2022-02-17 (1).png>)

Welcome everyone.

I would like to preface this presentation with the disclaimer that I am not an expert in Game Theory, Voting Systems or Social choice theory. My background is in Academic Philosophy and I approach these subjects as an amateur.

The purpose of this presentation is to draw attention to an interesting resource for understanding Blockchain governance in Cardano & Catalyst and to highlight possible further routes of enquiry.

The materials presented here will form part of the QADAO Ekphrasis philosophy GitBook which was successfully voted for in Fund 7 last week.

## “SoK: Blockchain Governance”

![](<../.gitbook/assets/2022-02-17 (2).png>)

This presentation is an overview of Prof Aggelos Kiayias & Philip Lazo’s recent paper “SoK: Blockchain Governance” published on the 19th January 2022.

Here is a link to the paper - [https://arxiv.org/pdf/2201.07188.pd](https://arxiv.org/pdf/2201.07188.pdf)[f](https://arxiv.org/pdf/2201.07188.pdf)

Prof [Aggelos Kiayias](https://iohk.io/en/team/aggelos-kiayias) is Chief scientist at IOG Academic Research & the Chair in cybersecurity and privacy at the University of Edinburgh and [Philip Lazos](https://iohk.io/en/team/philip-lazos) is Research Fellow at IOG, Academic Research.

Further details can found by following the links to their IOHK profiles.

## Overview

![](<../.gitbook/assets/2022-02-17 (3).png>)

### The Social Choice Theory context

The paper “SoK: Blockchain Governance” published on 19th January 2022 provides a useful entry point into Blockchain Governance. The Authors focus is on voting systems. But the paper also hints at the broader context and references Social Choice Theory which addresses the more general governance challenge of aggregating individual preferences into societal preferences.

### Challenges of decentralised nature of blockchain governance

As the authors point out in their introduction, the decentralised nature of blockchain governance introduces new challenges where the diverse needs and preferences of participants will not always align. Therefore a degree of stability is sought to balance these diverse needs and to mitigate division.

### Off-chain & on-chain governance

In this context different governing mechanisms may take the form of 1) off-chain governance which is centralized in the trust invested in core developers or key contributors and 2) the voting mechanisms of on-chain governance which can be more transparent and inclusive.&#x20;

### Community division

But these mechanisms themselves are no guarantee against community division. If consensus fails then one part of the community can adopt a change they see as beneficial to themselves leaving another part of the community behind.

![](<../.gitbook/assets/2022-02-17 (4).png>)

### Approach / Methodology

The approach the paper “SoK: Blockchain Governance” takes is to “derive a set of properties, that are drawn from general governance principles and election theory\
and then interpret them to the blockchain governance setting.”

### Sources

The sources the authors draw on include Council of Europe technical standards for e-voting, the Federal Election Commission’s Voting Systems Standards as well as blockchain specific standards.

### Evaluate a range of blockchain platforms

The authors go on to evaluate a range of blockchain platforms against those properties identifying their strengths and weaknesses. For the sake of brevity and focus I will not be covering the entirety of this section today. But rather on the Authors assessment of Project Catalyst.

### Related Work

A paper referred to in Related Work is also worth exploring –

Defining Blockchain Governance: A Framework for Analysis and Comparison ([https://slingerjansen.files.wordpress.com/2020/03/defining-blockchain-governance-a-framework-for-analysis-and-comparison.pdf](https://slingerjansen.files.wordpress.com/2020/03/defining-blockchain-governance-a-framework-for-analysis-and-comparison.pdf)) which takes an open source approach and defines blockchain governance as ”the means of achieving the direction, control, and coordination of stakeholders within the context of a given blockchain project to\
which they jointly contribute”.

## A) Confidentiality - Security properties

![](<../.gitbook/assets/2022-02-17 (5).png>)

The first Blockchain Governance property has to do with the confidentiality of stakeholder involvement. How participation in governance is secured and verified.&#x20;

The Authors define the confidentially property as follows :

### **Definition 1 (Type 1: Secrecy).**&#x20;

A blockchain governance system satisfies secrecy if whenever a decision-making process is held, an adversary cannot guess the input of any participant better than an adversarial algorithm whose only inputs are the overall tally and, if the adversary is a participant, the adversary’s input. In Catalyst the authors assess this as mostly secret.

### **Definition 2 (Type 2: Pseudonymity).**&#x20;

A blockchain governance system satisfies pseudonymity if no participant is required to reveal their real-life identity to participate in the decision-making processes. In Catalyst Pseudonymity is assured by voter participation with a wallet address.

### **Definition 3.  Coercion-resistant.**&#x20;

A blockchain governance system is coercion-resistant if whenever a decision-making process is held, a  participant can deceive the adversary into thinking that they have behaved as instructed, when the participant has in fact made an input according to their own intentions. In Catalyst the authors assess the system as somewhat coercion resistant. The ballot itself cannot be decrypted by the voter – so there is nothing to coerce.

## B) Verifiability - Security properties

![](<../.gitbook/assets/2022-02-17 (6).png>)

The second property, verifiability complements the prior property of confidentiality by going in the opposite direction and making sure that any voting inputs can be independently verified from the voter to the tally.

### Definition 4 (End-to-End Verifiability).&#x20;

This property rests on **Definition 4 (End-to-End Verifiability).** A blockchain governance system is verifiable if whenever a decision-making process takes place, participants are able to verify their inputs were properly tallied and independent observers are able to verify that inputs from eligible participants were properly tallied.

In Catalyst the result or tally of the vote can be independently verified and a voter can verify they have voted a particular way as long as they retain the means to decrypt their vote.

Outside of voting, verifiability can also be seen to be relevant to the “proof of life” onboarding process of a funded proposer or the debate over whether identities of Community Advisors should be known. A balance always needs to be drawn here between incentives for contribution (being funded as a proposer or rewarded for CA work) and the security that Secrecy & Pseudonymity may provide to a contributor.

## C) Pareto Efficiency

### Background

![](<../.gitbook/assets/2022-02-17 (7).png>)

There is a lot packed into the Pareto efficiency section of the authors’ Blockchain properties. Reference is made to the background subject of “Social Choice Theory” which encompasses the study of all collective decision processes and procedures.

Concerns with how individual choices can be aggregated into collective outputs date at least as far back as the Enlightenment when Nicolas de Condorcet examined the effectiveness of majority voting and how irrational majority preferences may emerge.

The Authors refer specifically to Kenneth Arrow who published a paper, then a book Social Choice and Individual Values (1951) which laid the groundwork for modern social choice theory.

I will come back to Arrow shortly but now lets look at an example of Pareto efficiency in the context of Catalyst.

### Pareto efficiency

![](<../.gitbook/assets/2022-02-17 (8).png>)

Pareto efficiency asks that, given all stakeholders’ preferences, the outcome of the governance process cannot be strictly improved vis-\`a-vis these preferences.

In relation to Project Catalyst the authors suggest Pareto Efficiency is only somewhat satisfied. “For example, if the total fund is $200,000 and the three winning proposals have budget $10, $100,000 and $100,000 (in order of popularity) the last proposal will not receive funding.”

### Arrow’s Impossibility Theorem

![](<../.gitbook/assets/2022-02-17 (9).png>)

Returning to the background context.

Like Condorcet, Arrow was concerned with the difficulties of group decisions and the inconsistencies to which they may lead.

Arrow’s Impossibility Theorem showed that even mild conditions of reasonableness could not be satisfied by any social choice procedure that identifies a social ordering (or ranking) for each cluster of individual preferences.

Very briefly I will outline Arrow’s Impossibility Theorem only to give a hint of the foundation of modern social choice theory.

#### Arrow’s Impossibility Theorem

With three or more options, no ranked voting electoral system can convert the preferences of individuals into a community-wide (complete and transitive) ranking whilst also meeting the following set of criteria:

•Unrestricted domain (which means the universality of the ranking of preferences – that they will always be reproduced under the same conditions)

•Non-dictatorship (That no one voter dictates preferences or all other voters mimic one voter)

•Pareto efficiency (that there is unanimity of preferences, what any individual prefers is always reflected in the societal preference order).

•Independence of irrelevant alternatives (that a choice between A & B for example should not be affected by an alternative C).

## D) Accountability - Incentive properties

![](<../.gitbook/assets/2022-02-17 (10).png>)

The next property Accountability requires that all stakeholders are held accountable for the input they provide to the system.

### Definition 6. Accountability

A blockchain governance system satisfies the property of accountability if whenever participants bring in a change, they are held individually responsible for it in a clearly defined way by the platform.

The authors conclude that in respect of accountability in Catalyst there are no explicit, on or off-chain, penalties. They note that :

•Proposers need to submit periodic progress reports about their projects to keep receiving funding.•Similarly, community advisors and veteran community advisors can be penalized for poor reviews or absence.•But as these are either centralized or community-driven without clearly described mechanisms, accountability is mostly not satisfied.



## E) Sustainability - Incentive properties

![](<../.gitbook/assets/2022-02-17 (11).png>)

The Sustainability properties address the issue of whether appropriate incentives are provided for the system to evolve constructively and to the stakeholders for providing meaningful input.

### Definition 7 (Sustainable Development).&#x20;

A blockchain governance system sustains development if it incentivises, via monetary rewards or otherwise, participants who develop successful improvement proposals for the platform.

The authors conclude that sustainable development is satisfied in Catalyst through the funding process. Although there is no explicit incentive or reward given to the proposing group or individual, it is the responsibility of the proposer to request the amount which represents the value of their work.

I would suggest here that simply assuming the proposer will request the value of their work is an insufficient guarantee of their capability in budgeting and whether they are granted sufficient funds.

### Definition 8 (Sustainable Participation).&#x20;

A blockchain governance system sustains participation if it incentivises, via monetary rewards or otherwise, participants who participate in the decision-making process of the platform

The authors conclude that sustainable participation is satisfied in Catalyst as all parties are rewarded for participating in the governance process and to an extent receive larger rewards for additional effort (e.g. community advisors and review quality).

I would suggest here that not all parties have been rewarded for participation historically in Catalyst. Specifically the group dubbed Toolmakers & Maintainers who provide administrative, organizational and documentation services that are only intermittently rewarded through a completive funding process.



## F) Liveness

![](<../.gitbook/assets/2022-02-17 (12).png>)

The crucial ability of the system to produce outputs expediently is captured by Liveness property.

### Definition 9. liveness

A blockchain governance system satisfies liveness if it is capable of incorporating an input of urgency from the stakeholders and then being capable of acting on it in the sense that if an issue is deemed to be urgent according to\
some function, then the decision making procedure is capable of terminating within a reasonable amount of time, which is a function of the urgency of the matter.

The authors conclude that liveness is not satisfied as even though Catalyst funds can be released in accordance with a proposal’s progress, there is no direct mechanism to take urgent action for immediate release.

Whether liveness is required in Catalyst relates to debates over the timeliness of funds. This issue has been identified and has led to initiatives such as the Rapid Funding Mechanism Challenge and to emerging community treasuries and stakepool networks.

## G) Suffrage

![](<../.gitbook/assets/2022-02-17 (13).png>)

The final property concerns participation eligibility; Decision making systems can produce legitimate outcomes provided they are inclusive — a property that we capture by different aspects of Suffrage suitably adapted to the blockchain setting.

In the author’s assessment since voting eligibility depends on only having at least 500 ADA, token-based suffrage is satisfied.

There are no guaranteed voting rights based on previous positive contributions.

However, community advisors and veteran community advisors can affect the outcome of the votes through their reviews.

So the authors argue that meritocratic suffrage is slightly satisfied.

## Summary

![](<../.gitbook/assets/2022-02-17 (14).png>)

So to conclude here is a table of the Authors’ assessment of Governance properties in relation to Catalyst.

And I have added a column of my own assessments to the right.

I will leave it to you to consider your own assessment of these properties and how they are defined and framed.

## Thank You

![](<../.gitbook/assets/2022-02-17 (15).png>)

This presentation is funded by Project Catalyst in the form of the [Fund 7 Q](https://cardano.ideascale.com/c/idea/382334)[ADAO Ekphrasis ](https://cardano.ideascale.com/c/idea/382334)[GitBook](https://cardano.ideascale.com/c/idea/382334)[ proposal ](https://cardano.ideascale.com/c/idea/382334)which received a CA assessment score of 4.89 and was successfully voted for by 197 unique wallets last week.

Please consider delegating to [QADAO pool ](https://adapools.org/pool/e8fb1e898f1d3d9e219b784a080793d65153abf9dd0ab35a698cdcee)which is part of the [Ryuuki](https://twitter.com/RyuukiNetwork) Community Stakepool Network.

Also check out [General Properties of Blockchain Governance ](https://youtu.be/TKJDjwyAz4A)by [ADAO](https://www.theadadao.com) on their YouTube channel.

## Comments

19:33:19 From Tevo Saks : I will be taking notes on Miro Board after presentation: https://miro.com/app/board/uXjVOMES8sU=/&#x20;

19:34:17 From Tevo Saks : https://arxiv.org/pdf/2201.07188v2.pdf&#x20;

19:36:47 From Tevo Saks : Information System Management: https://slingerjansen.files.wordpress.com/2020/03/defining-blockchain-governance-a-framework-for-analysis-and-comparison.pdf&#x20;

19:43:17 From Tevo Saks : Social Choice Theory: https://plato.stanford.edu/entries/social-choice/&#x20;

19:43:32 From Heinz Gassner : Tevo, are these slides available ?&#x20;

19:43:41 From Heinz Gassner : I will need to leave soon&#x20;

19:44:13 From Tevo Saks : yes, if you doubleclick on the slide picture you get the link&#x20;

19:44:26 From Tevo Saks : But here is the link: https://docs.google.com/presentation/d/1kfKrqdZB8v4oN2WY\_nqDlGNB60s4u6iZjvpUKu5AQLU/edit&#x20;

19:44:53 From Heinz Gassner : @TEvo&#x20;

19:44:59 From Heinz Gassner : Thanks&#x20;

19:46:05 From Heinz Gassner : Very interesting, but need to leave …&#x20;

19:46:26 From Tevo Saks : iz ok, its recorded :D plan your time as you see fit&#x20;

19:46:37 From Tevo Saks : thx for joining&#x20;

19:48:56 From Jeremy B : late to the room, was there a link to the article Stephen is discussing?&#x20;

19:49:17 From Tevo Saks : https://miro.com/app/board/uXjVOMES8sU=/&#x20;

19:49:22 From Tevo Saks : you can find all the links here&#x20;

19:49:31 From Jeremy B : 👍&#x20;

19:49:34 From Tevo Saks : including the presentation

19:50:20 From Harris Warren : Thanks Stephen for such great coverage of this research. 🙏&#x20;

19:50:38 From Harris Warren : I need to run.&#x20;

19:51:05 From mike jarmon : Run well! Good stuff… Tx&#x20;

19:51:39 From Tevo Saks : Open Question: Should we do large scale survey related to assessing Catalyst Governance Properties?&#x20;

19:54:31 From Stephen Whitenstall : https://docs.google.com/presentation/d/1kfKrqdZB8v4oN2WY\_nqDlGNB60s4u6iZjvpUKu5AQLU/edit?usp=sharing&#x20;

19:55:27 From Dan Verowski : thanks for the pres Stephen and Tevo for facilitating. got to go, see u later (;&#x20;

19:57:13 From Stephen Whitenstall : Thanks Dan and Harris&#x20;

19:59:27 From Nick Smith : Thanks everyone. Gotta run to a 12 oclock meeting. Very interesting stuff, def going to dig in to this deeper.&#x20;

19:59:38 From Stephen Whitenstall : Thanks Nick&#x20;

20:07:17 From Sofi H : because of communication...&#x20;

20:07:44 From Sofi H : The message was shared upfront in TH to downvote&#x20;

20:20:28 From Tevo Saks : J P, all the info you might not need :D https://miro.com/app/board/uXjVOMES8sU=/&#x20;

20:20:38 From Özgür Yaşar Akyar : Thanks for the meeting. We are learning each day and excited to see where all this evolve… Warm greetings from Turkey. Lets build better system together&#x20;

20:20:54 From Tevo Saks : Turkey ftw&#x20;

20:25:54 From J P : Decentralized Consortium Fund&#x20;

20:26:06 From Curtis Myers : Tevo, I love your game wall! Off topic&#x20;

20:27:27 From Tevo Saks : you seen nothing yet :D its 6th of the games I guess.&#x20;

20:28:02 From Curtis Myers : Jealous, I have a good amount of games. But no one to play with, haha. I still have unopened boxes&#x20;

20:28:06 From Tevo Saks : I like play trough all kinds of game mechanics&#x20;

20:28:27 From Curtis Myers : Very valuable brain exercises IMO&#x20;

20:28:31 From Tevo Saks : some of the games are unopened too xD but yes finding players is not an easy task&#x20;

20:28:47 From Tevo Saks : harder than getting a volunteer group in Catalyst to do free work for community :D&#x20;

20:29:02 From Curtis Myers : hahaha 😂&#x20;

20:31:31 From Curtis Myers : Skepticism is a good approach to everything. As long as bias doesn't play a role. I have lots of faith in you Kenric!&#x20;

20:31:32 From Sofi H : I feel the same, bit unsure about the route, but also dont want to just judge from the sideline XD&#x20;

20:32:26 From J P : CoI&#x20;

20:32:47 From J P : d-rep&#x20;

20:33:21 From Tevo Saks : I speculate it will have positive impact, because we will see representatives, compared to unknown influencers influencing decision making&#x20;

20:33:49 From Tevo Saks : and we prolly gona analyze the decisions made by reps, because that's what we do, we analyze everything :D&#x20;

20:34:18 From Tevo Saks : which will lead to the liquid democracy research we need&#x20;

20:34:37 From Curtis Myers : Good view point Tevo. Right now is not optimal. But clarity can still be provide a negative impact, however I think this is progress regardless&#x20;

20:35:25 From Quasarito Salads : would like to explore governance through the lens of actor network theory and removing voting altogether&#x20;

20:36:44 From J P : It seems like one would delegate their voting power to another person&#x20;

20:36:46 From Quasarito Salads : or represent the wen Lambos!!!!!!!! LFG&#x20;

20:38:12 From Quasarito Salads : or, stop voting&#x20;

20:38:40 From Quasarito Salads : voting is a wolf in sheeps pants&#x20;

20:39:43 From Quasarito Salads : Here's voting and compromise for you&#x20;

20:39:45 From Quasarito Salads : https://en.wikipedia.org/wiki/Three-fifths\_Compromise&#x20;

20:41:56 From Quasarito Salads : let's get voting off the pedestal&#x20;

20:42:25 From Quasarito Salads : that's actor network theory, thank you Sofih&#x20;

20:44:20 From Quasarito Salads : Voting power is not power, it's a means of control.&#x20;

20:45:32 From Quasarito Salads : https://docs.google.com/document/d/1Z2qLzGbLQxLgfDKqnTZFTL3IM28V8uUykptng0p5jbE/edit&#x20;

20:46:21 From J P : Sorry all, I must drop off. Thanks for the discussion&#x20;

20:46:24 From Quasarito Salads : voting power and paying whales voter rewards is a framework of the repressive state apparatus.&#x20;

20:46:29 From Stephen Whitenstall : Thanks JP&#x20;

20:47:35 From Quasarito Salads : what's the percentage of wallets below 10K ada? percentage over 1M ada?&#x20;

20:48:28 From Quasarito Salads : but the voting rewards are reduced so that's a silver lining&#x20;

20:49:03 From Quasarito Salads : on a zoom call with google forms? why not? isn't this the zoom governance room?&#x20;

20:49:53 From Tevo Saks : session is kinda over, but Miro notes for new people: https://miro.com/app/board/uXjVOMES8sU=/&#x20;

20:50:11 From Jonathan Adjei : Tx&#x20;

20:50:21 From Stephen Whitenstall : Like Arrows Impossibility Theorem&#x20;

20:50:39 From Quasarito Salads : correct, different voting for different things, pick your governance, assigned the system/method&#x20;

20:50:52 From Stephen Whitenstall : But ranking systems are not the only option&#x20;

20:51:46 From Stephen Whitenstall : or meritocratic suffrage&#x20;

20:52:04 From Quasarito Salads : these intangibles love pontifications&#x20;

20:54:13 From Stephen Whitenstall : https://vitalik.ca/general/2017/12/17/voting.html&#x20;

20:54:34 From Quasarito Salads : the crowd always prevails, and slips&#x20;

20:54:38 From Quasarito Salads : splits&#x20;

20:54:46 From Sofi H : https://www.youtube.com/watch?v=sJcqNEyTUwg&#x20;

20:55:05 From Stephen Whitenstall : Link to presentation for latecomers - https://docs.google.com/presentation/d/1kfKrqdZB8v4oN2WY\_nqDlGNB60s4u6iZjvpUKu5AQLU/edit?usp=sharing&#x20;

20:55:20 From Sofi H : A brief version of why there is no one voting system to rule them all&#x20;

21:00:16 From Tevo Saks : well I got distracted, so I stopped taking notes when voting discussions started. I'm danzo for day&#x20;

21:03:17 From John Wellesz : Will we still have the option to vote directly for a proposal while delegating for other proposals we abstain?&#x20;

21:04:05 From Jonathan Adjei : @John .. I asked Harris earlier and he said yes You can choose how much of your voting weight to delegate,&#x20;

21:04:18 From Daniel Ribar : Yes, that is right.&#x20;

21:04:25 From Tomi Astikainen : I could delegate about 20 kg.&#x20;

21:04:26 From Kenric Nelson : @John interesting question; I assume the delegation is of your “coins”; and thus all the voting of those coins&#x20;

21:04:41 From Tevo Saks : 😅&#x20;

21:04:47 From Daniel Ribar : You will be able to split it - it’s not zero sum game like today all or no voting power.&#x20;

21:04:50 From Kenric Nelson : @JA, but not per proposal&#x20;

21:05:09 From Jonathan Adjei : Right ... yes&#x20;

21:05:47 From John Wellesz : I mean that I delegated 100% of my coins to a set of dreps I trust but I really want to vote yes or no to a particular proposal while still delegating for all the others proposal for which I trust my dReps&#x20;

21:06:22 From Kenric Nelson : Given that you’ll have public representatives; the hardest problem of identity is solved. So will options of saturated voting power and or quadratic voting be considered?&#x20;

21:08:22 From Kenric Nelson : Another side of Sofi’s point is that with the treasury growing, there may be more of a need to have multiple programs rather than one program&#x20;

21:17:15 From Nori Nishigaya : The Catalyst Circle writing proposals to fund them so they can write more proposals to them you is kind of silly. Granted, its not 100% of their time, but it’s not a trivial amount either.
