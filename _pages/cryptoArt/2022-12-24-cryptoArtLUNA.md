---
title: crypto Art History-LUNA
author: Aim Liu
date: 2022-12-24
category: Jekyll
layout: post
image : /assets/images/luna_peg.jpeg
---
updated : _{{ page.date }}_

# LUNA and UST

**LUNA**
is the native token of Terra chain

**UST**
is the stable coin of the chain

## Peg Machanism of UST
UST has no mint/burn limit

### Above peg
**BUY** LUNA --> Price ++ --> **BURN** --> Supply in the market --
**SELL** UST --> Price -- --> Supply in the market ++
> given LUNA = 100$ UST = 1.05$
> Investor will profit by;
> - Prepare 100 USD
> - **BUY** 100$ worth of LUNA (1 token)
> - **BURN** LUNA and **MINT** UST worth of 100$ (will obtain 100 tokens of UST)
> - **SELL** UST for 1.05$ per token (obtain 105$-fee)
> - Eventually profit 5$

### Below peg
**BUY** UST --> Price ++ --> **SWAP** --> Supply in the market --
**SELL** LUNA --> Price -- --> Supply in the market ++
> given LUNA = 100$ UST = 0.95$
> Investor will profit by;
> - Prepare 100 USD
> - **BUY** 100$ worth of UST (~105 tokens)
> - **SWAP/BURN** swap using LUNA/UST pair or reverse-burn UST ot get LUNA . Since LUNA see UST as 1$ unit, will obtain 105$ worth of LUNA (1.05 token)
> - **SELL** LUNA for 100$ per token (obtain 105$-fee)
> - Eventually profit 5$

![LUNA peg.]({{page.image | relative_url }})

## Ideal Scenario
- Everyone has **demand** for UST
- Still, there was only demand of UST because of  **Anchor protocol**. (20% APY)
- Somehow DO KWON decided to buy BTC to back UST value.   [LFG buy BTC](https://cryptobriefing.com/terras-lfg-acquires-1-5b-more-bitcoin-with-3acs-help/). Which lead to later tragedy.



