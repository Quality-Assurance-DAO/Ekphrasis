---
description: Charles Hoskinson on the Cardano Roadmap and Governance. 30th June 2022
---

# Roadmap and Governance

{% embed url="https://youtu.be/MwP-omMwd3A" %}

{% hint style="info" %}
This is a summary with inserted explanations, timestamps and references.\
The english is simplified in places to ease translation.\
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

If you look at that set \[of people in the ecosystem] that is a very large group of people. Okay, take the next step, join a members based organization, there is going to be governance committees, technical steering committees, growth and adoption committees. And actually get involved in the governance process.

### How will you run effective committees?

[12:00](https://youtu.be/MwP-omMwd3A?t=720)

\[Our model will be] the work Dirk Hohndel did at the [Linux Foundation](https://www.linuxfoundation.org/) which runs over 140 plus projects from [Kubernetes](https://kubernetes.io/), to [Node ](https://nodejs.org/en/)to cryptocurrency projects like Fabric, the entire [Hyperledger ](https://www.hyperledger.org/)group, even an Ethereum node called [Besu](https://besu.hyperledger.org/en/stable/). So there is a lot of decentralization there. And there is a lot of organizational wisdom in these types of models. And that is basically what we're pursuing.

In September 2022 we will have the first setup. Between now and September in July and August 2022 we are going to set up a website for signups.&#x20;

And then either you pay the membership fee to the \[member] organization, or you contribute some sort of work or both.&#x20;

### More people working for Cardano

[13:00](https://youtu.be/MwP-omMwd3A?t=780)

Another side is we need to get more people working for Cardano.

You may have noticed that [Sebastien Guillemot](https://www.sebastiengllmt.com/) from [dcSpark ](https://www.dcspark.io/)is now a CIP editor, and his role is covered completely by the Cardano blockchain itself. \[See Fund 8 Catalyst proposal - [CIP Editor time Sebastien for 1year](https://cardano.ideascale.com/c/idea/400716)]

I told [Harris Warren](https://iohk.io/en/team/harris-warren) at Project Catalyst that I would like to see three to five more community members become CIP editors paid for completely by the Cardano Blockchain \[Catalyst Treasury].

I'd also like to see 10 to 15 full time engineers working directly for Cardano, paid for by Cardano. This will be a big part of Catalyst Fund 10.

It is time to get a complete group of people that work for Cardano. That is the entire point of the system. With this members based organization it is pretty easy to do that because the members can be directly funded from Project Catalysts after \[the new Challenge] has started. \


It is good to have individuals in addition to companies working for Cardano. It creates checks and balances. So if you have the technical abilities to write code or the ability to read scripts then you can be part of that process. Jobs are opening up. Coming very soon before the end of the year.&#x20;

I guess what I'm trying to convey is that it is a lot of cleanup.

### Major inflection point

[14:47](https://youtu.be/MwP-omMwd3A?t=887)

It has gotten to the juncture \[to the point] where we are about to have a major inflection point \[change] where this structure \[the [Tripartite Governance Structure](roadmap-and-governance.md#tripartite-governance-structure)] is gone.

There has been an enormous amount of learning along the way. I would have done things very differently if I got to do the project again. But, to be fair, we had to live through seven years of history. And, we had to go through a lot of events to get to this point.&#x20;

The fact that we are now about to see the existence of a massive members based organization, that is going to provide proper representation of the community for roadmap, strategy etc. and has a consent component from voting is pretty exciting to me.&#x20;

A lot of good people are working on this, and I can't wait to make the announcement September 2022. I will be at some event for that. I cannot say anything about it right now. I have signed a mutual NDA (non disclosure agreement) with the Cardano Foundation.

### House cleaning

[15:57](https://youtu.be/MwP-omMwd3A?t=957)

Some house cleaning is needed in terms of the update committee and that has always been the case. And the proxy keys (see [update keys](roadmap-and-governance.md#update-keys)) and partial delegation and so forth.&#x20;

We still are number one for GitHub commits as an ecosystem. The push out \[rollout] of the Vasil Hard Fork even though it is complicated has been pretty seamless.&#x20;

The reality is that Cardano is not controlled by a person, an entity or a collection of entities. It truly is one of the most decentralized of all cryptocurrencies because it has this gigantic super smart community that is working towards an end.&#x20;

Some legacy has to be removed and cleaned up, some training wheels have to be clipped off. Sometimes it takes a little longer than you think. But there is an intent to do it.

### The Edinburgh decentralization index

[17:00](https://youtu.be/MwP-omMwd3A?t=1021)

We need a North Star. So what is our North Star, our guiding light, behind these types of things? Well, the North Star is this concept of decentralization. That is one of them. There are many North stars. But decentralization is the big one that I think we can tackle this year.&#x20;

So we are setting up something called the **Edinburgh decentralization index (EDI)**, it's going to be based at University of Edinburgh ([Blockchain Technology Laboratory network](https://www.ed.ac.uk/informatics/blockchain) & [IOHK Research Library](https://iohk.io/en/research/library/)). And obviously, it's going to measure decentralization of cryptocurrencies.

\[In this GitBook see also [How to Measure Decentralisation?](../july-2021/how-to-measure-decentralisation.md)]

Throughout the summer, papers are going to be written, a lab is going to be set up governed by the University of Edinburgh. And the team at the lab is going to start with [Bitcoin](https://bitcoin.org/en/), then [Ethereum ](https://ethereum.org/en/)and then move on to Cardano.&#x20;

They will keep going and create a decentralization index and we do not know where we are going to fall on this index.

Some of \[the decentralization score] might be great, some of it may not be so great. It will be aggregated together and we will get a score.

&#x20;Then the [government steering committee](roadmap-and-governance.md#steering-committees) of the open source program \[[members based organisation](roadmap-and-governance.md#members-based-organization)] can make an agenda and strategy of how do we improve \[the decentralization score].&#x20;

You have to have a collection of North Stars, a constellation of stars, that allow you to steer the project in a particular direction. Some of that is decentralization, some of that is resilience, some of that is effectiveness and cost, some of that is use and utility.&#x20;

### Roadmap and Smart Contracts

We did our best with the initial Cardano roadmap to try to balance all of these different types of concerns.

It did not make everybody happy all the time. For example, being slow to market with smart contracts meant that Cardano missed a lot of the [defi ](https://www.investopedia.com/decentralized-finance-defi-5113835)stuff that is happening today.

And in 2021, people thought we were horrible and idiots. Now \[being slow to market] seems to actually be a benefit as the defi markets come collapsing down and exponential losses are occurring.&#x20;

We did not play in those waters. And so we did not get bitten by those sharks. But that was out of an abundance of caution and we could have had smart contracts in the ecosystem a little earlier.

But there would not have been as much careful thought put into the development model. And we would also be suffering from the many hacks, protocol design flaws and other problems that the cryptocurrency ecosystem is now working its way through. And \[these problems] may actually several major cryptocurrencies. It has already destroyed [Luna ](https://www.terra.money/)and it's destroyed [Celsius ](https://celsius.network/)and more to come as exponential risk continues to scale. So roadmaps are hard.

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

### Blockchain Technology Laboratory network (Edinburgh University)

{% embed url="https://www.ed.ac.uk/informatics/blockchain" %}

### IOHK Research Library

{% embed url="https://iohk.io/en/research/library/" %}
