# Photofy
Photofy is a decentralized photo/image sharing platform. Secured by blockchain, where viewers can provide contributions/tip to authors in cryptocurrency.

Most of the image/photo sharing application that we use today are highly centralized, this central authority can remove your posts without any prior notice
and most of them does not provide any contributions or incentives to the content posters. 
Photofy platform users can directly provide tips to the contributor of any specific content whom they would like to support. This is done anonymously, ensuring sufficient privacy and also without the need for middle-men or intermediaries. Anyone can post image/photo with discription, this post can be of educational or entertainment value, which are stored in a decentralized, public and transparent form by virtue of blockchain technology. The uploaded files are stored using web3.storage with data persisted by Filecoin and accessible over IPFS. Tips are paid in ether.
The Smart Contracts are currently deployed on the Ganache Testnet and also can be deployed on any EVM-compatible chain.

Inspired by
Dapp University.

## Tech Stack Used

- Solidity
- Truffle Suite
- Ganache
- web3.storage - IPFS and Filecoin
- ReactJS
- react-bootstrap
- web3react
- Metamask
- ether

## Photofy Smart Contract Deployment

## Run Locally

### Pre-Requisites

- Truffle Suite
- Ganache CLI

```
$ npm install -g truffle
$ npm install -g ganache-cli
```  
Clone the project

```
$ git clone 
$ cd Photofy
```
### Setting up a local Blockchain
Install dependencies

```
$ npm install
```

Compile Smart Contracts

```
$ truffle compile
```

Run ganache

```
$ ganache-cli
```  

Run migrations to deploy the smart contracts

```
$ truffle migrate
```  

### Setting up the client

Start the App

```
$ npm start
```

Visit https://localhost:3000/ to view the app


## Running Tests

To run tests, run

```
  truffle test
```

![Screenshot 2022-05-08 at 12 43 18 AM](https://user-images.githubusercontent.com/98373232/167268513-fcd172e7-ba03-4748-b693-cd20887fd4ef.png)
