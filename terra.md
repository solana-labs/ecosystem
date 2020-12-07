---
slug: "terra"
date: "2020-04-03"
title: "Terra"
logline: "Terra is building a high speed token bridge to Solana, enabling the hyperfast transaction of Terra stablecoins on all of Solana’s Dapps."
cta: "https://medium.com/terra-money/terra-partners-with-solana-to-establish-low-latency-bridge-expanding-its-stablecoin-ecosystem-to-15883bdbb0fb"
logo: /img/terra.svg
category: stablecoin
---

Terra is a thriving payments network that is supported by a basket of stablecoins pegged to the world’s largest currencies. Today, these stablecoins largely flow through Terra’s flagship app, CHAI, which recently crossed 1M MAU and over \$3M USD in daily transaction volume. Terra is backed by an impressive team and some of the world’s best investors.

Together we’re building a new high-speed token bridge that facilitates the transfer of Terra stablecoins into Solana’s dapp ecosystem. Terra’s tokens will be the first stablecoins on the Solana network. By bringing stablecoins onto our network, we aim to dramatically expand the design space for developers, opening the door to novel applications that require price-stable payments. Similarly, and by the same token, we hope to support Terra’s expansion by creating a seamless gateway to our developer community.

To facilitate the bridge, we’re building two smart contracts (contract T and contract S respectively) that will each be deployed on both platforms by May 2020. The bridge leverages a mint-and-burn model via these mirrored smart contracts. Users can mint specific Terra tokens on Solana by calling a burn transaction on contract T and then minting a transaction on contract S by submitting a proof to Solana that the Terra tokens were burned using contract T. This works in both directions, creating a two-way warp.
