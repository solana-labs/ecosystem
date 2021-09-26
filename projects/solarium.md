---
slug: "solarium"
title: "Solarium"
date: 2021-07-25
logline: "Solarium is a fully decentralised, end-to-end encrypted instant messenger on the Solana blockchain."
category: app
logo: /img/solarium.svg
cta: "https://solarium.chat/"
status: live
website: https://solarium.chat/
twitter: https://twitter.com/solariume2e
---

Solarium is a fully decentralised, end-to-end encrypted, censorship-resistant instant messenger based on the Solana blockchain. Solarium is currently in alpha phase, running on the Solana devnet.

All messages in Solarium are end-to-end encrypted using the XChaCha20-Poly1305 symmetric encryption algorithm, using a 256-bit content encryption key (CEK) that is shared for all messages in a given channel.

The message content in Solarium is not directly signed, i.e. the data itself, once decrypted, does not contain details about the sender. Instead, the blockchain transaction that adds the message to the channel is signed by the sender. The Solarium program ensures the following statements are true:

1. The sender key of the transaction currently belongs to the DID of the stated sender of the message
2. The sender DID is a member of the channel that the message is being posted to
