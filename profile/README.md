<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/sentrix-labs/brand-kit@master/png-transparent/sentrix-labs-256.png" alt="Sentrix Labs" width="120" />
</p>

<h1 align="center">Sentrix Labs 🇮🇩</h1>

<p align="center">
  <b>Rust-based blockchain infrastructure for Sentrix Chain.</b>
</p>

<p align="center">
  Protocol · Validators · EVM · RPC · Indexers · Contracts · Developer tooling
</p>

<p align="center">
  <a href="https://sentrixchain.com">
    <img src="https://img.shields.io/badge/Website-sentrixchain.com-8A5A11?style=for-the-badge" alt="Website" />
  </a>
  <a href="https://docs.sentrixchain.com">
    <img src="https://img.shields.io/badge/Docs-docs.sentrixchain.com-2f855a?style=for-the-badge" alt="Docs" />
  </a>
  <a href="https://scan.sentrixchain.com">
    <img src="https://img.shields.io/badge/Explorer-scan.sentrixchain.com-1f2937?style=for-the-badge" alt="Explorer" />
  </a>
</p>

<p align="center">
  <a href="https://x.com/sentrixchain">
    <img src="https://img.shields.io/badge/X-@sentrixchain-000000?style=flat-square" alt="X" />
  </a>
  <a href="https://t.me/SentrixChain">
    <img src="https://img.shields.io/badge/Telegram-SentrixChain-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram" />
  </a>
  <a href="https://github.com/sentrix-labs/sentrix">
    <img src="https://img.shields.io/badge/Core-Rust-orange?style=flat-square&logo=rust" alt="Rust Core" />
  </a>
  <a href="https://github.com/sentriscloud">
    <img src="https://img.shields.io/badge/Apps-SentrisCloud-2563eb?style=flat-square" alt="SentrisCloud" />
  </a>
</p>

---

## Start here

