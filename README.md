# VIA Bridge UI

A simple React application that demonstrates how to bridge BTC from Bitcoin to the VIA network using OP_RETURN deposit transactions with the [sats-connect](https://docs.xverse.app/sats-connect) API and [Xverse wallet](https://www.xverse.app/).

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Overview
This application allows users to:
- Connect to Xverse wallet
- Send a small amount of Bitcoin to the VIA Bridge address
- Include an EVM address as OP_RETURN data for receiving funds on L2 (VIA network)
- Receive the change amount back to the wallet

## Prerequisites
- Node.js (v16 or higher)
- [Xverse wallet extension](https://www.xverse.app/download) installed in your browser
- Some tBTC in your Xverse wallet (check [Testnet Faucet](https://bitcoinfaucet.uo1.net/send.php))

## Setup

1. Clone the repository
2. Install dependencies:
```
npm install
```
3. Run the application
```
npm start
```
4. Build for Production
```
npm run build
```
This builds the app for production to the `build` folder, optimized for best performance.
