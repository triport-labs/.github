<p align="center">
  <a href="https://triport.io"><img src="https://raw.githubusercontent.com/triport-labs/.github/main/profile/assets/banner.png" alt="Triport Labs" width="100%"></a>
</p>

<h3 align="center">Low-latency RPC, Yellowstone gRPC &amp; shred streams for Solana, Base, BNB Chain, Robinhood Chain and Ethereum.</h3>

<p align="center">
  <a href="https://triport.io"><img src="https://img.shields.io/badge/Website-triport.io-88b4f5?style=flat-square" alt="Website"></a>
  <a href="https://triport.io/docs"><img src="https://img.shields.io/badge/Docs-Read_the_docs-22d97a?style=flat-square" alt="Docs"></a>
  <a href="https://x.com/triport_io"><img src="https://img.shields.io/badge/X-@triport__io-000000?style=flat-square&logo=x" alt="X"></a>
  <a href="https://t.me/triport_dev"><img src="https://img.shields.io/badge/Telegram-Community-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="mailto:sales@triport.io"><img src="https://img.shields.io/badge/Email-sales@triport.io-818cf8?style=flat-square" alt="Email"></a>
</p>

---

## What we build

**Triport** is blockchain infrastructure for teams that care about being first: trading bots, wallets, indexers and dApps.

| | |
|---|---|
| **RPC** | JSON-RPC and WebSocket endpoints for Solana, Base, BNB Chain, Robinhood Chain, Ethereum and more |
| **Yellowstone gRPC** | Geyser streams of accounts, transactions, slots and blocks at `grpc.triport.io` |
| **Shred streams** | Raw Solana shreds, before blocks are assembled |
| **Transaction sending** | Fan-out `sendTransaction` and Jito bundles |
| **Data APIs** | Transaction history, wallet activity and token metadata |

## Get started

1. Create a free key at **[triport.io/app](https://triport.io/app)**
2. Make your first call:

```bash
curl https://triport.io/r/<YOUR_KEY>/sol \
  -H "Content-Type: application/json" \
  -d '{"jsonrpc":"2.0","id":1,"method":"getSlot"}'
```

3. Explore the guides at **[triport.io/docs](https://triport.io/docs)**

## Talk to us

- Community and updates: [t.me/triport_dev](https://t.me/triport_dev)
- Sales and custom plans: [t.me/triport_sales](https://t.me/triport_sales) · [sales@triport.io](mailto:sales@triport.io)
- News: [x.com/triport_io](https://x.com/triport_io)
