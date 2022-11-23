# NFT-TCG

Disclaimer some assets used in this project are not open source and so by accident the project was violating some copyright issues, as such the code has been removed and an example of the code can only be viewed via the included video or by the demo provided.

## Summary

This TCG uses NFTs as cards allowing users to compete using their own custom decks or by renting a default deck. The build created allows for single player with a bot or competition against another person over LAN. The project would've been set up for the players to bet NFTs that they judge to be of equal value however due to the conditions of the hackathon it was decided that it would likely be irratating to be constantly transfering the NFTs between accounts as you would only be able to play on LAN likely against yourself or against a bot that can't bet.

## How does the IPFS integration work?
Watch the video for a more in depth explanation of all aspects of the game however the IPFS aspects will be explained again in a simplified version here.

The project uses NFT.Storage a file storage system running off IPFS in order to store two files per card which is the metadata and the image that's linked inside. The project then loads each image from a supplied cid to display in card previews to display each card. In addition whenever a player chooses to mint a card it uses the cid of the metadata stored on NFT.Storage in order to create the NFT.

## Development

This project was developed with:
- Unity 2021.3.11f1 (C#)
- NFT.Storage (IPFS)
- Remix (Solidity)

## Token Info

Chain:
Polygon

Network:
Testnet

Token Contract Address:
0x780C19b1bf9478d061095E253b322dA3Ce9D6D94

Token Symbol:
CARD