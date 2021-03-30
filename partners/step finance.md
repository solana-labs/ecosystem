---
slug: step finance
date: 2021-03-22
title: Step Finance
logline: STEP.finance is an automated trading strategies platform.
cta: https://github.com/aaronovz1/step-solana
logo: /img/step.svg
category: DeFi
---

STEP.finance is an automated trading strategies platform of which the first strategy is a Dollar Cost Averaging (DCA) product for users to swap one token for another over a defined time period autonomously without user input. STEP is the first implementation of a DCA contract in DeFi which is made possible by the low cost and high speed of Solana (project profitable day 1 on Solana at >$0 vol, on ETH its ~300k vol to breakeven assuming a 1% fee). STEP integrates the SPL-Tokenswap program on Solana (an AMM) for liquidity but can easily also be setup to execute transactions on the Serum CLOB. The STEP contract is intended to implement any arbitrary strategy and in future the team expects to implement more strategies like EMAs and RSI crossover trading. STEP is designed based off Figma mockups the team made with a simple UI for users to Deposit token A and purchase token B over a defined time period- both tokens must be on the STEP whitelist. When a user sets up this purchase we call this a 'stream' and the user can see any active streams on their activity page. The STEP contract is composable across the same layer on Solana like every contract with the only restriction being the token whitelist which is defined by STEP. It is designed to be intuitive to DeFi natives and targeting existing coins from ETH which have been wrapped on Solana. Users can rest assured they can Dollar Cost Average into any coin available on Solana AMMs (or later Serum DEX), this aligns with the goals of the Solana and Serum teams to attract users and liqudity to the Solana/Serum DEX. Team of 2, prior experience building crypto startups and long time DeFi power users, looking forward to showcase Step.finance to the world.
