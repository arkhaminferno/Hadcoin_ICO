# Hadcoin_ICO
Hadcoin Initial Coin Offering issuing 1 millions tokens for the investors to be able to buy them or even sell them written in solidity using [Remix-Ethereum IDE](https://remix.ethereum.org) 

## What is an Initial Coin Offering?
Initial Coin Offering (ICO) is the cryptocurrency’s world public crowdsale. Whenever a project wants to launch a new coin or dApp, they can conduct an ICO to attract investors into their ecosystem.


## Requirements 

- Requires Ethereum Wallet Software [MyEtherWallet](https://github.com/kvhnuke/etherwallet)
 
>preferred etherwallet-v3.11.2.4.zip is the smaller package containing the gh-pages branch aka MyEtherWallet.com

-Requires Local Ethreum Blockchain software to run tests, execute commands, [Ganache](https://www.trufflesuite.com/ganache)


## Deploying Smart Contract on MyEtherWallet
  -Start Ganache Software
  -Unzip MyEtherWallet and open index.html  
  -Goto new wallet tab  
  -Setup custom node  
   
  -Goto Contracts Tab and click on Deploy contract  
  -Open hadcoin_ico.sol file on Remix IDE  
  -goto details and copy the Bytecode from details  
  -now,paste the copied Bytecode into myetherwallet deployed contracts tab
  -it will automatically generate Gas Limit and then click on private key option.
  -Open ganache and copy Private key from any of the accounts and then paste it.
  -click on sign Transaction and then Deploy Contract.
  -Open ganache and check if the blocks are getting created on the blocks tab if it is happening then you are good to go.
   
 ## Interacting with Smart Contract on myEtherWallet
 
    -click on the latest block which is created and copy contract address of that block on ganache.  
    -Now,Goto Interact with Contract Tab  
    -Paste contract address  
    -Copy ABI deatils from Remix Ethereum IDE and paste it into MEW tab  
     Click on Access and BOOM! you can now use the functions to interact with the ICO. 
     
      - Buy Hadcoin tokens
      - Check Total Hadcoins Bought
      - Check Equivalence price to USD (In this ICO 1000 tokens equals 1 Dollars)
      - Sell Hadcoin Tokens
    
    
    
    
 
 
