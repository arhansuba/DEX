# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```
# Basic DEX
In this project, I've developed a decentralized exchange (DEX) similar to Uniswap v1 on a testnet. The decentralized exchange allows users to swap ERC-20 tokens directly from their wallets without the need for a central authority
For the RPC_URL - Go to QuickNode and sign up for an account if you haven't already. If you have a pre-existing Sepolia RPC URL there, you can continue using the same one. Copy that and replace the value in the .env file with  the link. If you don't already have one, create an Endpoint on QuickNode and select Ethereum and then the Sepolia Testnet. After creating the endpoint, copy the HTTP Provider link from there and add that to the RPC_URL in the .envfile.

For the PRIVATE_KEY - you need to export this from MetaMask. Take this time to double check you aren't exporting an account that has any funds on Ethereum Mainnet (or any other mainnet). Use a development account only to avoid making mistakes and accidentally leaking your private key with funds on it and having them  stolen. Once you have the private key, replace the placeholder value in the .env file with it.

For the ETHERSCAN_API_KEY - sign in/sign up to Etherscan at https://etherscan.io/ and then generate/re-use an API Key from there and add it to the .env.

