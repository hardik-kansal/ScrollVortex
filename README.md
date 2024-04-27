# PayX - ScrollVortex Hackathon

## Project Summary

PayX, developed for the ScrollVortex Hackathon, enhances Non-Fungible Tokens (NFTs) and digital wallets, providing users with greater control and security over their assets. Users can mint unlimited NFTs, each associated with multiple wallets. Wallets have specific restrictions, ensuring proper fund allocation and utilization.

- **Minting NFTs:** Users can mint any number of NFTs, allowing for diverse asset representation within the blockchain.

- **Wallet Restrictions:** Each wallet is subject to restrictions:
  - **Admin-Only Deposits:** Only administrators can deposit ETH into wallets, ensuring centralized control.
  - **Owner Controls:** NFT owners can send ETH to specified addresses within a defined timeframe. Failure to do so results in locked funds, withdrawable by administrators.

## Problem Solving

PayX addresses the challenge of ensuring proper utilization of donated funds, such as for clothing donations. By enforcing wallet restrictions, the project ensures funds are used as intended, preventing misuse.

## Technologies Used

- **Solidity:** Programming language for Ethereum smart contracts.
- **Remix:** Online IDE for smart contract development.

## Repository Readme

- **Flexible NFT Minting:** Users can mint diverse NFTs, representing various assets.
- **Wallet Restrictions:** Administrators control wallet deposits, while owners have limited timeframes for fund usage.
- **Security and Transparency:** Smart contracts ensure secure and transparent fund handling.

### Usage Example

PayX enables organizations to facilitate clothing donations. NFTs represent clothing items, each linked to a wallet with ETH funds for purchasing. Administrators control fund allocation, while owners must use funds within allocated timeframes.

### Additional Information

- **Tests:** Comprehensive tests ensure smart contract functionality.
- **Deployment Scripts:** Scripts facilitate easy smart contract deployment.

