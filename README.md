# 🔐 Blockchain Node Quick Service

A blockchain node communication API module based on the QuickNode platform

## 📌 Project Overview
This project is a backend API module designed to interact with blockchain nodes
using the QuickNode platform.

Through the Endpoint module, it supports node RPC calls for
Bitcoin, Ethereum, and Tron networks, and provides wallet generation,
transaction signing, and signature verification functionalities.

The signing logic is implemented as an internal library and executed locally,
allowing signing and verification operations to be performed without any
network communication.

In addition, the Stream feature enables real-time monitoring of blockchain
transactions by filtering specified wallet addresses for each supported network
and delivering matched transaction results.

## 🛠 Tech Stack
- Language: TypeScript
- Runtime: Node.js
- Framework: Express
- Blockchain: Bitcoin, Ethereum, Tron
- Node Provider: QuickNode

## 📦 Libraries
- HTTP Client: axios
- Environment Management: dotenv
- Big Number Handling: big.js
- Ethereum SDK: ethers
- Tron SDK: tronweb
- Server Framework: express, body-parser
