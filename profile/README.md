# CodeQuill

**Memory infrastructure for software.**

CodeQuill is a source-centric software provenance system designed to preserve verifiable, immutable evidence of what source code existed at a given point in time — and under whose authority.

It records durable references for:
- Repository authority (claims)
- Deterministic source snapshots
- Curated project releases
- Artifact lineage attestations
- Optional encrypted preservation

All core primitives are anchored on Ethereum.

https://codequill.xyz

---

## Why CodeQuill

Modern software evolves quickly.

Repositories change.
CI systems rotate.
Logs expire.
Organizations restructure.

When questions arise later — during audits, incidents, or governance decisions — answers often depend on systems that were never designed to preserve long-term evidence.

CodeQuill exists to preserve facts, not narratives.

In an era where code is produced faster than it can be remembered, software needs durable memory.

---

## Core Principles

- **Source is evidence, not intent**
- **Authority is explicit**
- **Evidence must survive hostile assumptions**
- **Preservation must not require custody**
- **Infrastructure should be inspectable**

CodeQuill does not attempt to prove build causality or guarantee end-to-end supply-chain security. It preserves durable records so claims can be reasoned about over time.

---

## Repositories

### Smart Contracts
The on-chain primitives that define authority, snapshots, releases, attestations, and delegation are public and permissionless.

→ https://github.com/codequill-claim/codequill-contracts

Architecture diagrams, permission matrices, and threat model notes are included to make the design legible.

---

## Status

CodeQuill is preparing for public beta on Sepolia (Ethereum testnet).

The beta will allow:
- Claiming repositories
- Publishing snapshots
- Creating project releases
- Recording attestations
- Testing preservation workflows

---

## Maintained by

CodeQuill is maintained by **Ophelios Studio**.

→ https://github.com/ophelios-studio 

---

Ethereum works best when infrastructure explains itself.
