# Awesome Cashu 🥜✨

A curated, collaborative list of awesome resources for getting ramped up with Cashu

## What's Cashu?

Cashu is a free and open-source Chaumian Ecash system built for Bitcoin. [Chaumian Ecash](https://en.wikipedia.org/wiki/Ecash) is an anonymous cryptographic electronic money or electronic cash system invented in 1982. Cashu is a modern ecash implementation on Bitcoin.

Visit [cashu.space](https://cashu.space/) or [docs.cashu.space](https://docs.cashu.space/) to learn more.

## The Cashu protocol

Cashu is an open Ecash protocol for anyone to implement. The specifications, called [Cashu NUTs](https://github.com/cashubtc/nuts) (Notation, Usage, and Terminology) describe how to implement the protocol. Multiple Cashu client libaries make it easy for developers to write their own wallets.

## Mints
- [mintd](https://github.com/cashubtc/cdk/tree/main/crates/cdk-mintd) is a mint implementation in Rust using CDK.
- [nutshell](https://github.com/cashubtc/nutshell) is the reference mint implementation in Python.
- [nutmix](https://github.com/lescuer97/nutmix) is another mint written in Golang.

## Wallets
- [Agicash](https://github.com/MakePrisms/agicash) is a Cashu wallet that uses the Open Secret platform.
- [Cashu.me](https://github.com/cashubtc/cashu.me) is a web wallet built on Quasar and Vue.js. It is written in JavaScript and TypeScript.
- [Coconut](https://github.com/zig-bitcoin/coconut) is a Cashu wallet written in Zig.
- [eNuts 2](https://github.com/cashubtc/eNuts/tree/master) is a Cashu wallet being resurrected from the original eNuts wallet.
- [Harbor](https://github.com/HarborWallet/harbor) is an ecash wallet for better desktop privacy.
- [Kashir](https://github.com/KashirApp/Kashir) is an ecash wallet with nostr integration built using React Native and CDK.
- [Macadamia](https://github.com/zeugmaster/macadamia) is a Cashu wallet for iOS written in Swift.
- [Minibits](https://github.com/minibits-cash/minibits_wallet) is a mobile Cashu wallet with a focus on performance and usability.
- [Nutstash](https://github.com/gandlafbtc/nutstash-wallet) is a Cashu web wallet with many features such as multimint support and support for sending and receiving tokens via nostr. Nutstash is written in TypeScript and uses the [cashu-ts](https://github.com/cashubtc/cashu-ts) library.
- [Nutshell](https://github.com/cashubtc/nutshell) is a CLI wallet available through PyPi. It comes with builtin Tor, supports multiple mints, and can send and receive tokens on nostr, and supports pay-to-script-hash (P2SH) tokens.
- [Safebox](https://github.com/trbouma/safebox) is a Python implementation of a Cashu wallet component that lives in nostr and is intended for use by services that need a custodial wallet for Lightning payments. Still experimental.
- [Satoshi Pay](https://github.com/Codepocketdev/satoshi-pay-wallet) is a Cashu wallet built to serve African markets and the global Bitcoin community. It uses the [cashu-ts](https://github.com/cashubtc/cashu-ts) library and features a mobile-first PWA design. [Site](https://satoshipay.me). 
- [Sovran](https://github.com/SovranBitcoin) is a Cashu wallet for iOS.

## Wallets- On-Chain/Lightning Wallets 
- [Blitz](https://github.com/BlitzWallet/BlitzWallet) is a Lightning wallet with Cashu ecash integration.
- [coinos](https://github.com/coinos/coinos-ui) is a Lightning wallet with Cashu ecash integration.
- [Voltz](https://www.lnvoltz.xyz/) is an all-in-one on-chain+lightning+ecash wallet.
- [Zeus](https://github.com/ZeusLN/zeus) is a Lightning wallet with Cashu ecash integration.

## Wallets - Nostr NIP-60/61 support
- [AFK](https://afk-community.xyz/app/cashu) is a community application with NIP-60 support.
- [Cashu Cache](https://github.com/robwoodgate/cashu-cache) lets you create (or update) a NIP-60 compliant Cashu Wallet and advertizes the NIP-61 public key so you can receive NutZaps. It also makes a wallet backup.
- [Cashu Gather](https://github.com/robwoodgate/nostrly/blob/main/src/js/nostrly-cashu-gather.ts) lets you receive NutZaps sent to your NIP-61 public key, creating a token per mint you can redeem with any wallet. [Site]( https://www.nostrly.com/cashu-gather/) 
- [chachi](https://github.com/purrgrammer/chachi) is a nostr group chat client with NIP-60 and NIP-61 support.
- [+chorus](https://github.com/andotherstuff/chorus) is a simple space for communities to gather, share, and support each other. It is built on the decentralized Nostr protocol and has an integrated Cashu wallet.
- [Clams](https://clams.tech/) is a Personal Finance and Business Analytics application that has a Cashu NIP-60 connection.
- [Highlighter](https://github.com/pablof7z/highlighter)
- [Iris](https://github.com/irislib/iris-messenger) is a Nostr Android, iOS and web client that also has a standalone desktop app and a Cashu wallet.
- [Learn civics](https://civico.app) is a civics citizenship app that has NIP-60 and NIP-61 support.
- [lnw.cash](https://github.com/AlbiziaLebbeck/lnwCash), [Site](https://lnw.cash/)
- [nutlife.lol](https://nutlife.lol/) 
- [Nutsack](https://github.com/pablof7z/nutsack), [Site](https://github.com/pablof7z/nutsack)
- [nuts.cash](https://www.nuts.cash/)
- [Olas](https://github.com/pablof7z/olas) is an Instagram-like Nostr Client that supports NIP-60/61 (nutzaps/wallet), uses [nutsack](https://nutsack.me/).
- [Shopstr](https://github.com/shopstr-eng/shopstr) has a built-in Cashu wallet for payments that has several features and uses the [cashu-ts](https://github.com/cashubtc/cashu-ts) library.
- [sixty-nuts](https://github.com/shroominic/sixty-nuts) is a lightweight NIP-60 Cashu Wallet in Python.

## Libraries

Cashu libraries allow developers to build wallets, mints, and other services that use Cashu.

#### C#
- [dotnut](https://github.com/Kukks/DotNut) is a C# library implementing the Cashu protocol.

#### Java

- [Cashu-JDK](https://github.com/d4rp4t/Cashu-JDK) is a minimal, stateless reimplementation of the Cashu protocol in Java.

#### Python

- [Nutshell](https://github.com/cashubtc/cashu) is a Python library for using Cashu wallets and mints inside other Python projects.

#### Rust

- [Cashu Development Kit(cdk)](https://github.com/cashubtc/cdk) is a Rust library implementing the Cashu protocol.
- [cdk-kotlin](https://github.com/cashubtc/cdk-kotlin) are Kotlin/Android language bindings for the Cashu Development Kit (cdk).
- [cdk-swift](https://github.com/cashubtc/cdk-swift) are Swift language bindings for the Cashu Development Kit (cdk).
- [cdk-python](https://github.com/cashubtc/cdk-python) are Python language bindings for the Cashu Development Kit (cdk). 
#### Swift
- [CashuSwift](https://github.com/zeugmaster/CashuSwift) is a Swift library implementing the Cashu protocol.
- [CashuKit](https://github.com/SparrowTek/CashuKit) is a Swift library implementing the Cashu protocol.

#### Svelte
- [Cyphertap](https://github.com/cypherflow/cyphertap) provides Nostr, Lightning & ecash in a single Svelte component.

#### TypeScript & JavaScript

- [cashu-ts](https://github.com/cashubtc/cashu-ts) is a TypeScript library for building Cashu wallets.
- [cashu-crypto-ts](https://github.com/cashubtc/cashu-crypto-ts) is a TypeScript library that implements basic crypto operations for Cashu wallets and mints.
- [Coco](https://github.com/cashubtc/coco) is a modular, TypeScript-first toolkit for building Cashu wallets and applications.
- [Cashu tools](https://github.com/gandlafbtc/cashu-tools) are advanced Cashu wallet tools based on cashu-ts in TypeScript.
- [blind-sig-js](https://github.com/supertestnet/blind-sig-js) is a JavaScript library implementing Cashu's blind signature mechanism.
- [cashu-wallet](https://github.com/ebrakke/cashu-wallet) is a framework-agnostic Cashu wallet written in TypeScript.

## Documentation Web Sites
Note: These documentation sites are works in progress (WIP) and welcome feedback and suggestions for content.
- [CDK](https://cashudevkit.org/) is a CDK doc site. [GitHub](https://github.com/cashubtc/cdk) for input/feedback.
- [CDK](https://ok300.github.io/cdk-docs/mint/03_systemd_service/) is a CDK doc site.
- [cashu-ts](https://cashu-ts.dev/) is a cashu-ts doc site.  
- [Mint Best Practices](https://findingsov.github.io/cashu-mint-docs/) is a mint best practices doc site. [GitHub](https://github.com/findingsov/cashu-mint-docs) for input/feedback.

## Tools

### Testnut Mints
- [https://testnut.cashu.space](https://testnut.cashu.space) is a testnut mint with fees with unbacked fake ecash for testing.  
- [https://nofee.testnut.cashu.space ](https://nofee.testnut.cashu.space) is a testnut mint with no fees with unbacked fake ecash for testing.  

### Mint Discovery and Audit
- [bitcoinmints](https://github.com/MakePrisms/bitcoinmints) is a list of ecash mints, supported NUTS, and reviews of the mints. [bitcoinmints.com](http://bitcoinmints.com) 
- [Cashumints.space](https://Cashumints.space) is an index of Cashu ecash mints and offers reviews of these mints, complete with comprehensive mint pages.
- [cashu-mint-status-board](https://github.com/shroominic/cashu-mint-status-board) is a mint status board. [cashu.live](https://cashu.live)
- [Mint Audit](https://audit.8333.space/) is a mint auditor and [Mint Watch Bot](https://primal.net/p/npub1cashu0thfukl57lgwtarn7h4jrzrg2e346zc8sjvjd8u5hheds0qlhpt92) is a bot that watches the status of mints.
### Restore 
- [Restore Tool-from seed](https://wallet.cashu.me/restore) is a tool that enables you to restore from a seed phrase.

### Token Decoders 
- [Cashu Decode](https://decode.8333.space/) - a v4 token decoder that lets you view and edit the tokens in real time.
- [Cashu decoder](https://github.com/nostrapps/cashu/) is a [web decoder](https://nostrapps.github.io/cashu) for Cashu v3 tokens.
- [Cashu decoder](https://nutcoder.netlify.app/) is a decoder for Cashu v3 and v4 tokens.

### Misc
- [Numbnoot](https://numbnoot.gandlaf.com) is a simulator for the Blind Diffie-Hellman Key Exchange scheme in used in Cashu.
- [Nutshell configurer]( https://celadon-semolina-91d112.netlify.app/) is a tool to set up the .env file for nutshell mints.

## Projects
### LLM Purchase
- [ChatNut](https://chatnut.sparkpay.pt/) is a privacy-preserving Chat application for large language models (LLMs) that users pay-per-request with an integrated Cashu wallet without having to create accounts.
- [Cypherflow](https://github.com/cypherflow/cypherflow_ai) is an application that provides private AI conversations powered by Cashu payments.
- [ecash OpenAI API client](https://github.com/9qeklajc/ecash-402-client) is a privacy-focused payment gateway that enables anonymous micropayments using Cashu ecash for accessing Large Language Models via the OpenAI API.
- [otrta-client](https://github.com/Routstr/otrta-client) is privacy-first AI payment system powered by e-cash technology. [Site](https://ecash.client.otrta.me/documentation/overview)
- [routstr](https://github.com/routstr) is a  marketplace to buy and sell LLM APIs using Cashu ecash tokens.

### LN Address Support
- [npubcash-server](https://github.com/cashubtc/npubcash-server) is a Lightning-Address provider for nostr pubkeys based on [Cashu-Address](https://github.com/lightning-digital-entertainment/cashu-address)
- [SatsContact](https://github.com/massmux/SatsContact) is a Lightning address provider that automatically generates @sats.contact Lightning addresses and real-time converts received amounts in Cashu tokens sent to the Telegram Chat.

### Messengers
- [0xChat](https://github.com/0xchat-app) 0xchat is a secure chat app built on the Nostr protocol with payments support using Cashu
- [KeyChat](https://github.com/keychat-io/keychat-app) Keychat is a chat app built on Cashu, Nostr and the Signal Protocol.


### P2PK Locked and Multi-Sig Tokens
- [Cashu NutLock](https://github.com/robwoodgate/nostrly/blob/main/src/js/nostrly-cashu-lock.ts) lets you lock a Cashu token to one or more public keys (Nostr NPUB or P2PK) for a set time. Supports complex multi-signature (multi-sig) tokens. [Site](https://www.nostrly.com/cashu-nutlock/) 
- [Cashu Witness](https://github.com/robwoodgate/nostrly/blob/main/src/js/nostrly-cashu-witness.ts) lets you unlock locked Cashu tokens by signing them with your private key (Nostr NSEC or P2PK). Supports multi-sig, and will show you whose signature(s) are required to unlock. [Site](https://www.nostrly.com/cashu-witness/)


### Redeem Tools
- [Cashu-redeem](https://cashu-redeem.vercel.app/) webtool allows you to redeem any Cashu token directly onto your Lightning wallet without having to receive it in a Cashu wallet [GitHub](https://github.com/cashubtc/cashu-redeem).
- [Cashu-redeem (newer)](https://redeem.cashu.me/) is a webtool that enables you to redeem Cashu v4 tokens and decode emojis to redeem Cashu tokens directly into your Lightning wallet.  It has support for bitcoin connect (NWC) and also stores change in localstorage. 
- [Nostrly Cashu Redeem](https://github.com/robwoodgate/cashu-redeem) is an updated version of [Redeem](https://redeem.cashu.me/) that uses latest [cashu-ts](https://github.com/cashubtc/cashu-ts), reads v4 tokens, emojis, and gives 'change'. [Site](https://www.nostrly.com/cashu-redeem/) 

### X-Cashu
- [Proxnut](https://github.com/gandlafbtc/proxnut)  forwards requests only if they have a valid cashu token attached to the X-Cashu header.
- [X-Cashu](https://github.com/callebtc/xcashu) is a work-in-progress project that aims to create a 402 Payment Required scheme to monetize REST API access by using ecash in HTTP headers.


### Various nutcases
- [agentecash](https://agentecashsdk.replit.app/) is a tool that uses private, instant ecash payments between autonomous AI agents.
- [Almandine](https://lab.oak-node.net/almandine) uses Athenut and is basic wrapper with a built-in CDK wallet.
- [Athenut](https://github.com/thesimplekid/athenut-frontend) is a tool to search smarter (Kagi-powered). Pay in sats. [Site](https://athenut.com/), [Github-Mint](https://github.com/thesimplekid/athenut-mint)
- [Bitcoin Skills](https://gitlab.com/lemonknowsall/bitcoin-skills/) ia a workflow for building Bitcoin, Lightning, and Cashu wallets through prompts and images, with a Claude Skills library.
- [bitpoints.me](https://github.com/bitpoints-cashu/bitpoints.me) is a Cashu Ecash Wallet with Bluetooth mesh networking and Nostr integration.
- [BTCNutServer](https://github.com/d4rp4t/BTCNutServer?mc_cid=bf3feffb71) is a new experimental plugin to bring ecash payments to BTCPay Server.
- [bullishNuts](https://github.com/thebullishbitcoiner/bullishnuts) is an ecash wallet in early beta phase.
- [S-two Cairo Demo](https://stwo-cairo.vercel.app/) is bringing zero-knowledge proofs to Cashu. Github repos: [stwo-cairo](https://github.com/starkware-libs/stwo-cairo) and [stwo-cairo-ts](https://github.com/clealabs/stwo-cairo-ts)
- [Cashu Bonds](https://github.com/lescuer97/nut-bond) is a simple proof of concept of identity bonds using Cashu.
- [Cashu-brrr](https://github.com/gandlafbtc/cashu-brrr/) is a Cashu ecash printer. [Site](https://brrr.gandlaf.com) 
- [Cashu Casino](https://github.com/babdbtc/cashucasino) is a privacy-focused online casino powered by Cashu ecash.
- [cashu-kym](https://github.com/Egge21M/cashu-kym) is used to discover and score Cashu mints.
- [cashu-pos](https://github.com/babdbtc/cashu-pos) is a self-hostable POS app built with Expo for accepting Cashu payments via NFC tap-to-pay and Lightning invoices.
- [Cashucards](https://github.com/Marc26z/CashuCards) are greeting cards that give Bitcoin using the Cashu protocol.
- [Cashu for Community Sovereignty](https://github.com/cashu4community) provides private and censorship resistant payment systems for communities under authoritarian regimes. [Site](http://cashu4community.xyz)
- [Cashu for WooCommerce](https://github.com/robwoodgate/cashu-for-woocommerce) adds a secure Cashu payment gateway to your WooCommerce store.
- [Cashu MLS Chat](https://github.com/SatsAndSports/cashu_mls_chat) is a a web-based application combining MDK (Marmot Development Kit) for encrypted group messaging with Cashu (CDK) for ecash wallet functionality.
- [Cashu Monopoly](https://github.com/bTCpy/monopoly/) is classic Monopoly, but the money is real Bitcoin. Buy in with Lightning, pot held in a Cashu wallet, winner takes the sats.
- [Cashu Pay Server](https://github.com/jooray/cashupayserver) accepts Bitcoin Lightning payments without running a full BTCPay Server instance. [Site](https://cashupayserver.org)
- [CashuProjects](https://github.com/CashuProjects) is a collection of TypeScript projects.
- [CDK Spark Payment Processor](https://github.com/thesimplekid/cdk-spark-payment-processor) is a gRPC-based Lightning Network payment processor that implements the CDK payment processor protocol using the Breez SDK Spark.
- [cashu-escrow-kit](https://github.com/f321x/cashu-escrow-kit) is an ecash escrow provider and client concept.
- [Cashu LoRa Bridge](https://github.com/Silexperience210/cashu-lora-bridge) is a gateway server that enables offline Bitcoin transactions via LoRa radio networks.
- [cashu.me.extension](https://github.com/Kelbie/cashu.me.extension) is a Cashu.me wrapper that allows you to use your Cashu.me ecash and manage functionality related to it including sending and receiving.        [Chrome extension](https://chromewebstore.google.com/detail/cashume/adfafhcbnbehkgpkfgpbgagkjlddkohj) and [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/cashu-me/).
- [chessu.cash](https://chessu.cash/) is a game where you can solve chess puzzles and earn Cashu ecash.
- [classu](https://github.com/inscrib3/classu.cash) is an educational platform fully dedicated to Cashu. [Site](https://classu.cash)
- [CLN mint plugin](https://github.com/gudnuf/cln_pyshu_mint) is a work-in-progress CLN plugin for running a mint on your own node.
- [deez-cashus](https://github.com/ngmisl/deez-cashus) is a production-ready demonstration of HTTP 402 (Payment Required) using Cashu for privacy-preserving Bitcoin-backed micropayments.
- [EchoCash](https://github.com/Harshdev098/EchoCash) is a P2P communication and payment platform using WebRTC and WebSockets for decentralized value transfer via Fedimint and Cashu.
- [Hashpool](https://github.com/vnprc/hashpool) is an accountless mining pool that uses ecash to represent mining shares.
- [Hide a message in an emoji](https://github.com/paulgb/emoji-encoder) is a [Site](https://emoji.paulbutler.org) that allows you to hide ecash in an emoji.
- [Layer3 Press](https://layer3.press/welcome) is an unstoppable publishing service that allows people to easily receive Bitcoin, Lightning and Cashu subscription payments with a built-in Coinos wallet.
- [lnuts](https://gitworkshop.dev/npub1dfedhrhn7wu7uhkdsz8dd5rrr50ymkjutkklq7y8zpxn89t7hfyqfzlc7u/relay.ngit.dev/lnuts) is a full Nostr-ready LNURL-pay server that bridges Lightning payments to Cashu tokens.
- [mcp-money](https://github.com/pablof7z/mcp-money) is an MCP (Model Context Protocol) money implementation for Nostr using NDK (Nostr Development Kit) with Cashu ecash functionality.
- [Meme amigo](https://memeamigo.lol/) enables you to hide ecash in a meme.
- [Morning Glory](https://github.com/hzrd149/morning-glory) is a paid blossom server that only stores blobs for a day.
- [ngx_l402](https://github.com/DhananjayPurohit/ngx_l402) is an L402 authentication module/plugin for Nginx that integrates seamlessly into your web server.
- [nostr.blue](https://github.com/patrickulrich/nostr.blue) ia a full-featured Nostr social client with a built-in NIP-60 Cashu wallet, compiled to WebAssembly using CDK.
- [nostrpay](https://github.com/Unit-Matrix/nostrpay) is a child-friendly learning app with offline-first Cashu payments built into an educational environment.
- [Numo](https://github.com/cashubtc/Numo) is an Android Point-of-Sale application that enables merchants to receive Cashu ecash payments via tap-2-pay.
- [nutoff-wallet](https://github.com/gzuuus/nutoff-wallet) is a command-line interface and MCP server interface implementing a Cashu wallet.
- [Nutband](https://github.com/jooray/nutband) aims to use Cashu payments over long range radio and other mesh networks using Reticulum and LXMF.
- [Nutshell in Azure TEE](https://github.com/aljazceru/nutshell-azure-tee) is a Cashu mint running in confidential containers (Azure TEE).
- [Nuts are Pure Signal](https://github.com/swedishfrenchpress/bitcoinforsignal) is a bitcoin for Signal hackathon project winner.
- [Obfusats](https://devpost.com/software/obfusats) is a hackathon project that takes a stack of sats, splits and routes through a couple of Cashu mints before merging again. 
- [Openpleb](https://github.com/gandlafbtc/open-pleb) is a platform for matching users that want to pay a banking QR with bitcoin, and earners that want to earn bitcoin for paying the users offers.
- [OnChainDiscGolf](https://github.com/OnChainDiscGolf/app) is a disc golf scorecard app with integrated Bitcoin payments via Cashu ecash.
- [Orchard](https://github.com/orangeshyguy21/orchard) is a Bitcoin super application that has Cashu mint monitoring.
- [Paywally](https://github.com/bordalix/paywally) is a Lightning paywall powered by Cashu.
- [Portal Technologies](https://github.com/PortalTechnologiesInc) is a universal app for identity & payments.
- [Purrwallet](https://github.com/heathermm55/purrwallet) is a cross-platform Cashu ecash wallet built with Rust and Flutter, featuring a terminal-inspired UI for privacy-focused Bitcoiners.
- [Receipt.cash](https://github.com/Origami74/receipt-cash) is a bill splitter to snap a picture of a fiat bill and easily split costs auto-converted to Bitcoin. It's based on Cashu payment requests. [Site](https://sugardaddy.cash/)
- [Satocash-Applet](https://github.com/Toporin/Satocash-Applet) is an ecash wallet implementation in javacard.
- [sig4sats](https://github.com/vstabile/sig4sats-script) is a a simple script demonstrating how to atomically exchange Cashu payments for Nostr event signatures using Schnorr adaptor signatures.
- [Spacenut](https://github.com/gandlafbtc/spacenut) is the sickest Cashu-enabled game you've ever played. [Site](https://spacenut.nutstash.app)
- [Spark Payment processor](https://github.com/thesimplekid/cdk-spark-payment-prcoessor) is a gRPC-based Lightning Network payment processor that implements the CDK payment processor protocol using the Breez SDK Spark.
- [Taskify](https://github.com/Solife-me/Taskify_Release) is a clean, powerful to-do app where tasks can carry Cashu bounties.
- [The Nutty Pill](https://github.com/MonkeyDGigi/The_Nutty_Pill) is an educational application that gamifies Bitcoin learning with a Cashu.me wallet.
- [Tollgate](https://github.com/OpenTollGate/tollgate-app) turns any WiFi router into a decentralized ISP using bitcoin and ecash.
- [Wally](https://github.com/Origami74/wally) allows your device to discover and (auto)connect to TollGates around you. Implements Cashu Wallet Connect (CWC), an extension of NIP-47 (Nostr Wallet Connect) that enables applications to interact with Cashu ecash wallets over Nostr.
- [Wrapnuts](https://github.com/wrapnuts/wrapnuts/tree/main) is a CLI developed for embedding Cashu ecash into files with the help of steganography.
- [402.markets](https://github.com/Kelbie/402.markets) is an API marketplace powered by Lightning Network and Cashu tokens. [Site](https://402.markets/) 
## Currently Unmaintained Projects

- [Cashcrab](https://github.com/thesimplekid/cashcrab) is a Cashu wallet with a flutter UI and with as much logic as possible in rust using [cashu-crab](https://github.com/thesimplekid/cashu-crab) with nostr integration for contacts and messaging.
- [cashu-client](https://github.com/thunderbiscuit/cashu-client) is a Cashu client library in Kotlin.
- [cashu-bdhke-kmp](https://github.com/gandlafbtc/cashu-bdhke-kmp) is a Kotlin library that implements the basic cryptographic blinded signature scheme.
- [cashu-feni](https://github.com/cashubtc/cashu-feni) is a Golang library for Cashu wallets and mints.
- [Cashubrew](https://github.com/AbdelStark/gakimint) is a Cashu mint written in Elixir.
- [Cashu faucet](https://github.com/gandlafbtc/cashu-faucet) allows you to deposit and withdraw Cashu tokens from a web interface. [Site](https://www.gandlaf.com/faucet/anarchy)
- [Chamberlain](https://github.com/sovereign-app/chamberlain) is a mint implementation with an Integrated LDK Node using CDK.
- [Coconut](https://github.com/zig-bitcoin/coconut) is a Cashu mint written in Zig.
- [Cashu-dart](https://github.com/0xchat-app/cashu-dart) is another Library that allows developers to integrate Cashu easily into apps 
- [eNuts](https://github.com/cashubtc/eNuts) is a Cashu wallet for Android and IOS. It empowers you with a user-friendly interface that streamlines every step of your ecash journey.
- [Moksha](https://github.com/ngutech21/moksha) is a Cashu wallet and mint written in Rust.

