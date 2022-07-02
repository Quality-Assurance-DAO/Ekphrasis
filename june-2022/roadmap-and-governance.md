---
description: Charles Hoskinson on the Cardano Roadmap and Governance. 30th June 2022
---

# Roadmap and Governance

{% embed url="https://youtu.be/MwP-omMwd3A" %}

{% hint style="info" %}
This is a summary with inserted explanations and references.\
Transcriptions are funded by [QA-DAO Transcription Service](https://cardano.ideascale.com/c/idea/383492).
{% endhint %}

## Beginning

[00:11](https://youtu.be/MwP-omMwd3A?t=11)

Lots of stuff going on in the markets reflecting the macro \[macro economic conditions]. Bear markets are good for building. Time for getting things done

## Vasil

[00:57](https://youtu.be/MwP-omMwd3A?t=57)

Vasil \[Hard Fork] is under way we forked the test net. As of July 3rd the test net will be running Version 1.35 which will run until the end of July 2022. Input Endorsers \[The core idea of input endorsers is to separate transaction selection from block production]

## What next ?

[01:46](https://youtu.be/MwP-omMwd3A?t=106)

There are four tracks running concurrently.

### The Shelley Clean-up

01:47

{% hint style="info" %}
[https://roadmap.cardano.org/en/shelley/](https://roadmap.cardano.org/en/shelley/)
{% endhint %}

Partial delegation, Proxy keys, Peer to peer and Genesis.

### Goguen

[02:17](https://youtu.be/MwP-omMwd3A?t=137)

{% hint style="info" %}
[https://roadmap.cardano.org/en/goguen/](https://roadmap.cardano.org/en/goguen/)
{% endhint %}

Vasil is the first Goguen clean-up hard fork. Better [PAB ](https://plutus-apps.readthedocs.io/en/latest/plutus/explanations/pab.html)\[Plutus Application Backend] documentation. Optimizations of the language.

### Basho

[02:54](https://youtu.be/MwP-omMwd3A?t=174)

{% hint style="info" %}
[https://roadmap.cardano.org/en/basho/](https://roadmap.cardano.org/en/basho/)
{% endhint %}

Sidechains. Paper coming out August 2022 explain how we upgrade OPST to do quorum sampling.

[Mithril ](https://iohk.io/en/blog/posts/2021/10/29/mithril-a-stronger-and-lighter-blockchain-for-better-efficiency/)\[protocol acts as a stake-based threshold signature scheme allowing for transparent, secure, and lightweight stake leveraging]. Is under construction with a two week release cadence.

[Input Endorsers ](https://cardano.stackexchange.com/questions/4626/what-are-input-endorsers-and-how-do-they-make-cardano-more-scalable)\["The core idea of input endorsers is to separate transaction selection from block production."]. Work in summer on Input Endorsers official specification will rely heavily on Mithril and it's UTXO \[[Unspent Transaction Output](https://docs.cardano.org/plutus/eutxo-explainer)].

### Scalability and interoperability

[03:46](https://youtu.be/MwP-omMwd3A?t=226)

These three things together, along with the work we are doing on [Hydra](https://iohk.io/en/blog/posts/2021/09/17/hydra-cardano-s-solution-for-ultimate-scalability/). Is a starting point for true scalability and interoperability. The sidechain idea of Mithril is really the foundation of interoperability. Hydra is really a dApp accelerator. And backfills in the micro transactions use case. Input Endorsers gets rid of any consensus bottlenecks in the system. Everything is network constrained - so super high TPS \[Transactions per second].

## Voltaire

[04:39](https://youtu.be/MwP-omMwd3A?t=279)

Voltaire is interesting. We have a lot of programs like [Catalyst ](https://cardano.ideascale.com/a/index)where there is just about to be a massive surge in voting. There is going to be the voting center, [dReps ](https://iohk.io/en/blog/posts/2022/04/11/introducing-the-concept-of-delegate-representatives-dreps/)and how to link Catalyst to mainnet (so it overlaps with some of the Basho agenda). Right now its running as a permissioned sidechain.

### Protocol governance

[05:37](https://youtu.be/MwP-omMwd3A?t=337)

The question of protocol governance and the bureaucracy behind updates. Things like - initiation of the [hard fork combinator](https://docs.cardano.org/core-concepts/about-hard-forks) , changes to parameters, the [CIP ](https://cips.cardano.org/)(Cardano Improvement Proposals) process, Treasury Management.

### Tripartite Governance Structure

[06:14](https://youtu.be/MwP-omMwd3A?t=375)

When Cardano was started the original intent was three entities -

**Cardano Foundation** (CF) - would take care of governance

**Emurgo** - would take care of ecosystem growth

**IOHK** - would take care of technical

There has been lots of back and forth. The CF (Cardano Foundation) of the Michael Parsons era was challenging ([Michael Parsons era](roadmap-and-governance.md#michael-parsons-era)). We can litigate the past and talk about these things, but the long and short of it \[_idiom - to sum up_] is that \[governance] structure has not been perfect.

### Members based organization

[06:48](https://youtu.be/MwP-omMwd3A?t=408)

The particular thing I wanted to see built over the past few years was a members-based organization. That would run the bureaucracy of protocol governance. This was my hope for the CF (Cardano Foundation) but the system & structure in Switzerland is not good for that.

Earlier this year we had a long conversation with CF (Cardano Foundation) in a series of workshops. This asked the question - "How do we move the bureaucracy \[of protocol governance] from the Tripartite Governance Structure, which was always ephemeral \[temporary] to a members based organisation ?".

Members are defined by merit.

### Dirk Hohndel, Chief Open Source Officer

[07:36](https://youtu.be/MwP-omMwd3A?t=457)

The CF (Cardano Foundation) hired [Dirk Hohndel](https://cardanofoundation.org/en/news/dirk-hohndel-joins-cardano-foundation-as-chief-open-source-officer/) who is a legend in the open source software community. He is co-founder of the [Linux Foundation](https://www.linuxfoundation.org/)

### Steering committees

There are about 50 people from the CF (Cardano Foundation) & IO (Input Output Global) who have been working since February 2022 on the construction of this members based organization.

There will be an announcement about the specific structure of the members based organization in September 2022.

This organization will have -

* A governance steering committee (GSC).
* A technical steering committe (TSC).
* Other committees - related to growth and adoption.
* A CIP (Cardano Improvement Process) committee.

These committees will make decisions about the [Roadmap](https://roadmap.cardano.org/en/), suggestions for [CIPs ](roadmap-and-governance.md#cardanoimprovementproposalscips)(Cardano Improvement Process), strategy and other things.

### Bicameral Model

[08:57](https://youtu.be/MwP-omMwd3A?t=537)

To allow for people to consent to this we want to move to a Bicameral Model \[[Bicameralism](https://en.wikipedia.org/wiki/Bicameralism)]. The Bicameral Model says that the bureaucracy proposes and the ADA holder votes.

After the [Vasil ](roadmap-and-governance.md#vasil)hard fork, the next hard fork combinator will be a special type of update proposal (written to the [CIP ](roadmap-and-governance.md#cardanoimprovementproposalscips)standard) that will go to ADA holders to vote on. And then it gets signed by the [CIP ](roadmap-and-governance.md#cardanoimprovementproposalscips)committee.

The update keys \[[update keys](roadmap-and-governance.md#update-keys)] were connected to the three entities of the [Tripartite Governance Structure](roadmap-and-governance.md#tripartite-governance-structure)  (Cardano Foundation, emurgo and IOHK).

The intent was always to create a decentralized update system. We wrote a paper \[Source ?] with a European Union Horizon 2020 grant to explore how to do that. And there is a lot of technical complexity in it.

A nice halfway house \[compromise] is to have a CIP committee that controls an M of N set of keys that they cannot sign without approval from ADA holders. They write an update proposal and take it to the ADA holders. The ADA holder approve it and then the CIP committee can sign the proposals.

### You pay or you work

[10:31](https://youtu.be/MwP-omMwd3A?t=631)

What do we mean by a merit based members organization ? Merit and Members organization.&#x20;

Well either you pay or you work. Either you do something or you contribute some funding.

Pretty simple and easy to understand.

You have to allow a set of people in the ecosystem to grow and evolve to a point where they are capable of participating.

That is effectively what the dReps (Delegated Representatives), SPOs (Stakepool operators) and the dApp developers are. Alongside people who take a community role. So we have the Ambassador program, 1000 plus dApps projects, 3000 Stake Pool Operators and a large corps of dReps are forming.

These are not pairwise disjoint sets \[mathematical analogy - see [pairwise disjoint sets](roadmap-and-governance.md#pairwise-disjoint-sets)] , there is an overlap, and that is a good thing.

## References

### The Cardano Roadmap

{% embed url="https://roadmap.cardano.org/en/" %}

### Vasil upgrade - the state of play

June 20th 2022

{% embed url="https://iohk.io/en/blog/posts/2022/06/20/vasil-upgrade-the-state-of-play/" %}

### What is the PAB?

_Plutus Application Backend_

{% embed url="https://plutus-apps.readthedocs.io/en/latest/plutus/explanations/pab.html" %}

### Mithril: a stronger and lighter blockchain for better efficiency

{% embed url="https://iohk.io/en/blog/posts/2021/10/29/mithril-a-stronger-and-lighter-blockchain-for-better-efficiency/" %}

### Ouroboros: A Provably Secure Proof-of-Stake Blockchain Protocol

See - 8.1 Input Endorsers

{% embed url="https://eprint.iacr.org/2016/889.pdf" %}

### What are input endorsers and how do they make Cardano more scalable?

{% embed url="https://cardano.stackexchange.com/questions/4626/what-are-input-endorsers-and-how-do-they-make-cardano-more-scalable" %}

### Sidechains explained: Cardano's answer to scalability and interoperability

{% embed url="https://youtu.be/BoywCpnv8uk" %}

### Hydra – Cardano’s solution for ultimate Layer 2 scalability

{% embed url="https://iohk.io/en/blog/posts/2021/09/17/hydra-cardano-s-solution-for-ultimate-scalability/" %}

### Introducing the Concept of Delegate Representatives (dReps)

{% embed url="https://iohk.io/en/blog/posts/2022/04/11/introducing-the-concept-of-delegate-representatives-dreps/" %}

### About hard forks

{% embed url="https://docs.cardano.org/core-concepts/about-hard-forks" %}

### Cardano Improvement Proposals <a href="#cardanoimprovementproposalscips" id="cardanoimprovementproposalscips"></a>

{% embed url="https://cips.cardano.org/" %}

### Michael Parsons era

#### Cardano Leaders Split With Foundation, Demand Chairman Resigns

Oct. 12, 2018

{% embed url="https://cryptobriefing.com/cardano-leaders-split-with-foundation-demand-chairman-resigns/" %}

![https://twitter.com/CardanoStiftung/status/1062384674390073345?s=20\&t=3metSqbeK9bLEO3AS16PyA](<../.gitbook/assets/Screenshot 2022-07-02 141600.png>)

### Dirk Hohndel, Chief Open Source Officer

#### Dirk Hohndel Joins Cardano Foundation as Chief Open Source Officer

{% embed url="https://cardanofoundation.org/en/news/dirk-hohndel-joins-cardano-foundation-as-chief-open-source-officer/" %}

### Linux Foundation

{% embed url="https://www.linuxfoundation.org/" %}

### Bicameralism

{% embed url="https://en.wikipedia.org/wiki/Bicameralism" %}

### Update keys&#x20;

#### Cardano Treasury with Kevin Hammond - A Catalyst Town Hall Presentation on the Cardano Treasury with an After Town Hall Q\&A

{% embed url="https://quality-assurance-dao.gitbook.io/community-governance-oversight/parameters/governance-parameters/cardano-treasury-with-kevin-hammond#who-is-making-the-governance-decisions" %}

### Pairwise disjoint sets

**Disjoint sets** are those sets whose intersection with each other results in a null set.

A collection of sets is pairwise disjoint if any two sets in the collection are disjoint. It is also known as mutually disjoint sets.

Let P be the set of any collection of sets and A and B.

i.e. A, B ∈ P. Then, P is known as pairwise disjoint if and only if A ≠ B. Therefore, A ∩ B = ϕ

**Examples:**

* P = { {1}, {2, 3}, {4, 5, 6} } is a pairwise disjoint set.
* P = { {1, 2}, {2, 3} } is not pairwise disjoint, since we have 2 as the common element in two sets.
