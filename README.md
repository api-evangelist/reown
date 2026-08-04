# Reown (reown)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Reown (formerly WalletConnect) provides Web3 connection infrastructure including AppKit (login + wallet integration UX), WalletConnect SDK (wallet-side), the Reown Cloud Explorer API (dApp/wallet directory), Push Notifications, and Multi-chain RPC. The WalletConnect protocol itself is SDK-mediated; Reown also exposes REST APIs for the Cloud Explorer.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/reown/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/reown/refs/heads/main/apis.yml)

## Tags

- Web3
- Wallets
- WalletConnect
- AppKit
- RPC

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Reown Cloud Explorer API

REST API to retrieve listings of WalletGuide-approved wallets, dApps, hybrid entries, and chains, plus logo assets. Filter by chain, platform, SDK, standard, or search term.

- **Human URL:** [https://docs.reown.com/cloud/explorer](https://docs.reown.com/cloud/explorer)
- **Base URL:** `https://api.web3modal.org/v3`

#### Tags

- REST
- Directory

#### Properties

- [Documentation](https://docs.reown.com/cloud/explorer)
- [Postman Collection](collections/reown.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/reown.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Reown Notify (Push) API

REST API for sending wallet push notifications via the Reown Notify protocol, plus subject/topic management.

- **Human URL:** [https://docs.reown.com/cloud/notify-api](https://docs.reown.com/cloud/notify-api)
- **Base URL:** `https://notify.walletconnect.com`

#### Tags

- REST
- Push

#### Properties

- [Documentation](https://docs.reown.com/cloud/notify-api)
- [Postman Collection](collections/reown.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/reown.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Reown Blockchain API

Multi-chain JSON-RPC over HTTPS used by AppKit and partners; provides on-chain reads, gas, swaps, and onramp helpers.

- **Human URL:** [https://docs.reown.com/cloud/blockchain-api](https://docs.reown.com/cloud/blockchain-api)
- **Base URL:** `https://rpc.walletconnect.com/v1`

#### Tags

- JSON-RPC
- Multi-chain

#### Properties

- [Documentation](https://docs.reown.com/cloud/blockchain-api)
- [Postman Collection](collections/reown.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/reown.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WalletConnect Relay (SDK-mediated)

WalletConnect v2 relay network for end-to-end encrypted JSON-RPC pairing between dApps and wallets. Accessed through SDK clients only; not a direct REST surface.

- **Human URL:** [https://docs.reown.com/walletkit/overview](https://docs.reown.com/walletkit/overview)
- **Base URL:** `wss://relay.walletconnect.com`

#### Tags

- WebSocket
- Relay

#### Properties

- [Documentation](https://docs.reown.com/walletkit/overview)
- [AsyncAPI](asyncapi/reown-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/reown.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/reown.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/reown-com)
- [LinkedIn](https://www.linkedin.com/company/re-own)
- [Website](https://reown.com/)
- [Plans](plans/reown-plans-pricing.yml)
- [Rate Limits](rate-limits/reown-rate-limits.yml)
- [Fin Ops](finops/reown-finops.yml)
- [L L Ms Txt](https://docs.reown.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
