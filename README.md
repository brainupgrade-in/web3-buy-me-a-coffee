# Web3 Buy Me A Coffee - A Blockchain Donation Platform

Welcome to the "Web3 Buy Me A Coffee" repository, an innovative project that leverages blockchain technology to enable content creators to receive donations in Ethereum. This decentralized application (dApp) simplifies the process of sending and receiving 'coffee' as a token of appreciation, using Ethereum smart contracts for secure and transparent transactions.

## Features

- **Ethereum Integration**: Fully integrated with the Ethereum blockchain for secure transactions.
- **Smart Contract Functionality**: Utilizes smart contracts for handling coffee donations.
- **MetaMask Support**: Easy connection with MetaMask for a seamless user experience.
- **Test Network Deployment**: Deployed on the Sepolia test network for safe and risk-free testing.
- **User-Friendly Interface**: Simple and intuitive web interface for both donors and receivers.

## Technology Stack

- **Solidity**: For writing smart contracts.
- **Ethereum**: As the blockchain platform.
- **MetaMask**: For wallet management and transactions.
- **Alchemy**: To interact with the Ethereum blockchain.
- **Hardhat**: For smart contract deployment and testing.
- **React**: For the frontend web application.

## Getting Started

### Prerequisites

- Node.js and npm installed.
- MetaMask browser extension.
- An Alchemy account for blockchain interaction.

### Setup

1. **Clone the Repository**

```bash
git clone https://github.com/brainupgrade-in/web3-buy-me-a-coffee.git
cd web3-buy-me-a-coffee
```

2. **Install Dependencies**

Navigate to the contract and app directories to install npm packages.

```bash
# Install dependencies for smart contracts
cd BuyMeACoffee-contracts
npm install

# Install dependencies for the web application
cd ../app
npm install
```

### Deploying Smart Contracts

1. **Configure Environment**: Set up your `.env` file in `BuyMeACoffee-contracts` with your MetaMask and Alchemy credentials.

2. **Deploy Contracts**:

```bash
npx hardhat run scripts/deploy.js --network sepolia
```

### Running the Application

```bash
# Navigate to the app directory
cd app

# Start the application
npm start
```

## Contributing

We welcome contributions from the community! Whether it's a bug fix, new feature, or additional documentation, your contributions are greatly appreciated. Please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file for more details on how to contribute.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to Alchemy for providing the tools necessary to interact with the Ethereum blockchain.
- Gratitude to the Ethereum community for resources and support.

---

Feel free to dive into the project, explore the code, and contribute to the exciting world of blockchain development. Happy coding!
