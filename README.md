# Ethers Storage: A Simple Application

A study project on how Blockchain works. This simple application is built using [Solidity](https://docs.soliditylang.org/en/v0.8.15/), [Node.js](https://nodejs.org/en/) and [Ethers.js](https://docs.ethers.io/v5/) library.

[Alchemy](https://www.alchemy.com/) is also used to connect to Rinkeby Testnet.

## Key Features

- Store your favorite number
- Display your favorite number
- Apply Ethers.js encrypting function to store private key

## Building

**Clone this directory**

```
git clone git@github.com:nvtrinh2001/ethers-simple-storage.git
```

**Compile**

```
yarn compile
```

**Preparation for deployment**

- Install dependencies:

```
yarn
```

- Go to Alchemy website to get the RPC_URL HTTPS key.
- Put the Alchemy key and your MetaMask private key in the .env file.
- Create an encrypted key:

```
node encryptKey.js
```

- Now you can delete your MetaMask private key from your environment file.

**Deployment**

```
node deploy
```

Transaction address will be generated in Terminal.
