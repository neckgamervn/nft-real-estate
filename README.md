# NFT

## Overview

This project is a full-stack web3 development, that is built in react/javascript, solidity and CSS. The program renders a
website, where clients can mint real estate by inputting the address and description of the house they would like to mint to
the ethereum blockchain.

## Instructions

1. Install metamask for chrome: https://metamask.io/download.html
2. Install ganache (private blockchain for testing): https://www.trufflesuite.com/ganache
3. Open ganache, do quickstart, then on the far right side of the first address click the key icon, copy the private key,
   add that private key into your meta mask to make an account and call it something like ganache testing
4. Add a custom rpc on meta mask for ganache: name it ganache network, all info for all fields is found on the top bar of your
   ganache application you have open.
5. To get the script working, type the following commands into a new terminal window...

- git clone https://github.com/neckgamervn/nft-real-estate nft-realestate
- cd nft-realestate
- yarn install
- yarn start

6. run `npm install -g truffle` Then `truffle compile`. Then run `truffle migrate`. You will create a new `build` folder. Delete folder `src/build`, and move the new one into its place.
7. Open in a chrome browser: http://localhost:3000/
8. Choose the ganache testing account in metamask which should be loaded with 100 ETH for testing, and choose the ganache
   network you added to connect.
