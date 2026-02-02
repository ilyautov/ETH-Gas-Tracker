# Privacy Policy for Multi-Chain Gas Tracker

**Last updated:** February 2, 2026

## Overview

Multi-Chain Gas Tracker ("the Extension") is a browser extension that helps users track gas prices on blockchain networks. We are committed to protecting your privacy and being transparent about our data practices.

**In short: We do not collect, store, or transmit any personal information.**

## Data Collection

### What We DO NOT Collect

- ❌ Personal identification information
- ❌ Wallet addresses or private keys
- ❌ Transaction history
- ❌ Browsing history
- ❌ IP addresses
- ❌ Device identifiers
- ❌ Location data
- ❌ Usage analytics or telemetry

### What We DO Store Locally

The Extension stores the following data **only on your device** using Chrome's local storage API:

- **User preferences:** Theme selection, notification settings, alert thresholds, selected network
- **Price history:** Historical gas prices for chart display (stored locally for up to 7 days)
- **Custom operations:** User-defined transaction types with custom gas limits

This data:
- Never leaves your device
- Is not synced to any cloud service
- Is not accessible to us or any third party
- Can be deleted by uninstalling the extension or clearing browser data

## Network Requests

The Extension makes network requests to the following services:

### Blockchain RPC Endpoints
To fetch current gas prices, the Extension sends standard JSON-RPC requests to public blockchain nodes:
- Ethereum: eth.llamarpc.com, 1rpc.io, ethereum.publicnode.com
- Arbitrum: arbitrum.llamarpc.com, arb1.arbitrum.io
- Optimism: optimism.llamarpc.com, mainnet.optimism.io
- Base: base.llamarpc.com, mainnet.base.org
- Polygon: polygon.llamarpc.com, polygon-rpc.com

These requests contain only the gas price query method (`eth_gasPrice`, `eth_feeHistory`) and do not include any user-identifiable information.

### Price Data
Token prices in USD are fetched from CoinGecko's public API (api.coingecko.com). No user data is sent with these requests.

## Permissions Explained

| Permission | Purpose |
|------------|---------|
| `storage` | Store user preferences and price history locally on your device |
| `alarms` | Schedule periodic background updates of gas prices |
| `notifications` | Send browser notifications when gas drops below your set threshold |
| `host_permissions` | Access blockchain RPC endpoints and CoinGecko API for price data |

## Third-Party Services

We do not use any third-party analytics, advertising, or tracking services. The only external services contacted are the blockchain RPC endpoints and CoinGecko API listed above, solely for fetching gas and token price data.

## Data Security

Since all user data is stored locally on your device and never transmitted to external servers, security is maintained by your browser's built-in protections. We recommend:
- Keeping your browser updated
- Using the official extension from Chrome Web Store

## Children's Privacy

The Extension does not knowingly collect any information from children under 13 years of age.

## Changes to This Policy

We may update this Privacy Policy from time to time. Any changes will be reflected in the "Last updated" date at the top of this document. Continued use of the Extension after any changes constitutes acceptance of the updated policy.


## Contact

If you have any questions about this Privacy Policy, please contact:
- Email: ilyautov@gmail.com

---

## Summary

| Question | Answer |
|----------|--------|
| Do you collect personal data? | No |
| Do you track users? | No |
| Do you sell data? | No |
| Do you use analytics? | No |
| Where is data stored? | Only on your device |
| Can I delete my data? | Yes, uninstall the extension or clear browser data |
