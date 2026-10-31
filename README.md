# Reown

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Reown (formerly WalletConnect) provides Web3 connection infrastructure including AppKit (login + wallet integration UX), WalletConnect SDK (wallet-side), the Reown Cloud Explorer API (dApp/wallet directory), Push Notifications, and Multi-chain RPC. The WalletConnect protocol itself is SDK-mediated; Reown also exposes REST APIs for the Cloud Explorer.

**Areas:** Web3 · Wallets · WalletConnect · AppKit · RPC · Real-Time

## Reown on APIs.io

Everything profiled for Reown is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/reown/](https://apis.io/providers/reown/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Reown Cloud Explorer API](https://apis.io/apis/reown/explorer-api/) — REST API to retrieve listings of WalletGuide-approved wallets, dApps, hybrid entries, and chains, plus logo assets. Filter by chain, platform, SDK,…
- [Reown Notify (Push) API](https://apis.io/apis/reown/notify-api/) — REST API for sending wallet push notifications via the Reown Notify protocol, plus subject/topic management.
- [Reown Blockchain API](https://apis.io/apis/reown/blockchain-api/) — Multi-chain JSON-RPC over HTTPS used by AppKit and partners; provides on-chain reads, gas, swaps, and onramp helpers.
- [WalletConnect Relay (SDK-mediated)](https://apis.io/apis/reown/walletconnect-protocol/) — WalletConnect v2 relay network for end-to-end encrypted JSON-RPC pairing between dApps and wallets. Accessed through SDK clients only; not a direct REST…
- [Reown Chains API](https://apis.io/apis/reown/reown-chains-api/) — Blockchain chains registered under CASA namespaces.
- [Reown Listings API](https://apis.io/apis/reown/reown-listings-api/) — Wallet, dApp, and hybrid directory listings.
- [Reown Logos API](https://apis.io/apis/reown/reown-logos-api/) — Logo image assets for listings.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Reown / WalletConnect v2 Relay](https://apis.io/asyncapis/reown/reown-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [/](https://apis.io/channels/reown/untitled/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Reown Agentic Access](https://apis.io/agentic-access/reown/reown-agentic-access/)

#### Collections (4)

Postman and Open Collection request collections.

- [Reown Cloud Explorer API](https://apis.io/collections/reown/open-reown/)
- [Reown Cloud Explorer Chains API](https://apis.io/collections/reown/open-reown-chains-api/)
- [Reown Cloud Explorer Chains Listings API](https://apis.io/collections/reown/open-reown-listings-api/)
- [Reown Cloud Explorer Chains Logos API](https://apis.io/collections/reown/open-reown-logos-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Reown — asyncapi rules](https://apis.io/rules/reown/reown-asyncapi-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Reown Authentication](https://apis.io/security/reown/reown-authentication/)
- [Reown Domain Security](https://apis.io/security/reown/reown-domain-security/)
- [Reown Vulnerability Disclosure](https://apis.io/security/reown/reown-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Reown Plans Pricing](https://apis.io/plans/reown/reown-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Reown Rate Limits](https://apis.io/rate-limits/reown/reown-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Reown Finops](https://apis.io/finops/reown/reown-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://reown.com/)
- [Blog](https://reown.com/blog)
- [GitHub](https://github.com/reown-com)

## API Evangelist rating

**Kin Score 29.4** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 55.5 |
| Contract governance | 11.4 |
| Operational transparency | 7.9 |
| Developer ergonomics | 23.8 |
| Access clarity | 7.9 |

**Agent readiness 22.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.1** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/reown/](https://apis.io/providers/reown/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Reown: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/reown/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
