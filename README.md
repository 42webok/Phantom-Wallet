# Solana Send 0.1 SOL Web App

This is a simple web app that connects a user's Phantom Wallet and sends 0.1 SOL to a fixed recipient address on **Solana Mainnet**.

## 🌐 Live Features

- Connect Phantom Wallet
- Show wallet address
- Send 0.1 SOL to a hardcoded address
- Toast notifications for all actions

## 🛠 Setup

1. Get a free Solana Mainnet RPC endpoint from [QuickNode](https://www.quicknode.com)
2. Replace the line in `index.html`:
   ```js
   const rpcUrl = "https://solana-mainnet.quiknode.pro/YOUR-KEY-HERE/";


const staticRecipient = "YOUR_SOLANA_WALLET_ADDRESS";



