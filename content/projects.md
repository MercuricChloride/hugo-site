---
title: "Projects"
date: 2022-10-05T10:08:58-07:00
draft: false
---

# Soulbound Labs

_This is where I am currently doing the majority of my work._

[LINK: soulbound.xyz](https://soulbound.xyz)

Soulbound Labs was created to build a better way to do dao governance. Rather than the traditional 1 token = 1 vote governance model. We wanted a way to build a decentralized and flexible meritocracy. Where someone's voting power is determined based off what kind of actions they have performed within the context of the specific dao ecosystem or generalized actions on chain. This is super hard and expensive to do via traditional smart contract code so we needed to build a better way. We chose the graph's network to allow daos to build subgraphs, with different "reputation pathways" that mint unique non-transferable (soulbound) NFT's to represent varying voting power, based on how difficult or impactful an on-chain action is. Think of it similar to an RPG skilltree.

However, we had to build two important pieces to make this idea possible.

- ### A Subgraph Bridge

TLDR: A customizable way to bridge off chain subgraph data and put it on chain. Enabling the graph's network to function as an L2.

A subgraph simply defined, is some computation put on top of existing blockchain data, that allows you to filter the raw data and put it into a custom graphQL api so you can find what data you care about. But the problem here is that this is all done off chain, and we can't just take someone's word that what they say is correct. So we used the graph's existing crypto-economic system to have gurantees of correctness of results. Indexers, when they index data to create a subgraph have to stake $GRT, and should their data be wrong, they will get slashed and lose all of that money. We take a similar approach with the attestation system.

When an indexer wants to provide a query result to a subgraph bridge they must stake an amount of GRT set by the subgraph bridge. This is a customizeable amount because a defi application will not need the same level of security as a social media app. Should their result be proven false, they will get slashed and their GRT liquidated.

- ### A no code interface for building subgraphs

Subgraphs are a fantastic tool, but the new user experience for building them could definitely use some help. The main reason for this is that writing subgraphs is done in the programming language assemblyscript. This language looks similar to typescript, but has some strange quirks when using it that can make it a headache for a new developer to use.

We also believe that building reputation pathways should not be programmer exclusive. As anyone who has participated in a dao can know that not all important players in a dao are programmers.

So to make an inclusive user experience, we built a node based editor that makes it easy to track what on chain reputation actions you should care about, and how much voting power to reward for it.

And because these reputation pathways are just subgraphs, it makes it super easy to fork or modify existing reputation pathways, should the dao decide that the current model is broken or outdated. Simply deploy a new subgraphs bridge.

# Martian Premier League

[LINK: martianpremierleague.com](https://martianpremierleague.com)

What is the first thing you must do after colonizing mars? Obviously build a football league!

The MPL is an NFT project following a football league on mars shortly after colonization. I did a variety of work for them during their launch event "Bootcamp". The majority of it being website interface building for their risky games, as well as smart contract writing and testing for said risky games. It was a ton of fun, albeit a bit intense given the tight turnaround time of 1 game per week, but I learned a lot from the whole experience and my time there.

# Eth.Rebuild

A Typescript Rebuild of Austin Griffith's eth.build. I loved this project and it was a super useful learning tool for me when I was getting into web3. But unfortunately it followed the fate of most vanilla JS projects and is now unmaintained. So I rebuilt the project from scratch in typescript, using minimal frameworks for maximum project lifespan. With future maintainability in mind.

# Moonshot Collective

- ### Public Goods Party

I championed the building of the MVP version of the decentralized Gitcoin Grants 2.0 Ecosystem. Allows anyone to make their own QF public goods funding rounds for their own ecosystem, while hooking into the state of the globally accessible grants registry.

# Buidl Guidl / Personal Projects:

- ### SVG Fractal NFT

An interesting project with on chain NFT's

- ### Every NFT Ever

A meta nft art project I built trying to highlight why NFT's are important, and how the art is not what makes an NFT an NFT. Allowed a user to duplicate any NFT on mainnet ethereum for free.

- ### Polygon State Sync Starter Kit

A demo showcasing how to use the polygon network's state sync feature, for secure cross chain transactions.

- ### Harberger Tax NFT

A showcase of a novel taxation method that attempts to bridge a truly free market while still allocating money towards public goods. Built after reading _Green Pilled_ By Kevin Owocki

- ### 100 Year Aging NFT

A dynamic nft that ages over the course of 100 years, until it hits it's final stage of decay in the year 2121.

- ### Bonez

A fork of my 100 year Aging NFT build for Halloween 2021. It's a corpse that progresses through all 5 stages of decay, until finally you are left with a randomly generated corpse.

- ### LarpMinter

A site that allows conditional minting of a 3d version your "Eth-Bot" or "Moloch-Bot" for holders of either NFT. Built for gitcoin during their Greatest Larp Event in 2021.

- ### MVP 1/1 NFT

A stripped back and cheap contract designed for 1/1 NFT deployment, without all of the traditional bloat you have with an openzeppelin ERC-721 contract, while also being human readable. Built for songadaymann, with the concept being an artist can encode their music in ABC notation and mint it as a 1/1 for cheap.

# Freelance Work

- ### Operator LA

An experimental artist duo from Berlin and Los Angeles. I was commissioned to build a few different NFT's for them. One of which has been featured in Vogue.

- ### Assorted NFT and token projects

I have also done some work for not super notable NFT and token projects.
