<img src="./banner1.png" width="100%" alt="Marc F. — Data Engineering · Blockchain Infrastructure · Security"/>

**I build the indexers, forensic engines, and security tooling DeFi runs on.**

7+ years shipping production systems at the intersection of data engineering, DeFi protocol infrastructure, and applied security. I design and ship data pipelines, on-chain indexers, forensic analytics engines, and security tooling across Web2 and Web3 stacks — with the protocol-level depth most data engineers don't carry.

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](#)
[![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)](#)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](#)
[![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat&logo=solidity&logoColor=white)](#)
[![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)](#)

---

## ⚙️ Infrastructure & indexing

- **reth-usdc-indexer** — Real-time USDC indexer built on Reth. Zero RPC calls, sub-10ms queries, reorg handling.
- **defi-replay-kit** — Pre-packaged DeFi exploit datasets, offline-queryable via SQL. Used for forensic research and protocol audits.
- **yulsafe** — Gas-optimized ERC4626 vault for zkSync Era.
- **perp-liquidity** — 8-venue cross-venue perp tool: orderbook, funding, OI, liquidations. 138 tests.
- **depth-map** — Cross-venue L2 order book depth and cost-to-move across 5 venues, including custom Binance and OKX adapters.

## 🔐 Security tooling

- **rsentinel** — Shipped Rust CLI security scanner: SSL/TLS, HTTP header, and DNS checks, plus detection and hardening for AI/agent infrastructure (prompt injection, tool abuse, session integrity).
- **CyberShield** — Threat detection platform for SMBs: three-tier email scanning pipeline (rule engine + ML + LLM fallback), browser extension for real-time DOM link analysis.
- **cve-guard** — Node.js dependency vulnerability scanner with live CVE database integration.

## 📡 Market data & signal infrastructure

- **LiqNode** — Raspberry Pi liquidation data node for Hyperliquid. Infers liquidations via OI-delta on the `activeAssetCtx` feed (HL exposes no native liquidation flag), with a FastAPI backend serving live heatmaps.
- **signal-pipeline** — Source-agnostic signal ingestion layer: trust tiers, MAD anomaly detection, multi-source aggregation. 44 tests.
- **hip3-divergence** — Three-price divergence monitor for oracle-backed perps, tracking spot, oracle, and mark price drift in real time. 42 tests, running 24/7 on a Pi.
- **cohort-pnl / cohort-dashboard** — Wallet cohort analytics by PNL tier across multiple assets, with per-wallet drill-down and exposure calculation.

## 📊 Data & analytics

- **grvt-sdk** — Python SDK for GRVT Exchange: REST, WebSocket, EIP-712 signing, low-latency order pipeline. 83 unit tests.
- **VLTFI / RiskLens** — Forensic DeFi risk intelligence engine: cross-vault concentration mapping, protocol exposure analysis, institutional reporting.
- **Quarq** — RAG-based research and report assistant: ingestion, retrieval, and LLM-driven report generation pipeline.
- **cac40-portfolio-analyser** — Portfolio analysis tool for CAC40 equities.
- **paradex-py** — Merged PR adding a `ThreadedWebSocketClient`, plus a sybil-detection build for Paradex's market.
- **nansen-cli** — Two merged PRs extending Nansen's open-source CLI.
- Dune Spellbook contributor · BigQuery datasets (Numia, P2P)

---

| | |
|---|---|
| **Languages** | Python · Rust · TypeScript · SQL |
| **Infra** | Reth · zkSync · BigQuery · Tailscale · Nginx |
| **Protocols** | Aave · Morpho · Uniswap · ERC4626 · EIP-712 |
| **Spoken** | French (native) · English · Mandarin |

---

**Based in Taipei or EU** &nbsp;·&nbsp; Open to senior data engineering & infrastructure roles (remote, Singapore, HK, Europe)

[![Email](https://img.shields.io/badge/zkmarc@proton.me-8B89CC?style=flat&logo=protonmail&logoColor=white)](mailto:zkmarc@proton.me)
