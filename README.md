# Awesome ICP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<a align="center" href="https://internetcomputer.org/">
  <img src="assets/dfinity-logo.png">
</a>

> A curated list of awesome projects and resources relating to [DFINITY](https://dfinity.org) and the Internet Computer.

The [Internet Computer](https://internetcomputer.org/) is a public blockchain that hosts smart contracts that run at web speed, can serve web from cyberspace, run efficiently, and can scale within an environment that has unbounded capacity. Smart contracts are a profoundly new and superior form of tamperproof and unstoppable software. They can imbue systems and services with new properties, enabling the reimagination of websites, systems, internet services and finance.

---

## Contents

- [Awesome ICP ](#awesome-icp-)
  - [Contents](#contents)
  - [Client Libraries (Agents)](#client-libraries-agents)
    - [JavaScript/TypeScript](#javascripttypescript)
    - [Rust](#rust)
    - [Python](#python)
    - [Dart/Flutter](#dartflutter)
    - [Go](#go)
    - [C#](#c)
    - [Java](#java)
  - [Canister Development Kits (CDKs)](#canister-development-kits-cdks)
    - [Motoko](#motoko)
    - [Rust](#rust-1)
    - [JavaScript/TypeScript](#javascripttypescript-1)
    - [Python](#python-1)
    - [C/C++](#cc)
    - [AssemblyScript](#assemblyscript)
  - [Developer Tooling](#developer-tooling)
    - [Testing](#testing)
    - [CI/CD](#cicd)
    - [Monitoring](#monitoring)
  - [Motoko](#motoko-1)
    - [Package Managers](#package-managers)
  - [Candid](#candid)
    - [Candid implementations](#candid-implementations)
      - [AssemblyScript](#assemblyscript-1)
      - [C#](#c-1)
      - [Dart](#dart)
      - [Elm](#elm)
      - [Haskell](#haskell)
      - [Java](#java-1)
      - [JavaScript/TypeScript](#javascripttypescript-2)
      - [Kotlin](#kotlin)
      - [Motoko](#motoko-2)
  - [Storage and Databases](#storage-and-databases)
  - [Fungible and Non-fungible Tokens (NFTs)](#fungible-and-non-fungible-tokens-nfts)
    - [Interface Standards](#interface-standards)
      - [ICRC](#icrc)
      - [Other Interface Standards](#other-interface-standards)
  - [DAO Frameworks](#dao-frameworks)
  - [Game Development](#game-development)
  - [Wallets and Authentication](#wallets-and-authentication)
    - [Libraries](#libraries)
  - [Dashboards, Explorers and Registries](#dashboards-explorers-and-registries)
  - [Crosschain Interoperability](#crosschain-interoperability)
  - [Starters](#starters)
  - [Blogs](#blogs)
  - [Courses, Tutorials and Samples](#courses-tutorials-and-samples)
    - [Courses](#courses)
    - [Tutorials and Samples](#tutorials-and-samples)
  - [How it works / Deep dives](#how-it-works--deep-dives)
  - [Communities and Communication](#communities-and-communication)
  - [Bounties and Grants](#bounties-and-grants)

## Client Libraries (Agents)

Agents facilitate the interaction from clients with canisters on the Internet Computer. If you want to contribute an agent implementation checkout out this [Grant RFP](https://github.com/dfinity/grant-rfps/issues/4).

### JavaScript/TypeScript

- [agent-js](https://github.com/dfinity/agent-js) - Collection of libraries to interact with the IC using JavaScript.
- [ic-js](https://github.com/dfinity/ic-js) - Collection of libraries for interfacing with core canisters on the Network Nervous System (NNS).
- [icblast](https://github.com/infu/icblast) - Communicate with IC directly using NodeJS. Automatic service discovery.
- [node-ic0](https://github.com/dfinity/node-ic0) - The ic0 package is a simple, straightforward way to interact with canisters running on the IC.

### Rust

- [agent-rs](https://github.com/dfinity/agent-rs) - Collection of libraries and tools for interfacing with the IC using Rust.
- [dfx](https://github.com/dfinity/sdk) - Commandline tool to interact with the IC written in Rust.

### Python

- [ic-py](https://github.com/rocklabs-io/ic-py) - Library for interfacing with the IC using Python.

### Dart/Flutter

- [agent_dart](https://github.com/AstroxNetwork/agent_dart) - Framework to build mobile applications.
- [ic_dart_tools](https://github.com/levifeldman/ic_tools_dart) - Tools supporting Flutter on the web.

### Go

- [agent-go](https://github.com/aviate-labs/agent-go) - Libraries for interfacing with the IC using Go.
- [ic-go](https://github.com/mix-labs/IC-Go) - Libraries for interfacing with the IC using Go.

### C#

- [agent-unity](https://github.com/ShikuLabs/agent-unity) - Wrapper of agent-rs to be used in unity projects.
- [ICP.NET](https://github.com/edjCase/ICP.NET) - Native Implementation in C# (Unity compatible).

### Java

- [ic4j-agent](https://github.com/ic4j/ic4j-agent) - Libraries for interfacing with the IC using Java (Android compatible).

## Canister Development Kits (CDKs)

- [CDK Framework](https://github.com/demergent-labs/cdk_framework) - Framework to build CDKs which has been used for Azle and Kybra.

### Motoko

- [Motoko](#Motoko) - Simple high-level language for writing canisters.

### Rust

- [canister-sdk](https://github.com/infinity-swap/canister-sdk) - SDK for writing and testing canisters for the Internet Computer in Rust.
- [ic-cdk](https://crates.io/crates/ic-cdk) - Rust CDK maintained by DFINITY

### JavaScript/TypeScript

- [Azle](https://github.com/demergent-labs/azle) - TypeScript CDK.

### Python

- [Kybra](https://github.com/demergent-labs/kybra) - Python CDK.

### C/C++

- [Chico](https://github.com/ICPorts-labs/chico) - C/C++ CDK.
- [icpp](https://github.com/icppWorld/icpp) - Modern C++ for the IC.

### AssemblyScript

- [cdk-as](https://github.com/rckprtr/cdk-as) - AssemblyScript CDK.


## Developer Tooling

- [Developer Tooling Landing page](https://internetcomputer.org/tooling) - Overview of tooling in the Internet Computer ecosystem.
- [IC Inspector](https://chrome.google.com/webstore/detail/ic-inspector/meaadkenfkhjakkkdapaallimhbdofck) - Chrome extension to decode IC requests and responses.
- [ic-nix](https://github.com/ninegua/ic-nix) - Build IC projects with Nix.

### Testing

- [canister-profiling](https://github.com/dfinity/canister-profiling) - Code & scripts for collecting performance data for canisters.
- [ic-repl](https://github.com/chenyan2002/ic-repl) - A REPL environment to communicate with canisters. Allows to write E2E integration tests

### CI/CD

- [ICPipeline](https://www.icpipeline.com/) - CI/CD framework to simply IC release management.

### Monitoring

- [Canistergeek](https://cusyh-iyaaa-aaaah-qcpba-cai.raw.ic0.app/) - Open-source tool to track your project canisters cycles and memory status.
- [Canister monitoring](https://github.com/domwoe/canister-monitoring) - Example of using Prometheus to collect metrics from a canister.
- [ic-blackhole](https://github.com/ninegua/ic-blackhole) - Canister to publicly expose canister status information.
- [Metrics encoder](https://lib.rs/crates/ic-metrics-encoder) - Library to encode metrics in Prometheus text exposition format.

## Motoko

Motoko is a safe, simple, actor-based programming language for authoring Internet Computer (IC) canister smart contracts.

- [Awesome Motoko](https://github.com/motoko-unofficial/awesome-motoko) - Awesome list focused on Motoko.
- [Blocks](https://github.com/Blocks-Editor/blocks) - Online low-code editor for Motoko.
- [Embed Motoko](https://embed.smartcontracts.org/) - Embed an interactive Motoko code snippet on your website.
- [Motoko Formatter](https://github.com/dfinity/prettier-plugin-motoko) - A configurable Prettier plugin for Motoko.
- [Motoko GitHub Repository](https://github.com/dfinity/motoko) - The home of the Motoko language.
- [Motoko Playground](https://m7sm4-2iaaa-aaaab-qabra-cai.ic0.app/) - An online playground environment for Motoko.
- [Motoko VS code](https://marketplace.visualstudio.com/items?itemName=dfinity-foundation.vscode-motoko) - Motoko language support for Visual Studio Code.
- [Motoko.js](https://www.npmjs.com/package/motoko) - Compile and run Motoko in Node.js and the browser.

### Package Managers

- [MOPS](https://mops.one/) - Package manager for Motoko with fully on-chain package registry.
- [Vessel](https://github.com/dfinity/vessel) - Package manager for the Motoko programming language.

## Candid

Candid is an interface description language (IDL) for interacting with canisters (also known as services or actors) running on the Internet Computer. It provides a language-independent description of canister interfaces and the data they exchange, with type safety and extensibility.

- [Candid GitHub Repo](https://github.com/dfinity/candid) - The home of Candid
- [Candid UI](https://github.com/dfinity/candid/blob/master/tools/ui) - Canister generates a front-end UI for any canister.
- [didc](https://github.com/dfinity/candid/tree/master/tools/didc) - A multi-purpose tool for Candid.
- [idl2json](https://github.com/dfinity/idl2json) - Command line tool for converting Candid to JSON.
- [Intellij Candid Plugin](https://github.com/Alaanor/candid-intellij-plugin) - A Candid language plugin for editing .did files.

### Candid implementations

#### AssemblyScript

- [cdk-as candid](https://github.com/rckprtr/cdk-as/tree/master/packages/cdk/assembly/candid) - AssemblyScript library of Candid.

#### C#

- [ICP.NET candid](https://github.com/edjCase/ICP.NET/tree/main/src/Candid) - C# library of Candid. 

#### Dart

- [candid_dart](https://github.com/AstroxNetwork/candid_dart) - Dart library of Candid. 
- [ic_tools_dart](https://github.com/levifeldman/ic_tools_dart) - Dart library of Candid. 

#### Elm

- [ic-elm](https://github.com/chenyan2002/ic-elm/) - A template for using Elm to develop frontend user interface for the Internet Computer.

#### Haskell

- [haskell-candid](https://github.com/nomeata/haskell-candid) - Haskell library for Candid to Haskell.

#### Java

- [ic4j-candid](https://github.com/ic4j/ic4j-candid) - Java library for Candid.

#### JavaScript/TypeScript

- [@dfinity/candid](https://github.com/dfinity/agent-js/tree/main/packages/candid) - JavaScript and TypeScript library for Candid.

#### Kotlin

- [candid-kt](https://github.com/seniorjoinu/candid-kt) - Kotlin library for Candid.

#### Motoko

- [motoko_candid](https://github.com/edjcase/motoko_candid) - Library that enables encoding/decoding of bytes to candid values.

## Storage and Databases

- [CanDB](https://www.canscale.dev/) - Flexible, performant, and horizontally scalable non-relational multi-canister database built in Motoko.
- [ic-sqlite](https://github.com/froghub-io/ic-sqlite) - SQLite on the IC.
- [ic-stable-memory](https://github.com/seniorjoinu/ic-stable-memory) - Stable memory collections for Rust.
- [stable-structures](https://github.com/dfinity/stable-structures) - A collection of scalable and upgrade-safe data structures for Rust maintained by DFINITY.
- [Sudograph](https://github.com/sudograph/sudograph) - A GraphQL database for the IC.

## Fungible and Non-fungible Tokens (NFTs)

### Interface Standards

#### ICRC

- [ICRC-1](https://github.com/dfinity/ICRC-1/blob/main/standards/ICRC-1/README.md) - Base fungible token standard. 
- [ICRC-2](https://github.com/dfinity/ICRC-1/blob/main/standards/ICRC-2/README.md) - Extension to support `approve` and `transfer_from`.

#### Other Interface Standards

- [DIP20](https://github.com/Psychedelic/DIP20) - Fungible token standard inspired by the ERC20 standard.
- [DIP721](https://github.com/Psychedelic/DIP721) - NFT standard inspired the ERC721 standard.
- [EXT](https://github.com/Toniq-Labs/extendable-token) - The extendable token standard inspired by ERC1155.
- [Origyn NFT](https://github.com/origyn-sa/origyn_nft) - Origyn NFT standard.

## DAO Frameworks

- [Axon](https://github.com/icdevs/axon) - A multi-user, multi-neuron management canister. 
- [Service Nervous System](https://internetcomputer.org/sns) - Framework inspired by the Network Nervous System.

## Game Development

For Unity-compatible client libraries, see [C# agents](#C#).

- [WebGL Sample](https://internetcomputer.org/docs/current/samples/host-a-webgame) - Example of how to host a WebGL game on the IC. 

## Wallets and Authentication

- [AstroX Me](https://astrox.me/#/) - Canister-based mobile/web multi-chain wallet.
- [Bitfinity](https://wallet.infinityswap.one/) - Chrome extension. 
- [Internet Identity](https://github.com/dfinity/internet-identity) - Pseudoymous authentication system for the Internet Computer.
- [NFID](https://nfid.one/) - Digital identity for signing in to applications privately and securely.
- [NNS Dapp](https://nns.ic0.app/) - Stake ICP in neurons, participate in governance and decentralization sales.
- [Plug](https://plugwallet.ooo/) - Chrome extension and mobile wallet.
- [Stoic](https://www.stoicwallet.com/) - Web wallet.

### Libraries

- [connect2ic](https://connect2ic.github.io/docs/) - A frontend auth library & toolkit for the Internet Computer. 

## Dashboards, Explorers and Registries

- [Canlista](https://k7gat-daaaa-aaaae-qaahq-cai.ic0.app/) - Canister registry.
- [Cyql](https://n7ib3-4qaaa-aaaai-qagnq-cai.raw.ic0.app/) - Curated project registry.
- [ICLighthouse Explorer](https://637g5-siaaa-aaaaj-aasja-cai.raw.ic0.app/) - Explorer.
- [ICSCAN](https://icscan.io/) - Explorer.
- [Internet Computer Dashboard](https://dashboard.internetcomputer.org/) - Live stats and explorer.
- [Internet Computer Ecosystem Showcase](https://internetcomputer.org/ecosystem) - Curated project registry.
- [Kinic](https://74iy7-xqaaa-aaaaf-qagra-cai.ic0.app/) - Front-end search engine.

## Crosschain Interoperability

- [Bitcoin Integration](https://internetcomputer.org/bitcoin-integration) - Landing page of the direct integration with the Bitcoin network.
- [Chain-key ECDSA](https://internetcomputer.org/how-it-works/threshold-ecdsa-signing/) - Tech that allows creating transactions targeting various chains from canisters on the Internet Computer.
- [No key wallet](https://github.com/nikolas-con/ic-evm-sign-starter) - Example project of a canister-based Ethereum wallet.
- [Omnic](https://github.com/rocklabs-io/omnic) - Cross-chain messaging protocol to connect EVM-compatible chains via the Internet Computer.
- [Orally](https://github.com/orally-network/oracle) - Cross-chain oracle factory built on HTTPS Outcalls and Chain-key ECDSA.
- [Terabethia](https://terabethia.ooo/) - Bridge and communication protocol between Ethereum and the Interner Computer.

## Starters

- [create-ic](https://github.com/peterpeterparker/create-ic) - A simple command line tool to quickly create projects for the IC.
- [create-ic-app](https://github.com/MioQuispe/create-ic-app) -  Modern, unopinionated templates for React, Vue & Svelte powered by [Vite](https://vitejs.dev/).
- [ic-rust-starter](https://github.com/ocluf/ic-rust-starter) - Starter for a Rust backend-only canister project.
- [vite-react-motoko](https://github.com/rvanasa/vite-react-motoko) - Full-Stack React/Motoko starter with live reload.

## Blogs

- [B.Lynnity](https://fxa77-fiaaa-aaaae-aaana-cai.raw.ic0.app/) - Ben Lynn's Blog about development on the IC using C.
- [David dal Busco's blog](https://daviddalbusco.com/blog/) - Blog with many hands-on articles on IC development.
- [ICP Analysis](https://kylelangham.substack.com/) - Kyle Langham's writings about data analysis on the IC ecosystem.
- [Joachim Breitner's blog](https://www.joachim-breitner.de/blog/tag/Internet_Computer) - Articles on IC development and Candid.
- [Kyle Peacocks's blog](https://kyle-peacock.com/blog/) - Notes on IC development and more.
- [mmapped](https://mmapped.blog/) - Roman Kashitsyn's blog about IC internals and development.

## Courses, Tutorials and Samples

### Courses

- [Motoko Bootcamp #1](https://github.com/motoko-bootcamp/bootcamp-2022) - Lectures and materials for the first Motoko Bootcamp in 2022.
- [Motoko Bootcamp #2](https://github.com/motoko-bootcamp/motokobootcamp-2023) - Lectures and materials for the second Motoko Bootcamp in 2023.
- [The Complete Web Development Bootcamp](https://www.udemy.com/course/the-complete-web-development-bootcamp/) - Udemy course with a complete section on web3 development using the Internet Computer.
- [Web3, Blockchain and the Internet Computer](https://www.youtube.com/playlist?list=PLSzsOkUDsvdubXF5XGGPffyQJ5CVU_9_c) - Youtube series (excerpt from The Complete Web Development Bootcamp).

### Tutorials and Samples

- [Access control on the Internet Computer](https://github.com/domwoe/access_control).
- [Backup and Restore of Data on the Internet Computer](https://github.com/Factland/ic-factland/blob/main/backup/backup_restore.md).
- [Canister guard in Rust on the Internet Computer](https://medium.com/@daviddalbusco/canister-guard-in-rust-on-the-internet-computer-c896f75e0cef).
- [Considerations for NFT Developers](https://internetcomputer.org/docs/current/developer-docs/best-practices/considerations-for-nft-devs).
- [Hosting ERC 721 metadata on the IC](https://github.com/domwoe/erc-721-ic-assets).
- [How to Configure Dapps for Social Platform Previews and SEO](https://medium.com/dfinity/how-to-configure-dapps-for-social-platform-previews-and-seo-62a55ee63d33).
- [How to Migrate Canister Smart Contracts from Motoko to Rust](https://medium.com/dfinity/how-to-migrate-canister-smart-contracts-from-motoko-to-rust-3446a4b0c2ff).
- [How to programmatically convert ICP into Cycles in NodeJS](https://medium.com/dfinity/converting-icp-into-cycles-javascript-9b0dba8d8e00).
- [Internet Computer Sample Dapps](https://internetcomputer.org/samples) - DFINITY-maintained and community-contributed samples and tutorials.
- [Rust + React (Typescript) + Internet Identity on the Internet Computer](https://medium.com/@ilbert/rust-react-typescript-internet-identity-on-the-internet-computer-35331ae2a4be).
- [Video: Code Native Bitcoin](https://www.youtube.com/watch?v=LGegOFqP5x0) [(2nd part)](https://www.youtube.com/watch?v=H6Wu9n9Qwa8) - Video tutorial on how to use the native Bitcoin integration.
- [Video: Coding with Kyle | Make Oracles Obsolete in under 5 Minutes](https://www.youtube.com/watch?v=3e12N9mcWhw).
- [Video: Deploy Your First dApp on the IC in 10 Minutes!](https://www.youtube.com/watch?v=r5s7nD_XO0M). 
- [Video: Frontends on the Internet Computer](https://www.youtube.com/watch?v=rjSDvTaEj3s).
- [Video: Intro to Building on the Internet Computer](https://www.youtube.com/watch?v=fSO___x3e3I). 
- [Video: Uploading and Serving Images on the IC](https://www.youtube.com/watch?v=0O4M0W47KKA).
- [Which Language Should You Choose To Build on the Internet Computer?](https://medium.com/code-state/which-language-should-you-choose-to-build-on-the-internet-computer-%EF%B8%8F-851c31e9c28).
- [Working with Environments on the Internet Computer](https://medium.com/@Catalyze.One/working-with-environments-on-the-internet-computer-59ed3d2a5763).

## How it works / Deep dives

- [Internet Computer for Geeks](https://internetcomputer.org/whitepaper.pdf) - Whitepaper written by the DFINITY team.
- [Internet Computer Wiki](https://wiki.internetcomputer.org/wiki/Internet_Computer_wiki) - General knowledge resource about the Internet Computer.
- [How it works](https://internetcomputer.org/how-it-works) - Learn how the IC realizes the vision of the World Computer.

## Communities and Communication

- [DFINITY Developer Forum](https://forum.dfinity.org/) - Main forum about the Internet Computer.
- [IC Developer Community Discord](https://discord.gg/jnjVVQaE2C) - Developer-oriented community Discord.
- [ICP Discord](https://discord.gg/FygMb5VyCQ) - Multi-language server for the broader community.
- [ICP League](https://qbw7d-giaaa-aaaaj-aalta-cai.ic0.app/) - Fostering world-class community for Internet Computer Ecosystem.
- [Internet Computer Academy](https://internetcomputer.academy/) - Open-source and community-driven knowledge base about the IC.

## Bounties and Grants

- [DFINITY Developer Grants and Bounties](http://dfinity.org/grants) / [Requests and Discussions](https://github.com/dfinity/grant-rfps/discussions).
- [ICDevs Bounties](https://icdevs.org/bounties.html).
- [Video: Overview of the Developer Grants Program](https://www.youtube.com/watch?v=hoYo-c9SMfQ).
