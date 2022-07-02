---
description: Charles Hoskinson on the Cardano Roadmap and Governance. 30th June 2022
---

# Roadmap and Governance

{% embed url="https://youtu.be/MwP-omMwd3A" %}

{% hint style="info" %}
This is a summary with inserted explanations and references.
{% endhint %}

## Beginning

[00:11](https://youtu.be/MwP-omMwd3A?t=11)

Lots of stuff going on in the markets reflecting the macro \[macro economic conditions]. Bear markets are good for building. Time for getting things done

## Vasil&#x20;

[00:57](https://youtu.be/MwP-omMwd3A?t=57)&#x20;

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

&#x20;[Mithril ](https://iohk.io/en/blog/posts/2021/10/29/mithril-a-stronger-and-lighter-blockchain-for-better-efficiency/)\[protocol acts as a stake-based threshold signature scheme allowing for transparent, secure, and lightweight stake leveraging]. Is under construction with a two week release cadence.

&#x20;[Input Endorsers ](https://cardano.stackexchange.com/questions/4626/what-are-input-endorsers-and-how-do-they-make-cardano-more-scalable)\["The core idea of input endorsers is to separate transaction selection from block production."]. Work in summer on Input Endorsers official specification will rely heavily on Mithril and it's UTXO \[[Unspent Transaction Output](https://docs.cardano.org/plutus/eutxo-explainer)].

### Scalability and interoperability

[03:46](https://youtu.be/MwP-omMwd3A?t=226)

These three things together, along with the work we are doing on [Hydra](https://iohk.io/en/blog/posts/2021/09/17/hydra-cardano-s-solution-for-ultimate-scalability/). Is a starting point for true scalability and interoperability. The sidechain idea of Mithril is really the foundation of interoperability. Hydra is really a dApp accelerator. And backfills in the micro transactions use case. Input Endorsers gets rid of any consensus bottlenecks in the system. Everything is network constrained - so super high TPS \[Transaction per second].

### Voltaire

[04:39](https://youtu.be/MwP-omMwd3A?t=279)

Voltaire is interesting. We have a lot of programs like [Catalyst ](https://cardano.ideascale.com/a/index)where there is just about to be a massive surge in voting. There is going to be the voting center, [dReps ](https://iohk.io/en/blog/posts/2022/04/11/introducing-the-concept-of-delegate-representatives-dreps/)and how to link Catalyst to mainnet (so it overlaps with some of the Basho agenda). Right now its running as a permissioned sidechain.

### &#x20;Protocol governance

[05:37](https://youtu.be/MwP-omMwd3A?t=337)

The question of protocol governance and the bureaucracy behind updates. Things like - initiation of the [hard fork combinator](https://docs.cardano.org/core-concepts/about-hard-forks) , changes to parameters, the [CIP ](https://cips.cardano.org/)(Cardano Improvement Proposals) process, Treasury Management.

### Tripartite Governance Structure

[06:14](https://youtu.be/MwP-omMwd3A?t=375)

When Cardano was started the original intent was three entities -

**Cardano Foundation** (CF) - would take of governance

**Emurgo** - would take care of ecosystem growth

**IOHK** - would take care of technical&#x20;

There has been lots of back and forth. The CF (Cardano Foundation) of the Michael Parsons era&#x20;

![https://twitter.com/CardanoStiftung/status/1062384674390073345?s=20\&t=3metSqbeK9bLEO3AS16PyA](<../.gitbook/assets/Screenshot 2022-07-02 141600.png>)













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
