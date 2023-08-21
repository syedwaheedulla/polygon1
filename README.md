# Polygon-Advanced-Module-1

## Description

Polygon-Advanced-Module-1 is the inaugural project within the Polygon-Advance series. The project entails the deployment of a dedicated NFT collection on the Ethereum blockchain. The central tasks encompass mapping this collection to the Polygon network and executing the seamless transfer of assets using the Polygon Bridge.

## Getting Started

Follow these steps to begin your engagement with the project:

1. **Acquire the Codes:** Download the complete repository to access not only the main project but also supplementary content.

2. **Access Project Directory:** Navigate to the "Poly_Proof" project directory where the core implementation resides.

3. **Dependency Installation:**
4. Install required dependencies by running:
   ```bash
   npm install
Running Tests: After installing dependencies, initiate testing using:
   ```bash
   npx hardhat test
Deploying the ERC721 Contract: Before deployment, rename ".env.example" to ".env" and add your wallet's private key as: PRIVATE_KEY='your wallet private key'. Deploy the ERC721 contract to the Goerli Ethereum Testnet:
  '''bash
npx hardhat run scripts/deploy.js --network goerli
Batch Minting NFTs: Execute this command to perform batch minting of NFTs with the deployed ERC721 contract:
npx hardhat run scripts/batchMint.js --network goerli
Approval and Deposit to Polygon Mumbai: Transition minted NFTs from Ethereum to Polygon Mumbai network by running:
npx hardhat run scripts/approveDeposit.js --network goerli
**Author**
Syed Waheedulla

**License**
This project is licensed under the MIT License. You are free to duplicate and adapt the project for your needs.




  
