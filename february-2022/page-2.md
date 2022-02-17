---
description: Blockchain Governance Principles
---

# Blockchain Governance Principles

## Recording Placeholder

#### Recording Placeholder



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

## Security properties: A) Confidentiality

![](<../.gitbook/assets/2022-02-17 (5).png>)

The first Blockchain Governance property has to do with the confidentiality of stakeholder involvement. How participation in governance is secured and verified.&#x20;

The Authors define the confidentially property as follows :

### **Definition 1 (Type 1: Secrecy).**&#x20;

A blockchain governance system satisfies secrecy if whenever a decision-making process is held, an adversary cannot guess the input of any participant better than an adversarial algorithm whose only inputs are the overall tally and, if the adversary is a participant, the adversary’s input. In Catalyst the authors assess this as mostly secret.

### **Definition 2 (Type 2: Pseudonymity).**&#x20;

A blockchain governance system satisfies pseudonymity if no participant is required to reveal their real-life identity to participate in the decision-making processes. In Catalyst Pseudonymity is assured by voter participation with a wallet address.

### **Definition 3.  Coercion-resistant.**&#x20;

A blockchain governance system is coercion-resistant if whenever a decision-making process is held, a  participant can deceive the adversary into thinking that they have behaved as instructed, when the participant has in fact made an input according to their own intentions. In Catalyst the authors assess the system as somewhat coercion resistant. The ballot itself cannot be decrypted by the voter – so there is nothing to coerce.

## Security properties: B) Verifiability

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
