# Gitcoin-GR11-Hackathon

Welcome to the Gitcoin GR11 hackathon. We are excited to join you in pushing the Web3 envelope over the next six days and we are looking forward to support you in turning your ideas into decentralized realities.

## About Fluence

Fluence provides the infrastructure and tools to enable decentralized compute for applications and backends on peer-to-peer networks. Nodes in the the Fluence peer-to-peer network host content-addressable services comprised of WebAssembly Interface Types (IT) modules. Aqua, Fluence's purpose-built distribute systems programming language, allows developers to seamlessly program distributed networks and compose hosted services into decentralized applications. As as result, the Fluence platform allows you to bring peer-to-peer compute to a variety of Web3 use cases including data storage, blockchains, identity and to develop custom hosted services and workflows using the Fluence stack.

## The Prizes

### Beginner Bounty -- USD 250 x the first 10 people:
Extend the Fluence Quickstart, https://github.com/fluencelabs/examples/tree/main/quickstart/3-browser-to-service, with a distributed character count service deployed to at least one Fluence peer. Display a message's character count at the end of the message, e.g., (char count: 123 chars). Document your solution and submit it via a Github or GitLab repo with MIT or Apache 2.0 license.

### Intermediate Bounties -- USD 2,500 each:
* Build a performant explorer for the Fluence network with Fluence services, Aqua-based composition, IPFS (hot/cache) storage and a Web-framework of your choice. The explorer should allow users to query the network at least by service id and  blueprint id by peer. A graphical and even animated representation of the network would definitely score extra points. For info concerning the current explorer see https://github.com/fluencelabs/dashboard. Document your solution and provide a max three (3) minute video presenting and demonstration your solutions and submit via a Github or GitLab repo with MIT or Apache 2.0 license.
* Port or implement an Ethereum signature signing and verification service as Wasm IT modules  and provide Aqua  workflows at least for sign and verify functionalities. For inspiration, see for example https://crates.io/crates/ethereum-tx-sign or https://crates.io/crates/ethsign. Document your solution and provide a max three (3) minute video presenting and demonstration your solutions and submit via a Github or GitLab repo with MIT or Apache 2.0 license.
* Implement and deploy Wasm IT modules to create, manage or verify Decentralized Identity (DID) or Verifiable Credentials (VC) documents and associated linked data. An implementation using BBS+, see https://w3c-ccg.github.io/ldp-bbs2020/, would score a lot of goodwill. Document your solution and provide a max three (3) minute video presenting and demonstration your solutions and submit via a Github or GitLab repo with MIT or Apache 2.0 license.
* Create a Ceramix, https://ceramic.network/, Wasm IT adapter with Marine that provides bindings for both the complete CLI, https://developers.ceramic.network/build/cli/api/, and HTTP, https://developers.ceramic.network/build/http/api/,  APIs. Provide Aqua workflows for at least the 'create', 'update' and 'query` methods. Document your solution and provide a max three (3) minute video presenting and demonstration your solutions and submit via a Github or GitLab repo with MIT or Apache 2.0 license.

### Advanced Bounty -- USD 5000:
Implement an Aqua "playground", i.e. a browser-based development and execution environment for Aqua scripts.
The minimum acceptable submission should provide the following features and run on at least one of Firefox or Chrome:
* Syntax highlighting
* All examples listed in Aqua examples (see below) need to run
* Document your solution and provide a max five (5) minute video presenting and demonstration your solutions and submit via a Github or GitLab repo with MIT or Apache 2.0 license.

Have a look at the following resources:
* Aqua JS compiler: https://github.com/fluencelabs/aqua
* Aqua standard library: https://github.com/fluencelabs/aqua-lib
* JS SDK: https://github.com/fluencelabs/fluence-js
* Aqua examples: https://github.com/fluencelabs/aqua-playground
* Syntax highlighting: https://github.com/fluencelabs/aqua-vscode
* Sandbox PoC: https://codesandbox.io/s/aqua-typescript-nvrd1 or https://github.com/folex/aqua-typescript-codesandbox

### Best Use Of Fluence In Your DApp -- USD 2,500:
Examples in this category include:
* Use Fluence to power a decentralized NFT creation and storage solution using, for examples, NFT.storage. We are especially excited about using Fluence compute to dynamically update the metadata of mutable NFTs.
* Use Fluence to create a multi source DEX price oracle. We see Fluence compute at the "decenter" of querying and processing of streams to facilitate the optimal computation of buy/sell orders and routing to DExs.
* Use Fluence to capture, process and index events across multiple EVMs, e.g., Ethereum L1 and L2, for a (common) contract and store the results on Ceramic or Textile. Not unlike optimal order processing and routing, we see a need for a decentralized compute solution to make real-time transaction routing decisions for a contract available, or to be made available, across multiple EVM implementations.

Document the use of Fluence in your DApp and provide a max three (3) minute video presenting and demonstration your solutions and submit via a Github or GitLab repo with MIT or Apache 2.0 license.


Happy Hacking and Good Luck!

## General Resources

* [Fluence documentation](https://doc.fluence.dev/docs/)
* [Aqua book](https://doc.fluence.dev/aqua-book/)
* [Fluence Devcontainer](https://github.com/fluencelabs/devcontainer)
* [Fluence IPFS Adapter](https://github.com/fluencelabs/aqua-ipfs)
* [Discord](https://fluence.chat)
* [Fluence Youtube channel](https://www.youtube.com/channel/UC3b5eFyKRFlEMwSJ1BTjpbw)
* [Book A Meeting With The Team](https://calendly.com/fluencehack/)
