---
qip: 015
layer: na
title: "Implement privacy feature for QRL"
author: sync
comments-summary: 
comments-uri: https://github.com/theQRL/qips/pull/31
status: proposal/open
type: discussion
created: 2021-05-09
---
# Implement privacy feature

## Abstract

QRL currently has no privacy features. This means ***every transaction can be followed through the blockchain***. The identity of the original wallet holder can be revealed this way by for example tracing the transaction back to KYC required exchanges.

## Motivation

QRL adding privacy features will most likely attract a new target audience: privacy conscious people.

***Edward Snowden: "Arguing that you don't care about the right to privacy because you have nothing to hide is no different than saying you don't care about free speech because you have nothing to say"***

## Implementation

Privacy as an optional feature is no privacy at all so would need to be the default transaction type. 

See Monero's privacy features, such as:

- Stealth addresses
- Untracable transaction outputs
- Confidential transactions (hide amount sent)
- TOR/onion (or similar) network layer.

## Considirations

This will most likely require a hardfork.

Bittrex doesn't allow privacy coins, this means that QRL will be removed from Bittrex. We have to find alternative exchanges.

Other exchange(s):
Binance, Tradeogre, Uniswap or other decentralized exchanges.
