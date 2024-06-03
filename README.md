# Awesome Cashu 🥜✨

A curated, collaborative list of awesome resources for getting ramped up with Cashu

## What's Cashu?

Cashu is a free and open-source Chaumian Ecash system built for Bitcoin. [Chaumian Ecash](https://en.wikipedia.org/wiki/Ecash) is an anonymous cryptographic electronic money or electronic cash system invented in 1982. Cashu is a modern ecash implementation on Bitcoin.

Visit [cashu.space](https://cashu.space/) or [docs.cashu.space](https://docs.cashu.space/) to learn more.

## The Cashu protocol

Cashu is an open Ecash protocol for anyone to implement. The specifications, called [Cashu NUTs](https://github.com/cashubtc/nuts) (Notation, Usage, and Terminology) describe how to implement the protocol. Multiple Cashu client libaries make it easy for developers to write their own wallets.

## Mints

- [Nutshell](https://github.com/cashubtc/nutshell) is the reference mint implementation in Python.
- [Moksha](https://github.com/ngutech21/moksha) is a Cashu wallet and mint written in Rust.
- [Cashu-rs-mint](https://github.com/thesimplekid/cashu-rs-mint) is a mint implementation in Rust.
- [Gonuts](https://github.com/elnosh/gonuts) is a mint written in Golang.
- [lnbits-cashu](https://github.com/cashubtc/lnbits-cashu) is an LNbits Cashu mint extension based on Nutshell.
- [CLN mint plugin](https://github.com/gudnuf/cln_pyshu_mint) is a plugin for running a mint on your own node.


## Wallets

- [Nutshell](https://github.com/cashubtc/nutshell) is a CLI wallet available through PyPi. It comes with builtin Tor, supports multiple mints, and can send and receive tokens on nostr, and supports pay-to-script-hash (P2SH) tokens.
- [Nutstash](https://nutstash.app/) is a Cashu web wallet with many features such as multimint support and support for sending and receiving tokens via nostr. Nutstash is written in TypeScript and uses the [cashu-ts](https://github.com/cashubtc/cashu-ts) library.
- [eNuts](https://enuts.cash) is a Cashu wallet for Android and IOS. It empowers you with a user-friendly interface that streamlines every step of your Ecash journey.
- [Minibits](https://github.com/minibits-cash/minibits_wallet) is a mobile Cashu wallet with a focus on performance and usability.
- [Feni](https://github.com/cashubtc/cashu-feni) is a Cashu wallet and mint written in Golang. It supports multiple mints, P2SH, and offers Docker images for easy deployment.
- [Cashcrab](https://github.com/thesimplekid/cashcrab) is a Cashu wallet with a flutter UI and with as much logic as possible in rust using [cashu-crab](https://github.com/thesimplekid/cashu-crab) with nostr integration for contacts and messaging.
- [Moksha](https://github.com/ngutech21/moksha) is a Cashu wallet and mint written in Rust.
- [Cashu.me](http://cashu.me/) is another web wallet built on Quasar and Vue.js. It is written in JavaScript and TypeScript.
- [Macadamia](https://github.com/zeugmaster/macadamia) is a Cashu wallet for iOS written in Swift.
- [BoardwalkCash.com](https://boardwalkcash.com/setup) is a dollar-based CashuBTC wallet built on top of Bitcoin and connected to Nostr.

## Libraries

Cashu libraries allow developers to build wallets, mints, and other services that use Cashu.

#### Python

- [Nutshell](https://github.com/cashubtc/cashu) Nutshell is a Python library for using Cashu wallets and mints inside other Python projects

#### TypeScript & JavaScript

- [Cashu-TS](https://github.com/cashubtc/cashu-ts) is a TypeScript library for building Cashu wallets
- [cashu-crypto-ts](https://github.com/cashubtc/cashu-crypto-ts) is a TypeScript library that implements basic crypto operations for cashu wallets and mints.
- [Cashu tools](https://github.com/gandlafbtc/cashu-tools) are advanced Cashu wallet tools based on cashu-ts in TypeScript.
- [blind-sig-js](https://github.com/supertestnet/blind-sig-js) is a JavaScript library implementing Cashu's blind signature mechanism
- [cashu-wallet](https://github.com/ebrakke/cashu-wallet) is a framework-agnostic Cashu wallet written in TypeScript.

#### Rust

- [@cashubtc/cdk](https://github.com/cashubtc/cdk) wallet and mint library
- [@ngutech21/moksha](https://github.com/ngutech21/moksha) wallet and mint library and flutter app
- [@clarkmoody/cashu-rs](https://github.com/clarkmoody/cashu-rs) wallet and mint library

#### Golang

- [Cashu-Feni](https://github.com/cashubtc/cashu-feni) is a Golang library for Cashu wallets and mints
- [gonuts](https://github.com/elnosh/gonuts) Cashu library for wallets and mints in Go.

#### Kotlin

- [cashu-client](https://github.com/thunderbiscuit/cashu-client) is a Cashu client library in Kotlin.
- [cashu-bdhke-kmp](https://github.com/gandlafbtc/cashu-bdhke-kmp) is a Kotlin library that implements the basic cryptographic blinded signature scheme.

#### Dart

- [cashu_dart](https://github.com/ryzizub/cashu_dart) is one Library for Cashu wallets written in Dart
- [Cashu-dart](https://github.com/0xchat-app/cashu-dart) is another Library that allows developers to integrate Cashu easily into apps

## Tools
- [Cashu decoder](https://github.com/nostrapps/cashu/) is a [web decoder](https://nostrapps.github.io/cashu) for Cashu tokens
- [Numbnoot](https://numbnoot.gandlaf.com) is a simulator for the Blind Diffie-Hellman Key Exchange scheme in used in Cashu
- [bitcoinmints](http://bitcoinmints.com) is a list of ecash mints, supported NUTS, and reviews of the mints.  [GitHub](https://github.com/MakePrisms/bitcoinmints)
- [Cashumints.space](https://Cashumints.space) is an index of Cashu ecash mints and offers reviews of these mints, complete with comprehensive mint pages.
## Projects

### X-Cashu

- [Proxnut](https://github.com/gandlafbtc/proxnut)  forwards requests only if they have a valid cashu token attached to the X-Cashu header.
- [ChatNut](https://chatnut.sparkpay.pt/) is a privacy-preserving Chat application for large language models (LLMs) that users pay-per-request with an integrated Cashu wallet without having to create accounts.
- [X-Cashu](https://github.com/callebtc/xcashu) is a work-in-progress project that aims to create a 402 Payment Required scheme to monetize REST API access by using ecash in HTTP headers.

### Various nutcases

- [Nutband](https://github.com/jooray/nutband) aims to use Cashu payments over long range radio and other mesh networks using Reticulum and LXMF.
- [Mint index](https://mintindex.gandlaf.com/) An index to find Cashu mints ([GitHub](https://github.com/gandlafbtc/mintindex))
- [Cashu faucet](https://www.gandlaf.com/faucet/anarchy) allows you to deposit and withdraw Cashu tokens from a web interface. Read the code [here](https://github.com/gandlafbtc/cashu-faucet).
- [Redeem](https://redeem.cashu.me/) webtool allows you to redeem any Cashu token directly onto your Lightning wallet without having to receive it in a Cashu wallet [GitHub](https://github.com/cashubtc/cashu-redeem).
- [Spacenut](https://spacenut.nutstash.app) The sickest Cashu-enabled game you've ever played ([GitHub](https://github.com/gandlafbtc/spacenut))
- [CashuProjects](https://github.com/CashuProjects) is collection of TypeScript projects
- [SatsContactBot](https://github.com/massmux/SatsContact) is a Telegram bot that converts Lightning Zaps/Tips in Cashu Ecash sent to you via a Telegram message
- [npub.cash](https://npub.cash) is a Lightning-Address provider for nostr pubkeys based on [Cashu-Address](https://github.com/lightning-digital-entertainment/cashu-address)
