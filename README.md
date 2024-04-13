# AVAX-1

## Avalanche DeFi Kingdom Clone

Welcome to the Avalanche DeFi Kingdom Clone project. This repository contains all the necessary components to set up your own EVM subnet on the Avalanche network and deploy foundational smart contracts, including an ERC20 token and a Vault contract. These contracts are integral to building a decentralized finance (DeFi) game inspired by DeFi Kingdoms.

## Project Overview

This project aims to demonstrate how to create a custom EVM-compatible subnet on Avalanche and utilize it for deploying DeFi applications. By following this tutorial, you will learn how to:

- Set up an EVM subnet on the Avalanche network.
- Deploy an ERC20 token contract as the native currency of your game.
- Deploy a Vault contract to manage game economics and interactions.
- Connect and test your contracts through Metamask.

## Prerequisites

Before you begin, make sure you have the following installed:
- [Node.js](https://nodejs.org/en/download/)
- [AvalancheGo](https://github.com/ava-labs/avalanchego)
- [Metamask](https://metamask.io/) extension for your browser
- [Remix IDE](https://remix.ethereum.org/) for deploying smart contracts

## Installation

### Step 1: Set up AvalancheGo

Clone the AvalancheGo repository and follow the setup instructions:

```bash
git clone https://github.com/ava-labs/avalanchego.git
cd avalanchego
./scripts/build.sh
```

### Step 2: Create a Custom EVM Subnet

Refer to the detailed steps in the [Avalanche documentation](https://docs.avax.network/) to set up your subnet. Ensure you configure it to be EVM-compatible.

### Step 3: Connect to Metamask

- Open Metamask and add your custom EVM subnet by entering the network details. You will need the RPC URL and Chain ID from your subnet setup.

### Step 4: Deploy Smart Contracts

Navigate to the `contracts` folder and use Remix IDE to compile and deploy the smart contracts.

```bash
cd contracts
# Open Remix, connect to your subnet in Metamask, and deploy the contracts
```

## Usage

Once deployed, you can interact with the smart contracts through Metamask or a custom frontend. See the `examples` directory for scripts demonstrating how to interact with the contracts programmatically.

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Thanks to Avalanche for the comprehensive documentation and tools.
- Inspired by the DeFi Kingdoms game and its innovative use of blockchain technology.

---

Feel free to adjust the content as per the actual directory structure and specific details of your project. This README template will guide contributors and users through setting up and using your DeFi Kingdom clone on Avalanche.
