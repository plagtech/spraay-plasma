# ⚡ Spraay Plasma

Batch payments for the Plasma ecosystem.

Spraay Plasma is the **first batch payment tool on Plasma L1** — send XPL, USDT0, or any ERC-20 token to up to 200 recipients in a single transaction.

🔗 [spraay.app/plasma](https://spraay.app/plasma)

---

## Deployed Contract

| Network | Address | Status |
|---------|---------|--------|
| Plasma Mainnet | [`0x08fA5D1c16CD6E2a16FC0E4839f262429959E073`](https://plasmascan.to/address/0x08fA5D1c16CD6E2a16FC0E4839f262429959E073) | ✅ Verified |
| Plasma Testnet | [`0x08fA5D1c16CD6E2a16FC0E4839f262429959E073`](https://testnet.plasmascan.to/address/0x08fA5D1c16CD6E2a16FC0E4839f262429959E073) | ✅ Verified |

## Supported Tokens

| Token | Type | Address |
|-------|------|---------|
| XPL | Native | — |
| USDT0 | ERC-20 (Stablecoin) | [`0xB8CE59FC3717ada4C02eaDF9682A9e934F625ebb`](https://plasmascan.to/address/0xB8CE59FC3717ada4C02eaDF9682A9e934F625ebb) |
| Any ERC-20 | ERC-20 | Supported via `sprayERC20` |

## Features

- **Batch XPL Sends** — Distribute native XPL to up to 200 wallets in one transaction
- **USDT0 Batch Payments** — Spray stablecoins to your entire team, community, or DAO
- **Any ERC-20** — Works with any ERC-20 token deployed on Plasma
- **Equal Splits** — Gas-optimized function for sending the same amount to all recipients
- **Sub-Second Finality** — Plasma's PlasmaBFT consensus delivers instant confirmation
- **Ultra-Low Gas** — Fractions of a cent in XPL gas fees
- **0.3% Protocol Fee** — Transparent, on-chain fee collection
- **Security** — OpenZeppelin ReentrancyGuard, Pausable, and Ownable

## Contract Functions

| Function | Description |
|----------|-------------|
| `sprayETH` | Send XPL to multiple recipients with variable amounts |
| `sprayERC20` | Send USDT0 or any ERC-20 to multiple recipients (requires approval) |
| `sprayEqual` | Gas-optimized: same amount to all recipients (XPL or ERC-20) |
| `calculateTotalCost` | Preview total cost including fees |
| `calculateFee` | Preview fee for a given amount |

## Mainnet Proof

| Detail | Value |
|--------|-------|
| XPL Spray | [`0xd899...59e1`](https://plasmascan.to/tx/0xd89938377438a7eecc61ccb2f443f1e16442505e5318581269280b55be3e59e1) ✅ |
| USDT0 Spray | [`0x1da6...431e4`](https://plasmascan.to/tx/0x1da66a22b9117268e43fb9c0f35470056e2ed982d250bd31c5b1c36c12c431e4) ✅ |
| Gas (XPL spray) | 119,154 |
| Gas (ERC-20 spray) | 132,429 |
| Fee Recipient | `0x75f3f4c27bb8db5d72e82a5359674084025fc82b` |

## Use Cases

- **💵 USDT0 Payroll** — Pay your entire team in stablecoins with one transaction
- **🎁 Token Airdrops** — Distribute XPL or tokens to your community
- **🏆 Bounty Payouts** — Reward contributors with variable amounts
- **🏛️ DAO Distributions** — Treasury payouts and governance distributions

## Why Plasma?

Plasma is a Layer 1 blockchain purpose-built for stablecoin payments. With $2B+ in USDT0 liquidity, sub-second finality, and zero-fee simple USDT transfers, it's the ideal chain for batch stablecoin distributions. Spraay brings the first batch payment infrastructure to this ecosystem.

## Part of Spraay Multi-Chain

Spraay is deployed across multiple chains:

| Chain | Link |
|-------|------|
| Base | [spraay.app](https://spraay.app) |
| Plasma | [spraay.app/plasma](https://spraay.app/plasma) |
| Bittensor | [spraay.app/tao](https://spraay.app/tao) |

Source code: [github.com/plagtech/spray-app](https://github.com/plagtech/spray-app)

## Links

- **Website**: [spraay.app/plasma](https://spraay.app/plasma)
- **Contract**: [Plasmascan](https://plasmascan.to/address/0x08fA5D1c16CD6E2a16FC0E4839f262429959E073)
- **Twitter**: [@lostpoet](https://twitter.com/lostpoet)
- **Farcaster**: [@plag](https://warpcast.com/plag)

---

<div align="center">
  <sub>Built by <a href="https://github.com/plagtech">Plag</a> — First batch payment tool on Plasma ⚡</sub>
</div>
