# LedgerFlow

LedgerFlow is our ETHGlobal hackathon submission designed to improve the developer and user experience when building with Ledger hardware wallets. Our project addresses two key bounties from Ledger: **Hardware Integrations** and **Documentation Improvement**.

---

## 🔧 Track 2 – Hardware Integration

### ✅ Contribution to Ledger's app-ethereum (Ledger Stax and Flex)

We contributed to the [`app-ethereum`](https://github.com/LedgerHQ/app-ethereum) codebase to improve the **clear signing** feature. Specifically, our pull request ([#835](https://github.com/LedgerHQ/app-ethereum/pull/835)) enhances transaction transparency by supporting **multiple blockchain explorers**.

#### 🔄 Summary of Changes:
- **Multi-Chain Explorer Support**: Added support for explorers on popular networks including **Arbitrum, Base, Optimism**, and more.
- **Dynamic Explorer Links**: Implemented a **chain ID to explorer URL** mapping to generate appropriate links for the scanned QR code.
- **Improved UI Messaging**: Updated clear signing text from "Scan to view on Etherscan" to the more generic "**Scan to view on explorer**", ensuring clarity across different networks.

These improvements enhance the **user experience** by ensuring the QR code redirects to a **valid, network-specific explorer URL**, allowing users to seamlessly verify their transactions on the correct chain.

---

## 📄 Track 3 – Documentation Improvement

👉 **[See detailed documentation improvements here](DocumentationImprovement/README.md)**

### 📝 Developer Experience Feedback


## 🔗 Related Resources

- 🔗 Pull Request: [LedgerHQ/app-ethereum#835](https://github.com/LedgerHQ/app-ethereum/pull/835)
