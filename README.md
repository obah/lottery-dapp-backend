# Description
This is a lottery game project built on the blockchain with chainlink.

## How it works
The user stakes an amount (set to 0.1 eth), picks a number and plays a raffle draw and if the number is chosen, the user wins.

For the game to be fair to all, the raffle draw must be truly random. To ahieve this on the blockchain, chainlink VRF is used.


# Getting started

## Requirements

- Git
- Nodejs
- Yarn
- Hardhat

## Quick start
```
git clone https://github.com/obah/lottery-dapp-backend.git
cd lottery-dapp-backend
yarn
deploy chainlink mocks and lottery contract on hardhat
```

For better experience, run the project with the [frontend](https://github.com/obah/lottery-dapp-frontend.git)

# Supported Chains

Goerli testnet
Ethereum mainnet (support coming)
Polygon mainnet (support coming)

# Tools used

Solidity
Javascript
NodeJs
Ethers.js
Hardhat
Chainlink
Alchemy
