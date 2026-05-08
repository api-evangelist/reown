# Reown (reown)

Reown (formerly WalletConnect) provides Web3 connection infrastructure including AppKit (login + wallet integration UX), WalletConnect SDK (wallet-side), the Reown Cloud Explorer API (dApp/wallet directory), Push Notifications, and Multi-chain RPC. The WalletConnect protocol itself is SDK-mediated; Reown also exposes REST APIs for the Cloud Explorer.

Honest skip: WalletConnect Relay is SDK-mediated. Reown publishes the Explorer API reference but not a stable OpenAPI download URL.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/reown/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=reown-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## APIs
- **Reown Cloud Explorer API** - REST API to retrieve listings of WalletGuide-approved wallets, dApps, hybrid entries, and chains, plus logo assets.
- **Reown Notify (Push) API** - REST API for sending wallet push notifications via the Reown Notify protocol, plus subject/topic management.
- **Reown Blockchain API** - Multi-chain JSON-RPC over HTTPS used by AppKit and partners; provides on-chain reads, gas, swaps, and onramp helpers.
- **WalletConnect Relay (SDK-mediated)** - WalletConnect v2 relay network for end-to-end encrypted JSON-RPC pairing between dApps and wallets.

## Tags
 - Web3, Wallets, WalletConnect, AppKit, RPC

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://reown.com/)
- [Plans](plans/reown-plans-pricing.yml)
- [RateLimits](rate-limits/reown-rate-limits.yml)
- [FinOps](finops/reown-finops.yml)

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
