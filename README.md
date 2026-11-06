# Gabriel Agada

**Rust & TypeScript engineer building privacy and payment infrastructure** — shielded
transfers, on-chain identity, and the contracts underneath them.

Stellar (Soroban) · NEAR · Starknet · Zcash · Ethereum

Open to protocol and backend roles.

---

## Selected work

**[LeakBench](https://github.com/raizo07/LeakBench)** — a leak oracle for Zcash. Scores a
wallet's on-chain behaviour against 15 heuristics and reports exactly what it published:
amounts, timing, fingerprints. Rust workspace, golden tests against real mainnet
transactions, SARIF output, CI, [live demo](https://raizo07.github.io/LeakBench/).

**[handover](https://github.com/raizo07/handover)** — a business is a NEAR account, its
shares are NFTs. A charter-enforced treasury vault plus a NEP-171 registry with a two-beat
rotation state machine. 32 tests, spec, and decision records.

**[BlindPay](https://github.com/raizo07/BlindPay)** — private invoicing on Starknet.
Merchants issue invoices, payers settle through the STRK20 privacy pool, and settlement
verifies without linking either side on-chain. [Demo](https://frontend-gules-chi-29.vercel.app).

**[Aztec Domain Identity](https://github.com/raizo07/Aztec-Domain-Identity)** — a DNSSEC →
DKIM key registry in Noir, so ZK-email verifies against the DNS root instead of a
hardcoded key that expires.

**[Flex Position Manager](https://github.com/raizo07/Flex-Position-Manager)** — one
Uniswap v4 NFT holding many liquidity ranges, backed by an on-chain red-black tree.

## Open source

171 merged pull requests across Zcash, Stellar, Starknet, and NEAR infrastructure. A few
representative ones:

- [`thus-spoke-zakura` #335](https://github.com/zcashlabs/thus-spoke-zakura/pull/335) — `ths rpc` CLI command: 232 lines of implementation, 452 lines of tests (+788/−6)
- [`wraith-protocol/contracts` #129](https://github.com/wraith-protocol/contracts/pull/129) — gas-benchmark regression gate in CI (+1194/−245)
- [`SYNCRO` #1770](https://github.com/Calebux/SYNCRO/pull/1770) — consolidated duplicate crates across a Rust workspace (+393/−126)

## Contact

[agadaraizo@gmail.com](mailto:agadaraizo@gmail.com) · [LinkedIn](https://www.linkedin.com/in/agada-gabriel-530104129/) · [X](https://twitter.com/skippo0007)
