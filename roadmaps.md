---
title: Ellaism Roadmaps
---

Ellaism is a network without pre-mine, thus its development team is
decentralized. It is expected that there will be multiple teams developing on
the Ellaism blockchain. Ellaism Core is a non-profit team that develops and
maintains some core infrastructures on the Ellaism blockchain.

You can donate to Ellaism Core by supporting the **Dev Fund**, which you can
find more information on [Donate to Ellaism](/donations/) page.

## Funding and Community Effots

One of the most important thing that users would care about would be how Ellaism
Core is funded and how the team would impact the community. Here we make several
points about what we are and what we aren't.

1. **Core is run by donations.** Everyone owns the Ellaism blockchain, thus they
   have the choice of whether they want to support Core or not, by making
   donations. **We will have complete financial transperancy,** so you know
   exactly where you donations go. Most of the donations will be used to pay
   salary for developers.
2. **Core has a public inspectable roadmap.** And it is what you're seeing right
   now. Every year, we publish a new short-term roadmap, for the coming year,
   three months in advance (November to February next year). Community always
   has chance to propose changes to the roadmap.
2. **Core is replacable.** Ellaism has no pre-mine. Every time when the
   community is not happy with Core, it has chance to replace Core by another
   team, by switching its donations.
   
Below are lists of our roadmap plan. Currently we're in the Request for Comments
period. You can submit your suggestions to the public Discord server, or
privately to [ellaismer@protonmail.ch](mailto:ellaismer@protonmail.ch). Note
that we only list things we plan to implement this year. That means many other
exciting features will not be listed here. This includes:

* Sharding and blockchain scaling.
* Light client.
* Decentralized bulk storage integrated with blockchain.
* And many others.

## Client and Wallet Development and Maintainance

Full nodes (clients) and lightweight wallets are probably the most important
pieces of the network. In the coming year, we plan to:

* Develop the [go-ellaism client](https://github.com/ellaism/go-ellaism).
* Maintain support for [Parity
  client](https://github.com/ellaism/parity-config).
* Develop the [ellawallet](https://ellaism.github.io/ellawallet).

## Ethereum Virtual Machine and Developer Tools

EVM is the central part of Ellaism, and developer tools are important pieces
that allows people to actually use the network. In the coming year, we plan to:

* Optimize the performance of Ellaism Virtual Machine. This helps the network to
  handle more transactions.
* Port and maintain other developer tools for Ellaism chain, if needed.

## Goverance System and Hard Forks

Ellaism uses the bullet-proof goverance system – proof of work and hard/soft
forks. Many would argue that an additional layer of democracy-like goverance
system, such as a chain-level decentralized autonomous organization (chain-level
DAO), is necessary. We respect this view, and would consider to incoperate an
additional layer of goverance system in the future. However, we would be
cautious to go through this approach and, in the short-term, use an on-chain
optional system instead.

Chain-level DAOs are usually of high complexity. If implemented incorrectly, can
lead to tyranny of the majority. This, in case of a divide, does not help in
reaching consensus – the minority might decide to hard fork and change the
chain-level DAO rules, and it still leads to a new chain.

Consensus is a research problem in politics. We believe there is a reason that
we have multiple cryptocurrencies. In case of a divide, Core team will not
choose side and will support the view of both sides by implementing it in the
client Core supported, and let users decide.

In the short term, the on-chain system is totally optional and will only be used
as an indicator of public opinions. This includes:

* **CarbonVote:** you vote with the amount of ELLA you have. One ELLA, one vote.
* **MinerVote:** you vote with blocks you mined on Ellaism. One GPU, one vote.

In the coming year, we plan to:

* Implement a public interface to incoperate CarbonVote and MinerVote. So
  everyone can easily find out the current network opinions.
* Support additional rules, such as voting delegation (you delegate your vote to
  other community members you trust).
* Work on specifications to standardize CarbonVote and MinerVote.

## Ethereum Protocol-level New Features

If the community decides to incoperate new features from Ethereum and reaches
consensus, we will prepare and implement them. We should treat them with
caution, however, because not all of them benefits the Ellaism blockchain.
Ethereum’s new features might include:

* Difficulty and total difficulty fix related to uncle and GHOST protocol.
* zkSNARK support with transaction privacy (EIP197).
* Big integer operations support for RSA related operations (EIP196 and EIP198).
* New EVM opcodes, including REVERT, RETURNDATASIZE, RETURNDATACOPY, STATICCALL.

## BTC Relay and Masternodes

BTC relay allows validation of Bitcoin transactions on Ellaism blockchain. In
the coming year, we plan to:

* Implement a new interface for BTC relay and allow easier usage.
* Restore Bitcoin-ELLA atomic swap.
* Build incentives for miners to run relays, and act as "masternodes".

## Protocol Specification

We believe that multiple teams and multiple clients result in a healthy
ecosystem for Ellaism. As a result, protocol specifications need to be created
and maintained as a common ground. Currently, while it has been improved along
the years, Ethereum still has many errors and missing pieces both in its Yellow
Paper, and in the Ethereum Inprovement Proposals repository. In the coming year,
we plan to:

* Create a clearly defined editor process for protocol specifications.
* Fill and correct missing pieces in the current [protocol
  specifications](https://github.com/ellaism/specs).