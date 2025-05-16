# Awesome Cashu 🥜✨

A curated, collaborative list of awesome resources for getting ramped up with Cashu

## What's Cashu?

Cashu is a free and open-source Chaumian Ecash system built for Bitcoin. [Chaumian Ecash](https://en.wikipedia.org/wiki/Ecash) is an anonymous cryptographic electronic money or electronic cash system invented in 1982. Cashu is a modern ecash implementation on Bitcoin.

Visit [cashu.space](https://cashu.space/) or [docs.cashu.space](https://docs.cashu.space/) to learn more.

## The Cashu protocol

Cashu is an open Ecash protocol for anyone to implement. The specifications, called [Cashu NUTs](https://github.com/cashubtc/nuts) (Notation, Usage, and Terminology) describe how to implement the protocol. Multiple Cashu client libaries make it easy for developers to write their own wallets.

## Mints

- [Nutshell](https://github.com/cashubtc/nutshell) is the reference mint implementation in Python.
- [cdk-mintd](https://github.com/cashubtc/cdk/tree/main/crates/cdk-mintd) is a mint implementation in Rust using CDK.
- [nutmix](https://github.com/lescuer97/nutmix) is another mint written in Golang.

## Wallets

- [Nutshell](https://github.com/cashubtc/nutshell) is a CLI wallet available through PyPi. It comes with builtin Tor, supports multiple mints, and can send and receive tokens on nostr, and supports pay-to-script-hash (P2SH) tokens.
- [Nutstash](https://github.com/gandlafbtc/nutstash-wallet) is a Cashu web wallet with many features such as multimint support and support for sending and receiving tokens via nostr. Nutstash is written in TypeScript and uses the [cashu-ts](https://github.com/cashubtc/cashu-ts) library.
- [Minibits](https://github.com/minibits-cash/minibits_wallet) is a mobile Cashu wallet with a focus on performance and usability.
- [Cashu.me](https://github.com/cashubtc/cashu.me) is another web wallet built on Quasar and Vue.js. It is written in JavaScript and TypeScript.
- [Macadamia](https://github.com/zeugmaster/macadamia) is a Cashu wallet for iOS written in Swift.
- [BoardwalkCash](https://github.com/MakePrisms/boardwalkcash) is a dollar-based CashuBTC wallet built on top of Bitcoin and connected to Nostr.
- [Safebox](https://github.com/trbouma/safebox) is a Python implementation of a Cashu wallet component that lives in nostr and is intended for use by services that need a custodial wallet for Lightning payments. Still experimental
- [Coconut](https://github.com/zig-bitcoin/coconut) is a Cashu wallet written in Zig. 
- [bullishNuts](https://github.com/thebullishbitcoiner/bullishnuts) is an ecash wallet in early beta phase.
- [Sovran](https://github.com/SovranBitcoin) is an ecash wallet
  
## Wallets- On-Chain/Lightning Wallets 
- [Blitz](https://github.com/BlitzWallet/BlitzWallet) is a Lightning wallet with Cashu ecash integration.
- [Voltz](https://www.lnvoltz.xyz/) is an all-in-one on-chain+lightning+ecash wallet.
- [coinos](https://github.com/coinos/coinos-ui) is a Lightning wallet with Cashu ecash integration.

## Wallets - Nostr NIP-60/61 support
- [Cashu Cache](https://github.com/robwoodgate/cashu-cache) lets you create (or update) a NIP-60 compliant Cashu Wallet and advertizes the NIP-61 public key so you can receive NutZaps. It also makes a wallet backup.
- [Cashu Gather](https://www.nostrly.com/cashu-gather/) lets you receive NutZaps sent to your NIP-61 public key, creating a token per mint you can redeem with any wallet.
- [nutlife.lol](https://nutlife.lol/) 
- [nuts.cash](https://www.nuts.cash/)
- [lnw.cash](https://lnw.cash/) [GitHub](https://github.com/AlbiziaLebbeck/lnwCash)
- [Nutsack](https://github.com/pablof7z/nutsack) [GitHub](https://github.com/pablof7z/nutsack)
- [Highlighter](https://github.com/pablof7z/highlighter)
- [Shopstr](https://github.com/shopstr-eng/shopstr) has a built-in Cashu wallet for payments that has several features and uses the [cashu-ts](https://github.com/cashubtc/cashu-ts) library.
- [Olas](https://github.com/pablof7z/olas) is an Instagram-like Nostr Client that supports NIP-60/61 (nutzaps/wallet), uses [nutsack](https://nutsack.me/)
- [Learn civics](https://civico.app) is a civics citizenship app that has NIP-60 and NIP-61 support.
- [AFK](https://afk-community.xyz/app/cashu) is a community application with NIP-60 support.
- [Clams](https://clams.tech/) is a Personal Finance and Business Analytics application that has a Cashu NIP-60 connection.
 
## Libraries

Cashu libraries allow developers to build wallets, mints, and other services that use Cashu.

#### C#
- [dotnut](https://github.com/Kukks/DotNut) is a C# library implementing the Cashu protocol


#### Dart

- [Cashu-dart](https://github.com/0xchat-app/cashu-dart) is another Library that allows developers to integrate Cashu easily into apps
  

#### Python

- [Nutshell](https://github.com/cashubtc/cashu) Nutshell is a Python library for using Cashu wallets and mints inside other Python projects

#### Rust

- [@cashubtc/cdk](https://github.com/cashubtc/cdk) wallet and mint library

#### Swift
- [CashuSwift](https://github.com/zeugmaster/CashuSwift) is a Swift library implementing the Cashu protocol

#### TypeScript & JavaScript

- [Cashu-TS](https://github.com/cashubtc/cashu-ts) is a TypeScript library for building Cashu wallets
- [cashu-crypto-ts](https://github.com/cashubtc/cashu-crypto-ts) is a TypeScript library that implements basic crypto operations for cashu wallets and mints.
- [Cashu tools](https://github.com/gandlafbtc/cashu-tools) are advanced Cashu wallet tools based on cashu-ts in TypeScript.
- [blind-sig-js](https://github.com/supertestnet/blind-sig-js) is a JavaScript library implementing Cashu's blind signature mechanism
- [cashu-wallet](https://github.com/ebrakke/cashu-wallet) is a framework-agnostic Cashu wallet written in TypeScript.

## Documentation Web Sites
Note: These documentation sites are works in progress (WIP) and welcome feedback and suggestions for content.
- [CDK](https://cashudevkit.org/) is a CDK doc site. [GH](https://github.com/cashubtc/cdk) for input/feedback.
- [CDK](https://ok300.github.io/cdk-docs/mint/03_systemd_service/) is a CDK doc site.
- [cashu-ts](https://cashubtc.github.io/cashu-ts-docs/) is a cashu-ts doc site.  [GH](https://github.com/cashubtc/cashu-ts-docs) for input/feedback.
- [Mint Best Practices](https://findingsov.github.io/cashu-mint-docs/) is a mint best practices doc site. [GH](https://github.com/findingsov/cashu-mint-docs) for input/feedback.

## Tools

### Testnut Mints
- [https://testnut.cashu.space](https://testnut.cashu.space) is a testnut mint with fees with unbacked fake ecash for testing  
- [https://nofees.testnut.cashu.space ](https://nofees.testnut.cashu.space) is a testnut mint with no fees with unbacked fake ecash for testing  

### Mint Discovery and Audit
- [bitcoinmints](http://bitcoinmints.com) is a list of ecash mints, supported NUTS, and reviews of the mints.  [GitHub](https://github.com/MakePrisms/bitcoinmints)
- [Cashumints.space](https://Cashumints.space) is an index of Cashu ecash mints and offers reviews of these mints, complete with comprehensive mint pages.
- [Mint Audit](https://audit.8333.space/) is a mint auditor and [Mint Watch Bot](https://primal.net/p/npub1cashu0thfukl57lgwtarn7h4jrzrg2e346zc8sjvjd8u5hheds0qlhpt92) is a bot that watches the status of mints.
### Restore 
- [Restore Tool-from seed](https://wallet.cashu.me/restore) is a tool that enables you to restore from a seed phrase.

### Token Decoders 
- [Cashu Decode](https://decode.8333.space/) - a v4 token decoder that lets you view and edit the tokens in real time.
- [Cashu decoder](https://github.com/nostrapps/cashu/) is a [web decoder](https://nostrapps.github.io/cashu) for Cashu v3 tokens
- [Cashu decoder](https://nutcoder.netlify.app/) is a decoder for Cashu v3 and v4 tokens

### Misc
- [Numbnoot](https://numbnoot.gandlaf.com) is a simulator for the Blind Diffie-Hellman Key Exchange scheme in used in Cashu
- [Nutshell configurer]( https://celadon-semolina-91d112.netlify.app/) is a tool to set up the .env file for nutshell mints

## Projects
### P2PK Locked and Multi-Sig Tokens
- [Cashu NutLock](https://www.nostrly.com/cashu-nutlock/) lets you lock a Cashu token to one or more public keys (Nostr NPUB or P2PK) for a set time. Supports complex multi-signature (multi-sig) tokens.
- [Cashu Witness](https://www.nostrly.com/cashu-witness/) lets you unlock locked Cashu tokens by signing them with your private key (Nostr NSEC or P2PK). Supports multi-sig, and will show you whose signature(s) are required to unlock.

### Messengers
- [0xChat](https://github.com/0xchat-app) 0xchat is a secure chat app built on the Nostr protocol with payments support using Cashu
- [KeyChat](https://github.com/keychat-io/keychat-app) Keychat is a chat app built on Cashu, Nostr and the Signal Protocol.

### X-Cashu
- [Proxnut](https://github.com/gandlafbtc/proxnut)  forwards requests only if they have a valid cashu token attached to the X-Cashu header.
- [ChatNut](https://chatnut.sparkpay.pt/) is a privacy-preserving Chat application for large language models (LLMs) that users pay-per-request with an integrated Cashu wallet without having to create accounts.
- [X-Cashu](https://github.com/callebtc/xcashu) is a work-in-progress project that aims to create a 402 Payment Required scheme to monetize REST API access by using ecash in HTTP headers.

### LN Address Support
- [npubcash-server](https://github.com/cashubtc/npubcash-server) is a Lightning-Address provider for nostr pubkeys based on [Cashu-Address](https://github.com/lightning-digital-entertainment/cashu-address)
- [SatsContact](https://github.com/massmux/SatsContact) is a Lightning address provider that automatically generates @sats.contact Lightning addresses and real-time converts received amounts in Cashu tokens sent to the Telegram Chat.

### Redeem Tools
- [Nostrly Cashu Redeem](https://www.nostrly.com/cashu-redeem/) is an updated version of [Redeem](https://redeem.cashu.me/) that uses latest [Cashu-TS](https://github.com/cashubtc/cashu-ts), reads v4 tokens, emojis, and gives 'change'. Read the code [here](https://github.com/robwoodgate/cashu-redeem).
- [Cashu-redeem](https://cashu-redeem.vercel.app/) webtool allows you to redeem any Cashu token directly onto your Lightning wallet without having to receive it in a Cashu wallet [GitHub](https://github.com/cashubtc/cashu-redeem).
- [Cashu-redeem (newer)](https://redeem.cashu.me/) is a webtool that enables you to redeem Cashu v4 tokens and decode emojis to redeem Cashu tokens directly into your Lightning wallet.  It has support for bitcoin connect (NWC) and also stores change in localstorage. 

### Various nutcases
- [Cashu-brrr](https://brrr.gandlaf.com) is a Cashu ecash printer. [GitHub](https://github.com/gandlafbtc/cashu-brrr/)
- [Athenut](https://athenut.com/) search smarter (Kagi-powered). Pay in sats. [Github-Mint](https://github.com/thesimplekid/athenut-mint), [Github-Frontend](https://github.com/thesimplekid/athenut-frontend)
- [Almandine](https://lab.oak-node.net/almandine) uses Athenut above, basic wrapper with a built-in CDK wallet
- [Nutband](https://github.com/jooray/nutband) aims to use Cashu payments over long range radio and other mesh networks using Reticulum and LXMF.
- [Cashu faucet](https://www.gandlaf.com/faucet/anarchy) allows you to deposit and withdraw Cashu tokens from a web interface. Read the code [here](https://github.com/gandlafbtc/cashu-faucet).
- [Spacenut](https://spacenut.nutstash.app) The sickest Cashu-enabled game you've ever played ([GitHub](https://github.com/gandlafbtc/spacenut))
- [CashuProjects](https://github.com/CashuProjects) is collection of TypeScript projects
- [cashu-escrow-kit](https://github.com/f321x/cashu-escrow-kit) Ecash escrow provider and client concept.
- [CLN mint plugin](https://github.com/gudnuf/cln_pyshu_mint) is a work-in-progress CLN plugin for running a mint on your own node.
- [Wrapnuts](https://github.com/wrapnuts/wrapnuts/tree/main) is a CLI developed for embedding cashu into files with the help of steganography.
- [Paywally](https://github.com/bordalix/paywally) is a Lightning paywall powered by Cashu.
- [Hide a message in an emoji](https://github.com/paulgb/emoji-encoder) is a [site](https://emoji.paulbutler.org) that allows you to hide ecash in an emoji.
- [Meme amigo](https://memeamigo.lol/) enables you to hide ecash in a meme.
- [Hashpool](https://github.com/vnprc/hashpool) is an accountless mining pool that uses ecash to represent mining shares.
- [Tollgate](https://github.com/OpenTollGate/tollgate-app)  turns any WiFi router into a decentralized ISP using bitcoin and ecash.
- [Cashucards](https://github.com/Marc26z/CashuCards) are greeting Ccards that give bitcoin using the Cashu protocol.
- [ecash OpenAI API client](https://github.com/9qeklajc/ecash-402-client) is a privacy-focused payment gateway that enables anonymous micropayments using Cashu ecash for accessing Large Language Models via the OpenAI API.
- [Receipt.cash](https://github.com/Origami74/receipt-cash) is a bill splitter to snap a picture of a fiat bill and easily split costs auto-converted to BTC. It's based on Cashu payment requests.
- [routstr](https://github.com/routstr) is a  marketplace to buy and sell LLM APIs using Cashu ecash tokens.
  
## Currently Unmaintained Projects
- [eNuts](https://github.com/cashubtc/eNuts) is a Cashu wallet for Android and IOS. It empowers you with a user-friendly interface that streamlines every step of your Ecash journey.
- [Chamberlain](https://github.com/sovereign-app/chamberlain) is a mint implementation with an Integrated LDK Node using CDK.
- [Moksha](https://github.com/ngutech21/moksha) is a Cashu wallet and mint written in Rust.
- [Coconut](https://github.com/zig-bitcoin/coconut) is a Cashu mint written in Zig.
- [Cashubrew](https://github.com/AbdelStark/gakimint) is a Cashu mint written in Elixir.
- [Cashcrab](https://github.com/thesimplekid/cashcrab) is a Cashu wallet with a flutter UI and with as much logic as possible in rust using [cashu-crab](https://github.com/thesimplekid/cashu-crab) with nostr integration for contacts and messaging.
#### Kotlin
- [cashu-client](https://github.com/thunderbiscuit/cashu-client) is a Cashu client library in Kotlin.
- [cashu-bdhke-kmp](https://github.com/gandlafbtc/cashu-bdhke-kmp) is a Kotlin library that implements the basic cryptographic blinded signature scheme.

