---
title: "Tezos"
date: 2019-09-11T20:42:21+01:00
lastmod: 2019-09-11T20:42:21+01:00
draft: false
description: ""
weight: 270
---
![](/tezos.jpg)

### Baking Consensus

Tezos uses Delegated Proof of Stake (DPoS) consensus, but does not put a cap on the number of BPs ("bakers") - they refer to this as [liquid proof of stake](https://medium.com/tezos/liquid-proof-of-stake-aec2f7ef1da7). In principle the maximum number of bakers can be quite large, it is determined by the minimum "roll size", but bakers that control more XTZ (Tezos' native currency) will bake more blocks and have a more reliable income.

Tezos is built around a process for amending the protocol (rules of the network) in which bakers vote over a series of phases to select, test and apply a set of changes to the protocol. Baking nodes all follow the outcomes of these votes to decide which version of the protocol they should run, in what has been described as a self-amending protocol. On Aug 29 Tezos [launched](https://medium.com/@tezosagora/enter-agora-c9e545ce4862) its [Agora](https://www.tezosagora.org/) platform, which tracks the outcomes of current and past protocol change cycles so that stakeholders can follow this. Agora also links to a forum post for each proposal where it can be discussed, this is a new feature and (writing in Sep 2019 so far none of the proposals have significant discussion.

For Tezos the constituency of bakers (there are currently around 240 bakers per cycle, number taken from this [chart](https://tzscan.io/charts_bakers) at cycle 140) is charged with producing new blocks and also with deciding what the rules of the network are. Holders of XTZ can delegate their stake to a baker of their choosing and bakers typically share a portion of the rewards they receive back to the delegators, less a [fee](https://mytezosbaker.com/) of ~5-33%. Holders who delegate their XTZ have no formal role to play in the network, bakers are the key actors who produce new blocks and make decisions about consensus rules. If a holder has enough XTZ for at least one roll, they can participate in baking directly (but would expect to be selected to bake and receive rewards sporadically).

Delegation allows a high proportion of XTZ to participate in the PoS system. On 05/21/19 there was 447.5 million XTZ delegated of a total 564.5 million XTZ staked - around 85% of XTZ participates in baking and 79% of that is delegated. Holders of XTZ can indirectly influence the governance of the chain by choosing which bakers to empower with their delegation, but it remains to be seen how actively holders will use this power and to what extent their decisions will be based on the pursuit of rewards. Delegation allows one to generate returns passively, and it is possible some delegators will pay little attention to their baker as long as the rewards keep coming.

Within the bakers constituency there are rules about baking and mechanisms for [enforcement](https://medium.com/@Tezzigator/tezos-baking-your-bonds-their-risks-78d90d47296). Bakers are not allowed to double bake (bake on two forks of the Tezos chain) or endorse blocks on two chains. If they are caught doing so they forfeit their security deposit, with 50% of this going to the baker who accused them of breaking the rules. These rules are intended to solve the "nothing at stake" problem which could prevent a PoS system from converging around a single chain.

### Development Funding

The Tezos [Foundation](https://tezos.foundation/) controls the proceeds of the Tezos ICO (worth [approximately](https://cointelegraph.com/news/the-history-of-tezos-the-infamous-ico-trying-to-rebound-amidst-lawsuits-and-disputes) $232 million at the time) and 10% of the initial XTZ tokens, and has a mandate to use these to give "support to Tezos and related technologies as well as to the Tezos community". 

Bakers and holders have no say in how these ICO funds are used. The initial supply was composed of 607 million XTZ for ICO funders and 76 million XTZ for each of the Tezos Foundation and Dynamic Ledger Solutions (DLS) - for a total initial supply of 763 million XTZ. DLS is a company [created](https://cointelegraph.com/news/the-history-of-tezos-the-infamous-ico-trying-to-rebound-amidst-lawsuits-and-disputes) by Arthur Breitman in 2015 to hold the rights to Tezos software, and contracted by the Tezos Foundation following the ICO to relinquish those rights and associated IP. Stakes in DLS were sold to early investors to raise funds for Tezos before the ICO. 

A [report](https://tezos.foundation/wp-content/uploads/2019/08/Tezos-Foundation-Biannual-Update-August-2019.pdf) published in Aug 2019 provides some insight into how the Tezos Foundation is managing its funds. They hold 61% of their $650 million USD equivalent as BTC, 15% as bonds/etfs/commodities, 15% as XTZ (their ICO tokens and staking rewards, untouched), 6% fiat. The Foundation funds a large number of initiatives but keeps the details of these arrangements (amounts, terms) private.

Tezos also has ongoing [inflation](https://messari.io/asset/tezos), with ~42 million XTZ awarded to Bakers each year (or a target of ~5.5% annual inflation). 96% of the current total supply was issued to ICO participants. Given that many of those same ICO participants have elected the bakers and continued to collect a share of the inflation rewards, the outlook for Tezos is still closely tied to that initial set of participants and the decision-makers at the Foundation.

Protocol upgrades can include the creation of new XTZ tokens from inflation. The first Tezos mainnet upgrade included 100 XTZ tokens so that the developers who produced it could buy a round of drinks. This mechanism is not playing a significant role in funding Tezos development yet. This kind of funding will be limited to supporting entities that work on the protocol, as contributors to other aspects will not be in a position to bundle inflation XTZ with on chain proposals.

Arthur Breitman has recently [written](https://medium.com/@arthurb/potential-design-for-a-simple-and-evolvable-on-chain-treasury-77cfe2176423) about a design for a simple on chain treasury, which if implemented will extend the influence stakeholders have over the direction development takes.
