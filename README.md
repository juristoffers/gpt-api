# Ethereum Data Fetching API for ChatGPT Integration

This repository contains an Express.js server that provides endpoints designed for easy integration with ChatGPT, allowing the assistant to interact with the Etherscan API and fetch Ethereum balance data and beacon chain withdrawal transactions for a given Ethereum address.

## Features

1. **Get ETH Balance**: Fetch the current Ethereum balance of a specific address from the Etherscan API.
2. **Get Beacon Chain Withdrawal Transactions**: Retrieve the beacon chain withdrawal transactions for a given Ethereum address.

## Endpoints

All endpoints are designed to be called programmatically by ChatGPT, making them easy to integrate into conversations or tasks that require Ethereum data.

### 1. `/get-eth-data`

This endpoint fetches the balance of an Ethereum address.

- **Method**: `POST`
- **Request Body**: 
  ```json
  {
    "ethAddress": "0xYourEthereumAddress"
  }
