# Security Policy

This policy applies to every repository in the TAG IT Network organisation. Individual
repositories may add a `SECURITY.md` with scope-specific detail; where they do, that file takes
precedence for that repository.

## Reporting a vulnerability

Email **security@tagit.network**. Do not open a public issue for a security report.

Please include: affected repository and commit or contract address, chain and network, a
description of the issue, reproduction steps or a proof-of-concept, and your assessment of impact.

## What to expect

| Stage | Target |
|---|---|
| Acknowledgement of your report | 72 hours |
| Initial triage and severity assessment | 7 days |
| Status update cadence while open | every 7 days |
| Fix or documented mitigation, high severity | 30 days |

We will tell you plainly if we assess a report as low severity or out of scope, and why.

## Current status — read before reporting

The protocol is **pre-mainnet**. Contracts run on Base Sepolia (84532) and hold testnet value
only. Two consequences:

- Findings whose only impact is loss of testnet funds will be acknowledged and triaged, but are
  unlikely to be treated as urgent.
- Several serious issues are already known to us and published in
  [KNOWN-ISSUES.md](https://github.com/TAG-IT-NETWORK/tagit-contracts/blob/main/KNOWN-ISSUES.md),
  including privilege concentration in a single deployer key and a short timelock delay. Please
  check that list before reporting — it will save you time.

## Out of scope

- The archived OP Sepolia (11155420) and Arbitrum Sepolia (421614) deployments, deprecated
  2026-06-27.
- Issues already listed in `KNOWN-ISSUES.md`.
- Findings that require compromising a maintainer's device or credentials.
- Denial of service against public RPC endpoints or third-party infrastructure.
- Automated scanner output submitted without a demonstrated impact.

## Safe harbour

We will not pursue or support legal action against anyone who makes a good-faith effort to comply
with this policy. Good faith means: you avoid privacy violations, data destruction and service
degradation; you only interact with accounts you own or have explicit permission to test; you give
us reasonable time to respond before disclosing publicly.

If you are unsure whether a specific action is in scope, ask first at security@tagit.network.

## Bug bounty

**There is no bug bounty programme at this time.** We would rather say so than imply a reward that
does not exist. We credit reporters in release notes where they wish to be named, and will revisit
a formal programme before mainnet.
