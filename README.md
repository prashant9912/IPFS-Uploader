# IPFS Image Uploader Dapp
A simple application that lets users upload an image (stored using IPFS and Ethereum blockchain) and displays the image.

## Dependencies
- Truffle
- Solidity
- React.js
- web3
- Infuria
- IPFS API: ipfs-http-api

## Storage
Images are uploaded to IPFS with the reference stored in a smart contract deployed on the Ethereum blockchain. This reference allows access to the file on IPFS.

## Client App
Built using React.js.

## Screenshot
<img src="https://i.imgur.com/mX6w538.png">

## How to Use

Install Ganache Ethereum

Run 👇🏼 in project dir
$ truffle unbox react
$ truffle migrate --reset

run react project

connect metamask with ganache & use that
