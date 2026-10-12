# Post-Quantum Finance Is Inevitable. EternaX Is Its Foundation.

**Quantum-safe private settlement at market speed.**

EternaX is a post-quantum-native, EVM-compatible Layer-1 for institutional stablecoin issuance, RWA tokenization, tokenized funds, collateral movement, and settlement — plus a migration path for assets on classical chains.

Most blockchains cannot adopt post-quantum cryptography without major throughput loss, complex migrations, and ecosystem-wide upgrades. EternaX is built PQ-native: every asset and application inherits post-quantum protection by default.

## Design

- **Post-quantum by default** — accounts, transaction authentication, and consensus anchored on **SLH-DSA** (NIST FIPS 205).
- **Compact PQ authentication** — **SILMARILS**, a ~160-byte designated-verifier scheme co-developed with UBC, keeps the PQ throughput penalty minimal.
- **Crypto-agility** — authentication is separated from authorization, so algorithms can rotate without re-issuance, re-onboarding, or a hard fork.
- **Auditable privacy** — confidential by default, with scoped selective disclosure for auditors and supervisors; no public order-flow MEV.
- **Dual-gate MPC custody** — signature-agnostic threshold authorization for custodians and MPC providers.
- **Fast finality** — targeting 20–50 ms soft and 400–520 ms hard finality.

## Try it

- **Pluto testnet** — public PQ-enabled EVM testnet: [pluto-testnet.eternax.ai](https://pluto-testnet.eternax.ai/web-wallet/) · tooling in [`pluto-testnet-tools`](https://github.com/eternax-ai/pluto-testnet-tools)
- **Pilot programme** — 90-day institutional pilots: [eternax.ai/pilot](https://eternax.ai/pilot.html)

## Research

- [SILMARILS: Designated-Verifier Authentication with Information-Theoretic Security](https://arxiv.org/abs/2605.03230) · [reference implementation](https://github.com/eternax-ai/silmarils-paper)
- [Threshold Authorization Without Threshold Signatures: Signature-Agnostic MPC Custody](https://arxiv.org/abs/2607.08226) · [`dual-gate-mpc`](https://github.com/eternax-ai/dual-gate-mpc)
- [The Native-Signature Boundary in Post-Quantum Distributed Authorization](https://arxiv.org/abs/2609.03547)
- Reports: [eternax.ai/reports](https://eternax.ai/reports/)

## Open source

- [`pq-onchainid`](https://github.com/eternax-ai/pq-onchainid) — SLH-DSA verification for ERC-3643 / ONCHAINID compliance flows
- [`utxo-ots`](https://github.com/eternax-ai/utxo-ots) — Bitcoin-ledger-finalized one-time hash signatures via standard P2WSH

---

[eternax.ai](https://eternax.ai) · info@eternax.ai
