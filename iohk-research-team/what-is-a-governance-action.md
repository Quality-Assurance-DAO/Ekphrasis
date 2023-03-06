# What is a Governance Action ?



## “An On-Chain Decentralised Governance Mechanism for Voltaire”

Input-Output Global has drafted a Cardano Improvement Proposal, CIP 1694, that outlines “An On-Chain Decentralised Governance Mechanism for Voltaire”. This presentation by QADAO focuses on Governance Actions.

## What is a Governance Action ?

A governance action is a blockchain parameter (“on-chain event”) triggered by a time-limited transaction (“has a deadline after which it cannot be enacted”).

## Ratifying an action

A governance action is ratified once it has gathered enough votes to support it. If it fails to gather sufficient yes votes before its deadline the action expires. Or any action may be dropped subsequent to a motion of no confidence. Once ratified an action is said to be “enacted”.

## Types of governance actions.

1. A motion of no-confidence - is a motion to create a state of no-confidence in the current Constitutional Committee
2. New Constitutional Committee and/or quorum size - Changes to the members of the Constitutional Committee and/or to its signature threshold.
3. Updates to the Constitution - these are modifications to the off-chain Constitution, recorded as an on-chain hash of the text document.
4. Hard-Fork Initiation - this triggers a non-backwards compatible upgrade of the network and requires a prior software upgrade.
5. Protocol Parameter Changes - that is, changes to one or more updatable protocol parameters, excluding changes to hard forks.
6. Treasury Withdrawals - these are movements from the treasury, sub-categorized into small, medium or large withdrawals.

## Plutocratic voting for governance actions.&#x20;

A motion of no confidence can be voted for by D Reps' and SPOs.&#x20;

A new committee or quorum in a normal state can be voted for by the constitutional committee, D Reps and SPOs.

A new committee or quorum in a state of no confidence can only be voted for by the D Reps and SPOs.

An update to the constitution can be voted for by the constitutional committee, D Reps and SPOs.&#x20;

A hard fork initiation can be voted for by the constitutional committee, D Reps and SPOs.

Protocol parameter changes can be voted for by the constitutional committee, D Reps and SPOs.&#x20;

Treasury withdrawals can be voted for by the constitutional committee, D Reps and SPOs.

## Active Voting Stake Thresholds (AVST)

The Active Voting Stake Thresholds (AVST) is the percentage to be used to determine if there is a sufficient active voting stake. This parameter represents the minimum amount of Ada deposit needed to enact a governance action.

## AVST Fallbacks

AVST Fallbacks operate in the following way. In constitutional committee no-confidence motions or states there is no AVST fallback. Instead both the d reps' and SPOs vote.

Hard fork initiations have no AVST fallback. In this situation the constitutional committee, d reps' and SPOs all vote.

Normal motions of no confidence, updates to the constitution, protocol parameter changes and treasury withdrawals all have an AVST fallback where SPOs vote.

## Governance Action Lifecycle

The Cardano blockchain splits time into periods called epochs. One epoch lasts approximately 5 days.&#x20;

Governance actions are ratified and staged for enactment only on an epoch boundary.

An action may be dropped as a result of some higher priority action. Governance actions will expire after a set number of epochs.&#x20;

Staged actions will be enacted on the following epoch boundary.
