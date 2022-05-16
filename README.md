# NFT(ERC-721) Smart Contract

## Platform

### Hardhat
Hardhat is next-generation Ethereum tooling.

### Local Development/Test
To deploy this project and test on local:
Install the Ganache Tool.

## Online Deployment

### Requirements
#### Node.js
#### .env File
Includes:<br />
-PRIVATE_KEY(wallet private key)<br />
-PRIVATE_KEY_LOCAL(for ganache test)<br />
-ALCHEMY_API_KEY<br />
-ETHERSCAN(ETHERSCAN API KEY)<br />

## Steps

#### npm install
#### npx hardhat run scripts/deploy.js --network ropsten(for test)
#### npx hardhat verify --network ropsten(for test) 0x1234567890"# nft-smart-contract" 
