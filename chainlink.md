---
slug: "chainlink"
date: "2020-04-03"
title: "Chainlink"
logline: "Together with Chainlink, Solana intends to develop a high frequency Oracle that can be used for trading binary options. One that is capable of price updates every 400ms with Solana’s architecture, with developers building DeFi assets and marketplaces using this platform."
cta: "https://medium.com/solana-labs/chainlink-and-solana-integration-high-quality-price-oracle-data-cd9fa41f6ecb"
logo: /img/chainlink.svg
category: oracle
---

Chainlink is a decentralized oracle network that currently provides decentralization at both the oracle and data source level. By using multiple independent Chainlink nodes, the user can protect against one oracle being a single point of failure. Similarly, using multiple data sources for sourcing market prices, the user can protect against one data source being a single source of truth.

Chainlink already offers secure and reliable market data via their Price Reference Contracts, a collection of decentralized oracle networks currently live on mainnet that secure 25+ DeFi price feeds, such as ETH/USD, CHF/USD, ETH/BTC, etc. Each Price Reference Contract is backed by at least seven of the 30 independent, security reviewed, and Sybil resistant nodes. These nodes source market data from a large pool of different highly respected data aggregator APIs, with at least seven deployed on each oracle network. The nodes’ individual responses are then aggregated together into a single data point and updated on-chain at specified intervals, such as by time (daily), deviation (every .5% change in price), or a customized combination of both (minimum once a day + 1% price deviations).

We plan to make Chainlink the oracle solution for both this initiative and the standard across all Solana Dapps. By doing so, Dapps will get secure access to all the inputs and outputs they need, while avoiding the major pitfalls with trying to deploy self-made oracles, such as long time delays, additional expenses, and even fatal security flaws.
