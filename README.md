# Ethereum Fraud Detection 🚀

Fraudulent and legitimate transactions on the Ethereum blockchain are analyzed in this project. Ethereum, launched in 2015 by **Vitalik Buterin** and **Gavin Wood**, is the second-largest cryptocurrency by market capitalization, accounting for over 17% of the $1.2 trillion global crypto market.

While Bitcoin focuses on being a medium of exchange, Ethereum serves as a **decentralized computing network** that supports smart contracts and dApps (decentralized applications).

---

## Dataset Overview 📊

| **Column Name**                       | **Description**                                                                 |
|---------------------------------------|---------------------------------------------------------------------------------|
| `Index`                               | Row index number                                                               |
| `Address`                             | Ethereum account address                                                       |
| `FLAG`                                | Indicates if the transaction is fraudulent (`1` for fraud, `0` for legitimate) |
| `Avg min between sent tnx`            | Average time (minutes) between sent transactions                               |
| `Avg min between received tnx`        | Average time (minutes) between received transactions                           |
| `Time Diff between first and last`    | Time difference between the first and last transaction (minutes)               |
| `Sent_tnx`                            | Total number of sent normal transactions                                       |
| `Received_tnx`                        | Total number of received normal transactions                                   |
| `NumberofCreated_Contracts`           | Total contracts created by the account                                         |
| `UniqueReceivedFrom_Addresses`        | Unique addresses that sent transactions to the account                         |
| `UniqueSentTo_Addresses`              | Unique addresses that received transactions from the account                   |
| `Min/Max/Avg Value Received`          | Minimum, maximum, and average Ether received                                   |
| `Min/Max/Avg Value Sent`              | Minimum, maximum, and average Ether sent                                       |
| `TotalEtherSent/Received`             | Total Ether sent and received by the account                                   |
| `TotalTransactions`                   | Total transactions, including contract creation                                |
| `ERC20-related columns`               | Transaction details for ERC20 tokens                                           |

---

## What is ERC20? 🤔

ERC20 is a **standard for fungible tokens** on the Ethereum blockchain. It acts as a guide for creating tokens that are interchangeable with other smart contract tokens.

### Key Differences Between ETH and ERC20:
- **ETH**: The native cryptocurrency of Ethereum, used for paying transaction fees (gas) and enabling operations.
- **ERC20**: Tokens created on Ethereum for specific use cases, such as stablecoins or decentralized finance (DeFi) platforms.

### Use Cases for ERC20 Tokens:
1. **DeFi Platforms**: Power decentralized financial applications.
2. **Stablecoins**: Pegged tokens like USDT and USDC.
3. **Gaming and NFTs**: Support in-game currencies and digital collectibles.

---

## Project Goals 🛠️

1. **Analyze Transaction Patterns**: Extract meaningful insights from Ethereum transactional data.
2. **Detect Fraudulent Transactions**: Build a machine learning model to classify transactions as fraud or legitimate.
3. **Visualize Key Metrics**: Display patterns and trends using visualizations.

---

## Visualizations 🌌
![Screenshot 2024-11-23 124051](https://github.com/user-attachments/assets/e34ce503-6bca-4f66-838d-403ba268c086)


---

## How to Contribute 🤝

1. Fork the repository.
2. Clone your fork:
   ```bash
   git clone https://github.com/rohithprem18/ethereum-fraud-detection.git
