# STAR — Web5 Developer Hub

**OASIS Omniverse · Build on Web5**

STAR is the Web5 developer platform of the OASIS Omniverse. It provides everything a developer needs to build, deploy and manage OAPPs (OASIS Applications) — from the ODK (OASIS Developer Kit) to the STAR API, STAR CLI, and COSMIC ORM for universal data abstraction across 40+ storage providers.

## Components

| Tool | Description |
|---|---|
| **STAR ODK** | OASIS Developer Kit — scaffolding, code generation and dev toolchain for OAPPs |
| **STAR API** | REST/GraphQL API for deploying, managing and discovering OAPPs |
| **STAR CLI** | Command-line interface for the full STAR/OASIS workflow |
| **COSMIC ORM** | Universal ORM with adapters for 40+ databases, blockchains and distributed storage providers |
| **STARNET** | Decentralized registry and asset store where published OAPPs are listed |

## COSMIC ORM Providers (40+)

COSMIC abstracts over providers including: MongoDB, SQL Server, PostgreSQL, MySQL, SQLite, Redis, IPFS, Holochain, Ethereum, Solana, Arweave, Filecoin, ThreeFold, ActivityPub, and many more — all behind a single unified API.

## OAPP Lifecycle

```
STAR ODK scaffold → develop → STAR CLI build → STAR API deploy → STARNET publish
```

## Related Repositories

- [`STARNET`](../STARNET) — the decentralized OAPP registry (TypeScript source)
- [`STARNETSite`](../STARNETSite) — the STARNET landing page
- [`OASIS2`](../OASIS2) — the core OASIS API platform

## Tech Stack

| Layer | Detail |
|---|---|
| Site | Single-file `index.html` — inline CSS + vanilla JS |
| Fonts | Orbitron, Rajdhani, Share Tech Mono (Google Fonts) |

## Running the Site Locally

```bash
npx serve .
# or
python -m http.server 8080
```

---

*Part of the [OASIS Omniverse](https://oasisomniverse.one) · Web5 Developer Platform*
