<p align="center">
  <img src="https://raw.githubusercontent.com/triport-labs/.github/main/profile/assets/banner-9-networks.png" alt="Triport Labs" width="100%">
</p>

<p align="center">
  <a href="https://triport.io"><img src="https://img.shields.io/badge/Website-88b4f5?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"></a>
  <a href="https://triport.io/docs"><img src="https://img.shields.io/badge/Docs-22d97a?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Docs"></a>
  <a href="https://x.com/triport_io"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"></a>
  <a href="https://t.me/triport_dev"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="mailto:sales@triport.io"><img src="https://img.shields.io/badge/Email-818cf8?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email"></a>
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
