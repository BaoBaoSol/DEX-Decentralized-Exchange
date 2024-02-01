# Build our own decentralized exchange



## Requirements For Initial Setup
- Install [NodeJS](https://nodejs.org/en/), should work with any node version 
- Install [Truffle](https://www.trufflesuite.com/docs/truffle/overview), In your terminal, you can check to see if you have truffle by running `truffle version`. To install truffle run `npm i -g truffle`. Ideal to have truffle version 5.4 to avoid dependency issues.
- Install [Ganache](https://www.trufflesuite.com/ganache).

##Setting Up

### 1. Clone/Download the Repository

### 2. Customize your front end 

### 3. Start Ganache

### 4. Install Dependencies:
` npm install`

### 5. Migrate Smart Contracts
` truffle migrate --reset`

## Instructions:



So for those of you who don't know, what is a decentralized exchange?

So it's basically a platform where you can buy, sell and trade cryptocurrencies which.

Is.

Totally automated.

So we're going to use the Truffle framework and the local blockchain ganache, and we.

Will also need to have the.

Metamask extension installed and an account created.

So here we are on the GitHub repository.

So within this repository you will have everything you need to build your own centralized exchange.

So there's all the migration file, the test and the Truffleconfile.

So first of all, for realizing this project you will have to install node GS, install truffle and also install the local blockchain ganache.

That is a very, very easy tool to use.

You will also need to add the Metamask extension and create an account so you can easily copy and paste this URL into a terminal and get this repository.

And that is what we're going to do right now.

So I will open Visual Studio, I will open a new terminal and I will tap git clone.

Going back to the repository.

Just copy this link going back to the terminal and past it here.

All right, so we have cloned this repository and now we want to open this folder, so we'll just tap CDTEX.

Now I will also open it on Visual Studio.

So I will do open folder decks, select folder, reopen my terminal.

So what we have here is our truffleconfig file.

We have the packages on for all the scripts that we're going to use.

We also have our migration file that will be useful for deploying, compiling and deploying smartcontract.

So as you can see here our contracts are located on our source folder because we want the front end and the API to have access to the contract within the source folder.

So now what we need to do is just install our package manager.

So I will tap NPM install.

Alright great so our package manager is installed.

So now the next step to do is open our Ganache local blockchain and Click to quick start.

Now you will see that the local blockchain has provided us with 10 accounts that each have 100 fake eaters.

So those eaters are not on the main net, they are part of a test net.

So now what we want to check is if our network is the same that our local blockchain ganache is using.

So you have to check if this number match with your truffle config file with the port here.

So here we are 7545 so it's the same.

Now what you want to do next is going to your browser and open your metamask.

So what you want to do next is just going here and Click to add network.

So here you can type ganache then go back to ganache application and copy this RPC server and then pass it here on the new RPC URL.

So for the chain ID you have to put 13 37.

So for the currency symbol you can put ETH because we are going to use ethers and you can save the network now.

So now what you want to do is import an account from your local box and ganache to your meta mask.

So you will need to go here and click on import account.

Now you have to go back to Ganache and show this private key, copy it and past it into your meta mask.

So here we go we have 100 ether on meta mask.

Now what you want to do is going back to your terminal and type 4 fold migrate so it will automatically compile and deploy your contracts.

OK, great.

So the migration.