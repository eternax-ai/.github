# EternaX

**The post-quantum authorization layer for institutional digital assets.**

Custody release, stablecoin mint and freeze roles, collateral release, compliance claims and upgrade keys are authorized today by ECDSA or EdDSA. EternaX requires NIST post-quantum signatures for these actions under the systems institutions already run, on Ethereum, EVM chains and Hyperledger Besu, without waiting for a chain upgrade or rebuilding custody.

- **NIST-standardized** — hash-based SLH-DSA (FIPS 205) by default, ML-DSA (FIPS 204) where throughput requires it.
- **Crypto-agile** — authentication is separated from authorization, so the algorithm can change without re-issuing assets or re-onboarding participants.
- **Custody-neutral** — existing HSMs, MPC and custodians keep signing; EternaX never holds keys or funds.
- **PQ-native settlement** — an EVM network that is post-quantum from genesis, for new issuance.

## Research

Index of papers, cryptanalysis, reports and code: [`research`](https://github.com/eternax-ai/research)

- [The Native-Signature Boundary in Post-Quantum Distributed Authorization](https://arxiv.org/abs/2609.03547)
- [Threshold Authorization Without Threshold Signatures: Signature-Agnostic MPC Custody](https://arxiv.org/abs/2607.08226) · [`dual-gate-mpc`](https://github.com/eternax-ai/dual-gate-mpc)
- [SILMARILS: Information-Theoretic and Quantum-Secure Designated-Verifier Signatures](https://arxiv.org/abs/2605.03230) · [`silmarils-paper`](https://github.com/eternax-ai/silmarils-paper)
- [Collision attacks on 39-step SHA-256 below generic search](https://eternax.ai/blogs/sha-256-39-step-collisions-below-generic-search/index.html)
- Reports: [eternax.ai/reports](https://eternax.ai/reports/index.html)

## Try it

- **Pluto testnet** — public post-quantum EVM testnet, live since November 2025: [web wallet](https://pluto-testnet.eternax.ai/web-wallet/) · [`pluto-testnet-tools`](https://github.com/eternax-ai/pluto-testnet-tools)
- **EternaX Vault** — post-quantum vault for ETH, stablecoins and ERC-20s, live on testnet: [eternax.ai/post-quantum-vault](https://eternax.ai/post-quantum-vault.html)
- **Pilot** — 30-day institutional pilot: [eternax.ai/pilot](https://eternax.ai/pilot.html)

## Open source

- [`dual-gate-mpc`](https://github.com/eternax-ai/dual-gate-mpc) — reference implementation of dual-gate custody: signature-agnostic threshold authorization (Rust, TypeScript, Solidity)
- [`silmarils-paper`](https://github.com/eternax-ai/silmarils-paper) — Rust reference implementation of SILMARILS designated-verifier signatures
- [`pq-onchainid`](https://github.com/eternax-ai/pq-onchainid) — SLH-DSA and ML-DSA claim verification for ERC-3643 / ONCHAINID compliance flows
- [`utxo-ots`](https://github.com/eternax-ai/utxo-ots) — one-time hash signatures finalized on the Bitcoin ledger through standard P2WSH

---

[eternax.ai](https://eternax.ai) · info@eternax.ai
