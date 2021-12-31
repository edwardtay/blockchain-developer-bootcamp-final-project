# Ropsten-Retrieval

## Project URL

https://github.com/edwardtay/blockchain-developer-bootcamp-final-project/

## Project Description

Ropsten Retrieval is a smart contract with a simple interface that lets anyone store texts on the blockchain. As a proof of concept project, Ropsten Retrieval gives everyone easy access to Ethereum. 

## Workflow
	
1. Connect your Metamask wallet to the website.

2. Change your wallet network to **Ropsten** Test Network

3. Input a message, and the number of days you would like the message to be stored for.

4. Click the submit message button and pay for the transaction through the Metamask.

5. Input the ID corresponding to your message and click the Retrieve Message button to see message. 

## Running the project locally

### Prerequisites

- Node.js >= v14
- Truffle and Ganache
- VScode with Live Server extension

### Directory structure

- `docs`: Project's frontend
- `contracts`: Smart contracts that are deployed in the Ropsten Test Net
- `migrations`: Migration files for deploying smart contracts.
- `test`: JS tests for the smart contracts.

### Contracts 

1. Run `npm install` to install dependencies

2. Run `ganache-cli` in a terminal, port 8545 is the default

3. Run `truffle migrate` in the root directory

4. `truffle console`

5. Run `test`

### Frontend

1. `cd docs/`
	
2. `code .`

3. Select `index.html`, right click and select Open with Live Server

4. Make sure you're running ganache and open http://127.0.0.1:5500 if it isn't already

5. Change Metamask network to Localhost 8545, then you can start interacting with the contract.


## Deployed URL
- https://61cf2781c249291152dcadf9--festive-leavitt-f94ad6.netlify.app
- https://blockchain-developer-bootcamp-final-project2-gbesdhlmi.vercel.app
- https://wandering-credit-3521.on.fleek.co

## Screencast Link
https://youtu.be/6redu5Obv-s

## Ethereum wallet address
0x38430336153468dcf36Af5cea7D6bc472425633A

