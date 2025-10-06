# WalletConnect × Base (8453) — Mini Demo

A minimal **single-file HTML/JS** demo showing how to connect to **Base (chainId 8453)** via WalletConnect.

## How to use
1. Project ID is already set: `3cf7abc4898e8a61abfcdbcc9b57ad06`.
2. Open `index.html` in a browser → click **Connect** → select your wallet → connect to Base.
3. Click **personal_sign** to test a simple signature.

## What to capture (proof)
- Account in the format `eip155:8453:0x...`
- Chain displayed as **Base (8453)**
- A truncated `personal_sign` result (do not expose the full signature publicly).

## Notes
- Uses `@walletconnect/universal-provider@2` + `@walletconnect/modal@2` via ESM CDN.
- Inspired by WalletConnect/Reown documentation and examples.
