<p align="center">
  <img src="https://raw.githubusercontent.com/triport-labs/.github/main/profile/assets/banner.png" alt="Triport Labs" width="100%">
</p>

<p align="center">
  <a href="https://triport.io"><img src="https://img.shields.io/badge/Website-triport.io-88b4f5?style=flat-square" alt="Website"></a>
  <a href="https://triport.io/docs"><img src="https://img.shields.io/badge/Docs-triport.io%2Fdocs-22d97a?style=flat-square" alt="Docs"></a>
  <a href="https://x.com/triport_io"><img src="https://img.shields.io/badge/X-@triport__io-000000?style=flat-square&logo=x" alt="X"></a>
  <a href="https://t.me/triport_dev"><img src="https://img.shields.io/badge/Telegram-@triport__dev-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="mailto:sales@triport.io"><img src="https://img.shields.io/badge/Email-sales@triport.io-818cf8?style=flat-square" alt="Email"></a>
</p>

## 9 networks, one API

**Triport** is blockchain infrastructure for teams that care about being first: trading bots, wallets, indexers and dApps. One key gives you all nine networks:

**Solana · Ethereum · Base · BNB Chain · Polygon · Tron · Robinhood Chain · TON · Stellar**

| | |
|---|---|
| **RPC** | JSON-RPC and WebSocket endpoints on every supported network |
| **Yellowstone gRPC** | Geyser streams of accounts, transactions, slots and blocks at `grpc.triport.io` |
| **Shred streams** | Raw Solana shreds, before blocks are assembled |
| **Transaction sending** | Fan-out `sendTransaction` and Jito bundles |
| **Data APIs** | Transaction history, wallet activity and token metadata |

## Get started

Create a free key in the [console](https://triport.io/app), then make your first call:

```bash
curl https://triport.io/r/<YOUR_KEY>/sol \
  -H "Content-Type: application/json" \
  -d '{"jsonrpc":"2.0","id":1,"method":"getSlot"}'
```
