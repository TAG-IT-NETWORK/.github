## TAG IT Network

Physical-world verification infrastructure. We bind NFC tags to on-chain digital twins so a
physical object's provenance, ownership and lifecycle can be verified by anyone, without trusting
the party holding it.

An asset moves through a seven-state lifecycle — `MINTED → BOUND → ACTIVATED → CLAIMED`, with
`FLAGGED` and `RECYCLED` for recall, theft and end-of-life. Each transition is gated by capability
badges and recorded on-chain.

### Where things are

| Repository | What it is |
|---|---|
| [tagit-contracts](https://github.com/TAG-IT-NETWORK/tagit-contracts) | Solidity protocol — digital twins, ERC-4337 accounts, governance, treasury |
| [tagit-sdk](https://github.com/TAG-IT-NETWORK/tagit-sdk) | TypeScript SDK and CLI |
| [tagit-dashboard](https://github.com/TAG-IT-NETWORK/tagit-dashboard) | Admin console, business portal, public verification apps |
| [tagit-mobile](https://github.com/TAG-IT-NETWORK/tagit-mobile) | Consumer app — tap to verify, asset vault, transfers |
| [tagit-indexer](https://github.com/TAG-IT-NETWORK/tagit-indexer) | Subgraph for lifecycle and governance queries |
| [tagit-docs](https://github.com/TAG-IT-NETWORK/tagit-docs) | Protocol and integration documentation |

### Status

**Testnet.** Contracts are deployed to **Base Sepolia (chain ID 84532)** and hold no production
value. Earlier OP Sepolia and Arbitrum Sepolia deployments were deprecated on 2026-06-27 and should
not be integrated against. Canonical addresses live in
[`deployment-addresses.json`](https://github.com/TAG-IT-NETWORK/tagit-contracts/blob/main/deployment-addresses.json)
— that file is the single source of truth; treat any address published elsewhere as stale.

An external security audit is in progress. Scope, current limitations and a candid list of open
issues are published in the contracts repo rather than held back:
[AUDIT-SCOPE.md](https://github.com/TAG-IT-NETWORK/tagit-contracts/blob/main/AUDIT-SCOPE.md) ·
[KNOWN-ISSUES.md](https://github.com/TAG-IT-NETWORK/tagit-contracts/blob/main/KNOWN-ISSUES.md)

### Security

Report vulnerabilities to **security@tagit.network**. See
[SECURITY.md](https://github.com/TAG-IT-NETWORK/.github/blob/main/SECURITY.md).

— [www.tagit.network](https://www.tagit.network)
