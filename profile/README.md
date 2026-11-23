<p align="center">
  <img src="https://raw.githubusercontent.com/TAG-IT-NETWORK/.github/main/assets/tagit-watch-banner.jpg" width="100%" alt="TAG IT Network. A phone taps a watch to answer the question: Is this watch the real thing?" />
</p>

# You can tap the watch. Your AI agent can check it, too.

TAG IT gives physical products an identity that people and AI agents can verify. A maker links a secure NFC tag to an individual item. Tap it with a phone to see where it came from and check its recorded history. An AI agent can read the same record before recommending a purchase.

Imagine telling your assistant, **“Find me this watch secondhand, check its history, and ask me before you buy it.”** That’s the kind of commerce we’re building toward.

## What could an agent tell you?

| Example result | What it means for a buyer |
| --- | --- |
| Tag verified | The tag checks out against the maker’s record. The agent can show you the item’s recorded history. |
| Reported stolen | Even a genuine item can be flagged. The agent can warn you before you buy. |

## Build with TAG IT

Start with the [developer docs](https://github.com/TAG-IT-NETWORK/tagit-docs) or explore the [TypeScript SDK](https://github.com/TAG-IT-NETWORK/tagit-sdk).

## Open-source protocol stack

| Layer | Repository | Purpose |
|:--|:--|:--|
| **Protocol** | [`tagit-contracts`](https://github.com/TAG-IT-NETWORK/tagit-contracts) | Digital twins, lifecycle controls, ERC-4337 accounts, governance and treasury |
| **Developer platform** | [`tagit-sdk`](https://github.com/TAG-IT-NETWORK/tagit-sdk) | TypeScript SDK and command-line tooling for TAG IT integrations |
| **Applications** | [`tagit-dashboard`](https://github.com/TAG-IT-NETWORK/tagit-dashboard) | Administration, business operations and public verification experiences |
| **Mobile** | [`tagit-mobile`](https://github.com/TAG-IT-NETWORK/tagit-mobile) | Tap-to-verify, asset vaults, claims and ownership transfers |
| **Data** | [`tagit-indexer`](https://github.com/TAG-IT-NETWORK/tagit-indexer) | Indexed lifecycle, ownership and governance data |
| **Governance** | [`tagit-governance`](https://github.com/TAG-IT-NETWORK/tagit-governance) | Governance configuration and operational transparency |
| **Documentation** | [`tagit-docs`](https://github.com/TAG-IT-NETWORK/tagit-docs) | Protocol concepts, integration guides and technical references |

## Current network status

> [!IMPORTANT]
> **TAG IT is currently pre-mainnet.** Contracts are deployed to **Base Sepolia (chain ID 84532)** and hold no production value. Canonical contract addresses are maintained in [`deployment-addresses.json`](https://github.com/TAG-IT-NETWORK/tagit-contracts/blob/main/deployment-addresses.json).

Security review is in progress. Review the current [`audit scope`](https://github.com/TAG-IT-NETWORK/tagit-contracts/blob/main/AUDIT-SCOPE.md) and [`known issues`](https://github.com/TAG-IT-NETWORK/tagit-contracts/blob/main/KNOWN-ISSUES.md) before integrating.

[Visit TAG IT Network](https://www.tagit.network) · [Contact the team](mailto:info@tagit.network) · [Report a vulnerability](https://github.com/TAG-IT-NETWORK/.github/blob/main/SECURITY.md)
