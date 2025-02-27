# Solana trading-bot on Raydium and Pump.fun in Rust 🚀

## Overview

Solana trading bots are automated programs designed to swiftly identify and capitalize on new token listings within the Solana ecosystem, particularly on platforms like **Raydium** and **Pump.fun**.
Built for speed and efficiency, these bots monitor blockchain data for newly launched tokens and execute buy orders almost instantaneously. They are often coded in **Rust** due to its performance and security benefits. These bots can also be customized to implement various trading strategies, allowing users to take advantage of trends and arbitrage opportunities in the decentralized finance space.

---

### How To Run
1. Environment Variables Settings
```plaintext
PRIVATE_KEY=your_private_key_here
RPC_HTTPS=https://mainnet.helius-rpc.com/?api-key=your_api_key_here
RPC_WSS=wss://atlas-mainnet.helius-rpc.com/?api-key=your_api_key_here
DEVNET_RPC_HTTPS=https://devnet.helius-rpc.com/?api-key=your_api_key_here
RAYDIUM_LPV4=675kPX9MHTjS2zt1qfr1NYHuzeLXfQM9H24wFSUt1Mp8
SLIPPAGE=10
JITO_BLOCK_ENGINE_URL=https://ny.mainnet.block-engine.jito.wtf
JITO_TIP_STREAM_URL=ws://bundles-api-rest.jito.wtf/api/v1/bundles/tip_stream
JITO_TIP_PERCENTILE=50
YELLOWSTONE_RPC_HTTP=http://elite.rpc.solanavibestation.com/?api_key=your_api_key_here
YELLOWSTONE_RPC_WSS=ws://elite.rpc.solanavibestation.com/?api_key=your_api_key_here
JITO_TIP_VALUE=0.004
BUY_THRESHOLD=1000
SELL_THRESHOLD=300
```
2. Add the wallet address you want to block on a new line and save the file.
```
0x1234567890abcdef1234567890abcdef12345678
0xabcdef1234567890abcdef1234567890abcdef12
```
3. Run `raypump-bot.exe`.

![image](https://github.com/user-attachments/assets/dffc8e4b-cd00-4921-8488-e25230f4a31a)

---
## Donate

paypal : quangydungforever@gmail.com