| I want to... | Go to |
|---|---|
| Understand the protocol | [`sentrix`](https://github.com/sentrix-labs/sentrix) |
| Find official resources | [`awesome-sentrix`](https://github.com/sentrix-labs/awesome-sentrix) |
| Read the docs | [`docs`](https://github.com/sentrix-labs/docs) |
| Build apps and tools | [`SentrisCloud`](https://github.com/sentriscloud) |
| Work with contracts | [`canonical-contracts`](https://github.com/sentrix-labs/canonical-contracts) |
| Follow protocol proposals | [`SIPs`](https://github.com/sentrix-labs/SIPs) |

---

## What is Sentrix Labs?

**Sentrix Labs** is the protocol engineering home of **[Sentrix Chain](https://sentrixchain.com)** — a Rust-based EVM Layer 1 built from Indonesia.

We work on the core chain stack: consensus, networking, execution, storage, validator infrastructure, RPC, canonical contracts, developer tooling, and ecosystem standards.

Sentrix is still early and actively being hardened. The focus is real infrastructure: measurable progress, reproducible systems, and public engineering work.

---

## Sentrix Chain

Sentrix Chain combines a Rust-native protocol core with familiar EVM tooling.

| Layer | Focus |
|---|---|
| Consensus | DPoS + BFT validator coordination |
| Execution | Native execution + EVM compatibility |
| EVM runtime | `revm`-based execution path |
| Networking | libp2p peer-to-peer networking |
| Storage | MDBX-backed chain storage |
| APIs | JSON-RPC, WebSocket, REST, gRPC, and gRPC-Web |
| Infrastructure | Validators, fullnodes, RPC, indexers, explorer backend |
| Ecosystem | Contracts, SDKs, docs, examples, and application tooling |

User-facing products such as the explorer, faucet, wallet, launchpad, SDKs, indexers, and frontend applications live under **[SentrisCloud](https://github.com/sentriscloud)**.

---

## Repositories

### Protocol and standards

| Repository | Description |
|---|---|
| [`sentrix`](https://github.com/sentrix-labs/sentrix) | Core Sentrix Chain node — Rust runtime, consensus, networking, storage, EVM execution, RPC, and validator infrastructure |
| [`SIPs`](https://github.com/sentrix-labs/SIPs) | Sentrix Improvement Proposals for protocol changes and ecosystem standards |
| [`whitepaper`](https://github.com/sentrix-labs/whitepaper) | Sentrix Chain whitepaper and protocol narrative |

### Developer and ecosystem resources

| Repository | Description |
|---|---|
| [`awesome-sentrix`](https://github.com/sentrix-labs/awesome-sentrix) | Curated Sentrix resources, official links, tools, apps, SDKs, and ecosystem references |
| [`docs`](https://github.com/sentrix-labs/docs) | Sentrix Chain documentation |
| [`token-list`](https://github.com/sentrix-labs/token-list) | Token registry for Sentrix mainnet and testnet |
| [`brand-kit`](https://github.com/sentrix-labs/brand-kit) | Official logos, icons, colors, and brand assets |

### Contracts and liquidity infrastructure

| Repository | Description |
|---|---|
| [`canonical-contracts`](https://github.com/sentrix-labs/canonical-contracts) | Canonical EVM contracts such as WSRX, Multicall3, SentrixSafe, and TokenFactory |
| [`sentrix-dex`](https://github.com/sentrix-labs/sentrix-dex) | AMM / DEX contracts for Sentrix ecosystem liquidity |
| [`sentrix-bridge`](https://github.com/sentrix-labs/sentrix-bridge) | Bridge and wrapped asset infrastructure |

---

## Live infrastructure

| Service | URL |
|---|---|
| Website | [https://sentrixchain.com](https://sentrixchain.com) |
| Documentation | [https://docs.sentrixchain.com](https://docs.sentrixchain.com) |
| Explorer | [https://scan.sentrixchain.com](https://scan.sentrixchain.com) |
| Mainnet RPC | [`https://rpc.sentrixchain.com`](https://rpc.sentrixchain.com) |
| Testnet RPC | [`https://testnet-rpc.sentrixchain.com`](https://testnet-rpc.sentrixchain.com) |
| REST API | [`https://api.sentrixchain.com`](https://api.sentrixchain.com) |
| Faucet | [https://faucet.sentrixchain.com](https://faucet.sentrixchain.com) |
| Wallet | [https://solux.sentriscloud.com](https://solux.sentriscloud.com) |
| Launchpad | [https://coinblast.sentriscloud.com](https://coinblast.sentriscloud.com) |
| Apps & tooling | [https://github.com/sentriscloud](https://github.com/sentriscloud) |

---

## Technical profile

| Area | Stack |
|---|---|
| Core language | Rust |
| Smart contracts | Solidity + Foundry |
| Application layer | TypeScript / Next.js |
| Mobile | Flutter |
| Consensus | DPoS + BFT |
| Execution | Native + EVM |
| EVM runtime | `revm` |
| Networking | libp2p |
| Storage | MDBX-backed storage |
| APIs | JSON-RPC, WebSocket, REST, gRPC, gRPC-Web |
| Mainnet chain ID | `7119` |
| Testnet chain ID | `7120` |
| Native asset | SRX |

---

## Contributing

We are opening more of the Sentrix ecosystem for technical contributors, reviewers, builders, and documentation contributors.

Good areas to help:

- Rust protocol engineering
- BFT consensus and validator liveness
- libp2p networking
- EVM / `revm` execution
- JSON-RPC, WebSocket, REST, and gRPC compatibility
- Indexer and explorer infrastructure
- Solidity contracts and dApp templates
- TypeScript and Rust SDKs
- Wallet UX and frontend applications
- Documentation, examples, tutorials, and testing

Entry points:

| Path | Best for |
|---|---|
| [`sentrix`](https://github.com/sentrix-labs/sentrix) | Protocol, node, consensus, RPC, validator infrastructure |
| [`awesome-sentrix`](https://github.com/sentrix-labs/awesome-sentrix) | Ecosystem map, official links, and contributor entry points |
| [`docs`](https://github.com/sentrix-labs/docs) | Documentation, tutorials, guides, and onboarding |
| [`SentrisCloud`](https://github.com/sentriscloud) | Explorer, wallet, faucet, launchpad, SDKs, indexers, and apps |

---

## For builders

If you are building on Sentrix, useful areas include:

- Deploying Solidity contracts on Sentrix EVM
- Building dApps with existing EVM tooling
- Integrating Sentrix RPC into wallets and dashboards
- Using SDKs and starter templates
- Adding tokens to the token list
- Building indexer-powered applications
- Contributing examples, guides, and developer tools

Useful repositories:

- [`canonical-contracts`](https://github.com/sentrix-labs/canonical-contracts)
- [`sentrix-dex`](https://github.com/sentrix-labs/sentrix-dex)
- [`sentrix-bridge`](https://github.com/sentrix-labs/sentrix-bridge)
- [`token-list`](https://github.com/sentrix-labs/token-list)
- [`sdk-ts`](https://github.com/sentriscloud/sdk-ts)
- [`sdk-rs`](https://github.com/sentriscloud/sdk-rs)
- [`dapp-starter`](https://github.com/sentriscloud/dapp-starter)

---

## For validators and infrastructure providers

Sentrix validator and node infrastructure is being hardened in public.

Relevant areas:

- Validator and fullnode operations
- RPC reliability
- gRPC and WebSocket infrastructure
- Peer networking
- Monitoring and alerting
- Indexer synchronization
- Explorer backend reliability
- Security hardening and incident runbooks

For validator discussions:

- Email: [validators@sentrixchain.com](mailto:validators@sentrixchain.com)
- Telegram: [t.me/SentrixChain](https://t.me/SentrixChain)

---

## Security

Please do not disclose vulnerabilities publicly.

| Purpose | Contact |
|---|---|
| Security disclosures | [security@sentrixchain.com](mailto:security@sentrixchain.com) |
| Private GitHub advisory | [`sentrix` security advisory](https://github.com/sentrix-labs/sentrix/security/advisories/new) |

---

## Contact

| Purpose | Contact |
|---|---|
| Builders / dApps | [builders@sentrixchain.com](mailto:builders@sentrixchain.com) |
| Validators | [validators@sentrixchain.com](mailto:validators@sentrixchain.com) |
| Ecosystem / grants | [grants@sentrixchain.com](mailto:grants@sentrixchain.com) |
| General support | [support@sentrixchain.com](mailto:support@sentrixchain.com) |
| Telegram | [t.me/SentrixChain](https://t.me/SentrixChain) |
| X / Twitter | [@sentrixchain](https://x.com/sentrixchain) |
| Founder | [@satyakwok](https://github.com/satyakwok) |

---

## Support the work

Sentrix is built and maintained by a small independent team.

If you want to support protocol development, validator tooling, documentation, and ecosystem infrastructure:

[![Sponsor @satyakwok](https://img.shields.io/badge/Sponsor-@satyakwok-2ea44f?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://github.com/satyakwok#sponsor)

---

<p align="center">
  <b>Built from Indonesia 🇮🇩</b>
</p>
