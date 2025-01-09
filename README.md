# African Bullion Coin (ABC)

A decentralized cryptocurrency backed by Africa's vast gold reserves, ensuring stability and transparency in digital financial systems.

![African Bullion Coin Logo](assets/logo.png)

## Features
- **Gold-Backed Stability:** Ensured value tied to African gold reserves.
- **Secure Transactions:** Powered by Ethereum blockchain.
- **Global Accessibility:** Borderless and inclusive.

## Technology Stack
- **Blockchain:** Ethereum-based smart contracts.
- **Programming Language:** Solidity.
- **Tools:** Hardhat, OpenZeppelin libraries.

## Installation

### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/) and npm
- [Hardhat](https://hardhat.org/)
- [Git](https://git-scm.com/)

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/africanbullioncoin/abc.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd abc
   ```

3. **Install dependencies:**
   ```bash
   npm install
   ```

4. **Compile the smart contracts:**
   ```bash
   npx hardhat compile
   ```

5. **Run tests:**
   ```bash
   npx hardhat test
   ```

6. **Deploy the contracts to a local blockchain:**
   ```bash
   npx hardhat node
   ```
   In a separate terminal, run:
   ```bash
   npx hardhat run scripts/deploy.js --network localhost
   ```

## Usage

### Interacting with the Smart Contract
1. Use Hardhat's console:
   ```bash
   npx hardhat console --network localhost
   ```
2. Interact with the deployed contract using the ABI and address.

### Frontend Integration
- Use the deployed contract's address and ABI in your frontend application.
- Libraries like `web3.js` or `ethers.js` can facilitate interaction with the blockchain.

## Contributing

We welcome contributions to the African Bullion Coin project. Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to your forked repository:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request to the `main` branch.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For inquiries, contact us at (mailto:support@africanbullioncoin.co.za ) or visit our [official website](https://africanbullioncoin.co.za).

---

*Empowering Africa's digital financial ecosystem through innovation and gold-backed stability.*

