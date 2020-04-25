# Notes-Using-Blockchain



# What is Block chain?

A block chain is a decentralized, distributed, and oftentimes public, digital ledger that is used to record transactions across many computers so that any involved record cannot be altered retroactively, without the alteration of all subsequent blocks.

# Why Block Chain ?
        
Based on a peer-to-peer (P2P) topology, blockchain is a distributed ledger technology (DLT) that allows data to be stored globally on thousands of servers – while letting anyone on the network see everyone else's entries in near real-time. That makes it difficult for one user to gain control of, or game, the network.

# Requirements of project :-

1.     Node Js

2.     Ganache

3.     Truffle Framework

4.     Web3.js

5.     Metamask (Browser Extension)

6.     Solidity



# Node js :-

Node. js (Node) is an open source development platform for executing JavaScript code server-side. Node is useful for developing applications that require a persistent connection from the browser to the server and is often used for real-time applications such as chat, news feeds and web push notifications

You can install this directly from nodejs website
	https://nodejs.org/en/
			
OR  , Type the command in terminal

	brew install node
  
        OR
        
	sudo apt install node
  
To See version :-

	node -v


# Ganache :-

Ganache is a personal block chain for Ethereum development you can use to deploy contracts, develop your applications, and run tests. It is available as both a desktop application as well as a command-line tool (formerly known as the TestRPC). Ganache is available for Windows, Mac, and Linux.
          
   Ganache Installation :-
         You can download the App Image file directly from the below site
                  https://www.trufflesuite.com/ganache


after downloading the app Image file type following commands in terminal

      chmod a+x ganche.appimage

      ./ganche.appimage

These commands will launch the ganache application.


# Truffle :-

Truffle is a development environment, testing framework and asset pipeline for Ethereum, aiming to make life as an Ethereum developer easier. 
With Truffle, you get:
           1.  Scriptable deployment & migrations framework.
           2.  Network management for deploying to many
                Public &  Private Networks.

   Truffle Installation:-
   To install truffle type the below command in the terminal.
        
        npm install -g truffle

   To see the version of truffle type the below command in terminal
	      
        truffle version 


# Web3.js:-

 \web3. js is a collection of libraries which allow you to interact with a local or remote ethereum node, using a HTTP or IPC connection. The web3 JavaScript library interacts with the Ethereum blockchain. It can retrieve user accounts, send transactions and  interact with smart contracts.

   Web3.js installation :-
		To install web3.js on your machine just type the below command in the terminal

	        npm install web3



# Metamask :-
	
 MetaMask is a bridge that allows you to visit the distributed web of tomorrow in your browser today. It allows you to run Ethereum dApps right in your browser without running a full Ethereum node.
	
It is an extension, To add this extension to your browser just search for metamask in your browser extension store.


# Solidity  :-

Solidity is an object-oriented, high-level language for implementing smart contracts.
Smart contracts are programs which govern the behaviour of accounts within the Ethereum state.

 Solidity Installation :-
	Type the command in terminal

          sudo apt install solc
	
# Smart Contracts :-

Smart contracts allow the performance of credible transactions without third parties. These transactions are trackable and irreversible. A smart contract is a computer protocol intended to digitally facilitate, verify, or enforce the negotiation or performance of a contract.



# How to run the project :-

first compile the code :-        
            
            truffle compile
            
open ganche    :- See above for opening ganche

Migrate our smart contracts :- 

          truffle migrate --reset

Final Command :-  
              
              npm run dev







#         Code With Us 
# Please Like and Subscribe to Our Channel
