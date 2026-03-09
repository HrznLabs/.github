# HrznLabs Ecosystem

Horizon Protocol is a decentralized coordination layer for real-world missions. Built on Base, it connects workers and requesters through trustless smart contracts, on-chain reputation (EAS attestations), and stablecoin payments (USDC/EURC).

## Highlights

- **HRZN Token** -- Governance and utility token with a fixed 1B supply on Base. Five utilities: governance voting, staking (USDC yield via sHRZN vault), fee discounts, stake-to-work eligibility, and buyback-and-burn. Fee distribution splits rewards across stakers, guilds, treasury, and resolvers.
- **iTake** -- The first live vertical: decentralized food delivery launching in Lisbon and Porto. Uses the same escrow, reputation, and payment primitives as the core protocol, wrapped in a courier-friendly mobile experience.
- **Multi-platform** -- Native mobile app (Expo), Farcaster + Base App miniapp, admin dashboard, and public marketing site all powered by a shared NestJS backend.

## 📂 Core Repositories

| Repository | Description |
| --- | --- |
| **[horizon](https://github.com/HrznLabs/horizon)** | Monorepo -- contracts, backend, mobile, dashboard, shared |
| **[horizon-contracts](https://github.com/HrznLabs/horizon-contracts)** | Standalone Foundry contracts and deployed addresses |
| **[horizon-sdk](https://github.com/HrznLabs/horizon-sdk)** | TypeScript SDK (`horizon-protocol-sdk` on npm) |
| **[horizon-miniapp](https://github.com/HrznLabs/horizon-miniapp)** | Farcaster + Base App miniapp (Next.js, OnchainKit) |
| **[horizon-protocol-docs](https://github.com/HrznLabs/horizon-protocol-docs)** | Public developer documentation |

## 🏗️ Verticals

Horizon supports vertical-specific implementations on top of the shared protocol layer.

- **iTake** (Food Delivery) -- Active development. Lisbon + Porto beachhead targeting 50 couriers and 10 restaurants.
- **ridesDAO** (Ride Sharing) -- R&D stage.
- **BuildDAO** (Construction) -- R&D stage.

## 🚀 Getting Started

```bash
git clone https://github.com/HrznLabs/horizon.git
cd horizon
yarn install
yarn docker:up
yarn dev
```

## 🔗 Quick Links

- **Docs**: [horizon-docs-public.vercel.app](https://horizon-docs-public.vercel.app/)
- **Contracts**: Deployed on Base Sepolia -- see `horizon-contracts` for addresses
- **GitHub**: [github.com/HrznLabs](https://github.com/HrznLabs)
