# 🔴 WARNING: Beta Release 🔴

-   This library is under development and there might be frequent breaking changes.

# Metal Wallet SDK (Beta)

Metal wallet SDK is a typescript library for creating and managing decentralized wallets.

It provides high level methods to transact on Metal's primary networks: X, P and C.

Wallet types supported:

-   Singleton Wallets
-   Ledger Wallets
-   Mnemonic Wallets
-   Public Mnemonic Wallets (XPUB)

Using the metal-wallet-sdk developers can:

-   Receive and send tokens and NFTs.
-   Cross chain transfer
-   Validation & Delegation
-   Create keystore files from wallet instances
-   Get transaction history of wallets
-   Mint NFTs on the X chain

## Installation

With npm

`npm install --save @metalblockchain/metal-wallet-sdk`

or yarn

`yarn add @metalblockchain/metal-wallet-sdk`

## Local build

1. Clone the repository.
2. Install dependencies `yarn install`
3. Run for development `yarn start`

## Webpack

For Webpack version 5 and above you must use this plugin with it. https://www.npmjs.com/package/node-polyfill-webpack-plugin

## Docs

Can generate documentation with `yarn docs` and open `docs/index.html` in a browser.
