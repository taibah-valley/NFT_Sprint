# Sprint: Build Your Own Non-Fungible Token

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

## Sprint Map
| Appendix |
| ------ |
| Key Words |
| High Level Goals of this Sprint | 
| Getting Started and Project Set Up |
| The Project |
| Extra Credit |

## Key Words
- Smart contracts standards.
- Non-fungible token.
- ERC721
- ERC Ethereum request for comments
- Truffle
- Solidity
- Web3.0
- Ethereum
- CryptoKitties
- Smart contracts


## What Is The Non-Fungible Token ??
A non-fungible token (NFT) is a special type of cryptographic token which represents something unique; non-fungible tokens are thus not interchangeable. This is in contrast to cryptocurrencies like Bitcoin, and many network or utility tokens that are fungible in nature.

Non-fungible tokens are used to create verifiable digital scarcity. NFTs are used in several specific applications that require unique digital items like crypto-collectibles and crypto-gaming. Popular blockchain games like CryptoKitties make use of non-fungible tokens on the Ethereum blockchain NFTs are used to represent in-game assets, which are in control of the user instead of the game developer NFTs also find potential use in digital art, by helping prove authenticity and ownership

The Ethereum community has adopted the ERC-721 protocol as a standard for Non-Fungible Tokens on Ethereum. Projects like CryptoKitties, CryptoPunks and Decentraland follow the ERC-721 protocol for their NFTs.

Non-fungible tokens made their way into mainstream news when CryptoKitties went viral and subsequently raised a $12.5 million investment RareBits, a Non-Fungible Token marketplace and exchange raised a $6 million investment. Gamedex, a collectible cards game platform made possible by Non-Fungible Tokens raised a $800,000 seed round. The creation of the Non-Fungible Token protocol on the Ethereum blockchain has caused other blockchain projects such as NEO to begin development of their own non-fungible token standards.


## What Is ERC-721??
ERC-721 is a free, open standard that describes how to build non-fungible or unique tokens on the Ethereum blockchain. While most tokens are fungible (every token is the same as every other token), ERC-721 tokens are all unique. Think of them like rare, one-of-a-kind collectables.

## THE STANDARD
ERC-721 defines a minimum interface a smart contract must implement to allow unique tokens to be managed, owned, and traded. It does not mandate a standard for token metadata or restrict adding supplemental functions. 

## High Level Goals Of This Sprint
- Learn the defferince between the non-fungible tokens vs the normal token.
- Learn more about the smart contracts and implement a complex smart contracts.
- Learn how to use truffle framework to make your life as Ethereum developer more easier.
- Learn how to deal with your contract form your web app.
- Practice using web3 to control every thing on your contract.

## Getting Started And Project Set Up
Get the smart contracts starter 
- fork the repository that given to form the instructional team clone it to your computer 
- open the project folder and run npm install to install the node dependencies.
- open ganache and be sure to set the port in the settings to 8545 if you still don't have ganache installed on your machine you can install from [here]
- if you don't have truffle installed globaly on your machine you need to install it by writing this command on terminal ```npm install -g truffle```

## The Project
### Bare Minimum Requirements
- if you already have truffle installed globaly on your machine so run the smart contracts test using this command truffle test
- to make the test pass you need to modify the methods that is located in ```~/contracts/ERC721BasicToken.sol ```
- follow the comments and the test to implement a fully working smart contract.


## Advanced
- after finishing the main ERC-721 standard smart contract now lets make the smart contract perfect and fully functional

- open the full ERC-721 token smart contract ```~/contracts/ERC721Token.sol``` that is implementing the contract that you have done and start modifying the methods to be full working.



## Extra Credit
when you get the smart contract fully working now you need to build the functions that interact with smart contract via web3 on the client side.
to modify the methods you can ```~/src/js/app.js```
run the lite server to run the website on a local host by running ```npm run dev```
when you run it for the first time it will not be functional but your job is to implement the methods correctly and use the method ```App.setMesagge``` to show the result to the end user
be sure to compile the smart contract and deploy it on ganache using truffle by using this command ```truffle migrate --compile-all --reset```


## Nightmare Mode
deploy your token to ethereum rinkeby or reposten test networks or
> if you are rich enough ;) deploy it to the main etherum network.

## Useful Links
- [Truffle and ganache documentation]
- [Ganache]
- [Web3.0 readme]
- [Using Infura with web3.0]
- [ERC-721 website]





License
----

MIT
**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [Truffle and ganache documentation]: <https://www.trufflesuite.com/docs>
   [Ganache]: <https://www.trufflesuite.com/docs/ganache/overview>
   [Web3.0 readme]: <https://github.com/ethereum/web3.js/>
   [Using Infura with web3.0]: <https://web3j.readthedocs.io/en/latest/infura.html>
   [ERC-721 website]: <http://erc721.org>
   [here]: <https://www.trufflesuite.com/ganache>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>

