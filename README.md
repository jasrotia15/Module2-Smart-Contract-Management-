# Module2-Smart-Contract-Management

This repository contains a simple Ethereum smart contract and a frontend interface for managing bank-like functionalities on the blockchain.


## Overview

This project showcases a basic implementation of a decentralized bank using Ethereum smart contracts. Users can interact with the smart contract to set account names, check balances, and transfer funds. The frontend provides a user-friendly interface for these operations.


### Functions

- `setAccountName`: Allows users to set their account names.
- `getAccountName`: Retrieves the account name of the caller.
- `transferFunds`: Transfers Ether to another address.
- `getBalance`: Retrieves the Ether balance of the caller.


### Features

- Connect wallet to interact with the blockchain.
- Display account name, address, and balance.
- Change account name and transfer funds functionalities.

## Technologies Used

- **Solidity**: Programming language for writing smart contracts.
- **Web3.js**: Library for interacting with Ethereum blockchain.
- **Bootstrap**: CSS framework for frontend design.
- **Ethers.js**: JavaScript library for Ethereum interaction.

## Getting Started

To run this project locally or deploy it:

### Prerequisites

- Install MetaMask or any Ethereum-compatible wallet extension in your browser.
- Connect to an Ethereum network (Mainnet, Ropsten, Rinkeby, etc.) using MetaMask.

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/NikhTheTech/Smart-Contract-Management
   ```

**Follow these steps to get the project up and running**
  1. Download or clone the project.
  2. Install the dependencies by running `npm install`.
  3. Start the local blockchain using Hardhat by running `npx hardhat node`.
  4. Open new terminal and deploy the Bank contract `npx hardhat run --network localhost scripts/deploy.js`
  5. Start the development server by running `npm run dev`.

## Contributing

Contributions are welcome! Please fork this repository, make your changes, and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.
