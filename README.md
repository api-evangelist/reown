# Reown (reown)

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
