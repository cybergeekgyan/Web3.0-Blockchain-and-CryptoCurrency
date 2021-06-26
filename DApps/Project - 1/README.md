## Objective 

* Building a very simple escrow-like smart contract that allows us to deposit ether into the contract only to be released by a third party to its eventual destination. 

* Keep in mind, of course, that it's exactly these kind of third parties that the blockchain's going to allow us to circumvent, but we're doing it this way for simplicity. 

* We could easily modify this to have the funds released based on some kind of off-chain event that won't require any user interaction. 

* We're then gonna build a user interface that will allow us to send ether from one address to another, check the balance that's being stored, see who the approver is, and 

* finally enable the approver to approve the transaction. 

* **This simple dapp will allow you to see how you can write dapps and interact with the Ethereum blockchain**

## Setup

**Server Setup

- Install Truffle Test Server 
         
      sudo install -g truffle
      
- Instal Ganache 
    - https://www.trufflesuite.com/ganache

- Install Metamask


start truffle local server 
 - for windows 

       truffle.cd develop
       
 - for others
 
       truffle develop 
    
