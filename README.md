# Decentralized Exchange
Decentralized Exchange basically a platform where you can buy, sell and trade cryptocurrencies which is Totally automated.

# Build our own decentralized exchange
Following these instructions, you can build your own Decentralized Exchange. First, install all the applications needed and then build your Decentralized Exchange. Make sure that the versions of the applications match your operating system. Otherwise, it will not work. Within this repository you will have everything you need to build your own centralized exchange.

## Requirements For Initial Setup
- Install [NodeJS](https://nodejs.org/en/), should work with any node version 
- Install [Truffle](https://www.trufflesuite.com/docs/truffle/overview), In your terminal, you can check to see if you have truffle by running `truffle version`. To install truffle run `npm i -g truffle`. Ideal to have truffle version 5.4 to avoid dependency issues.
- Install [Ganache](https://www.trufflesuite.com/ganache).
- Install Metamask extension and create an account.

## Instructions:

### 1. Clone/Download the Repository
- copy repository link form the code option on the top right corner.

### 2. Customize your front end 
- Open the repository on a editor(e.g Visual Studio)

### 3. Install Dependencies:
- write ` npm install` on your terminal.

### 4. Start Ganache
- open Ganache
- click Quick Start
- check is if your number match with your truffle config file with the port here that your local blockchain ganache is using.

### 5. Adding network to Metamask
- open Metamask
- click add network
- Fill out the form:
    RPC url - copy from Ganache
    Chain ID - 1337
    Currency symbol - ETH
- save the network

### 6. Import an account from your local blockchain Ganache to Metamask
- goto 'import account' on your Metamask
- put the private key form Ganache
- click import(You will see 100ETH on your Metamsk now)

### 7. Migrate Smart Contracts
- goto terminal again
- write ` truffle migrate`
- After migration is completed, write ` npm start`
- If a window opens on your browser, then it is working.

