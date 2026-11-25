# SPECULA

**Every project leaves a trace. Follow the evidence.**

SPECULA is autonomous Web3 intelligence infrastructure for **Robinhood Chain (`Chain ID: 4663`)** — combining deterministic onchain forensics, runtime bytecode fingerprinting, two-hop funding attribution, and persistent entity memory.

---

### Public Repositories

- **[`speculanetwork/specula-core`](https://github.com/speculanetwork/specula-core)** — Deterministic core primitives: Solidity CBOR metadata stripping, normalized runtime bytecode hashing, EIP-1167/1967 proxy resolution, content-addressed `keccak256` evidence records, CAIP-style entity canonicalization, connection graph builder, and forensic methodology.

---

### Investigation Architecture

| Module | Mode | Scope |
| --- | --- | --- |
| **ARGUS** | Deterministic | Target classification & bounded Pons `TokenLaunched` checkpoint indexing |
| **HERMES** | Deterministic + bounded tool selection | Contract verification, deployer separation & 2-hop native funding trace |
| **DAEDALUS** | Deterministic | CBOR-stripped runtime bytecode hashing, EIP-1167/1967 proxy resolution & repository blob fingerprints |
| **NYX** | Deterministic | Cross-investigation entity lookup & evidence-backed connection graph |
| **MNEMOSYNE** | Deterministic | Canonical entity normalization & SHA-256/keccak256 evidence deduplication |
| **THEMIS** | Citation-verified review + deterministic fallback | Structured evidence synthesis with strict provenance checks |

---

### Evidence Principles

- **Deterministic first** — every graph edge, timeline event, and Developer DNA match is backed by a stored evidence record with source URL and timestamp.
- **Explicit separation** — verified onchain facts, derived multi-hop relationships, and coverage limitations are never conflated.
- **No fabricated certainty** — shared upstream funding establishes a transfer path, not personal identity.

---

`NETWORK: ROBINHOOD CHAIN (4663)`
