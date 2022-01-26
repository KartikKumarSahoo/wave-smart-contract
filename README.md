# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

## How to test the smart contract locally
```shell
npx hardhat scripts/run.js
```

## How to deploy the smart contract locally
```shell
npx hardhat scripts/deploy.js --network localhost
```

## How to deploy the smart contract in testnet (rinkeby)
```shell
npx hardhat scripts/deploy.js --network rinkeby
```

## NOTE
After deploying the contract to any blockchain (testnet/mainnet) we get one address, this address is to be used in the frontend application along with the file under artifacts/contract/WavePortal.json

Post deploy things will look like bolow
```shell
➜ npx hardhat run scripts/deploy.js --network rinkeby
Deploying contracts with account:  0x9C8C1F7aD7C1fDb9349a68f14d9Fc34333d6c659a
Account balance:  18928665620309299
WavePortal address:  0x6909e506FBEc9F7635226b0b73eC2AAee7de6489
```

## Hardhat commands
Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```
