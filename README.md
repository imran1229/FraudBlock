# FraudBlock 🚫🔗

A **Blockchain-based Fake Product Detection System** that uses **QR codes** and **Ethereum smart contracts** to verify product authenticity.

![Last Commit](https://img.shields.io/github/last-commit/imran1229/FraudBlock)
![Tech](https://img.shields.io/badge/Built%20With-Solidity%2C%20Web3.js%2C%20Truffle-blue)

---

## 📌 Project Overview

FraudBlock helps consumers verify the authenticity of products by scanning QR codes linked to data stored on the blockchain. It prevents counterfeiting using smart contracts and decentralized technology.

---

## 🔧 Tech Stack

- **Blockchain**: Ethereum, Solidity, Ganache
- **Smart Contract Management**: Truffle
- **Frontend**: HTML, CSS, JavaScript
- **Web3 Integration**: Web3.js, MetaMask
- **Backend**: Node.js

---

## 🚀 How It Works

1. Manufacturer registers a product on the blockchain.
2. A QR code is generated with product data.
3. Consumers scan the QR code to verify authenticity via MetaMask-connected frontend.
4. Blockchain verifies and displays product legitimacy.

---

## 📽️ Demo Video

[![Watch the Demo](https://img.youtube.com/vi/F01t48jT5wQ/0.jpg)](https://youtu.be/F01t48jT5wQ)

---

## 🛠️ Setup Instructions

```bash
git clone https://github.com/imran1229/FraudBlock.git
cd FraudBlock
npm install
truffle compile
truffle migrate
npm run dev
