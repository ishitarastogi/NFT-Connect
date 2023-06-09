# NFT Connect

## Table of Content

- [Project Description](#project-description)
- [Repo Description](#repo-description)
- [Technologies Used](#technologies-used)
- [Concepts Used](#concepts-used)
- [Folder Structure](#a-typical-top-level-directory-layout)
- [Install and Run](#install-and-run)
- [User Flow](#user-flow)

## Project Description

Our application enables users to connect with NFT/ENS owners and communicate with them via PUSH Chat. They can also initiate video calls using Huddle01 to express their interest in a specific NFT/ENS and negotiate. The NFT owner will receive a PUSH Notification when someone searches for their NFT on our platform.

## Repo Description

The repository holds the source code for our web-app and NFT contract.

## Technologies Used

(List of technology or external libraries used)

- Soldity
- Openzepplein
- react

## Concepts Used

- ERC-721

## Protocols Used

- PUSH Protocols
- Huddle01
- FVM

## Install and Run

- Run `npm install` to install dependencies
- Run `npm run start` to compile all contracts

## User Flow

Our platform is designed for NFT holders, collectors, and ENS holders who can opt-in/subscribe to our `push channel` through our website or the push website.
Once a user has `opted-in`, they will be eligible to receive notifications.

As an NFT explorer/user, you can find a desired NFT or ENS on our platform through `Opensea Link`, `ENS domain`, `NFT address` and `NFT ID`.
The ENS/NFT admin will receive a notification(`push notification`) of interest from someone in their NFT.

Our platform then enables you to communicate with the NFT/ENS owner through the `Push chat` and express your interest in buying the NFT, you can also negotiate with them. User can connect with them via video call, powered by `Huddle01`.

In addition to our web-application, we have also created an `NFT smart contract` that incorporates the `opt-in` and `opt-out` functionality through the `PUSH communicator` contract. This allows NFT projects to directly integrate these functions into their own platform by connecting through their own NFT contract.

## Screenshots

### - Search your favourite NFTs and connect with the owner via Push chat and Huddle01

1. Opensea URL
   <img width="1423" alt="Screenshot 2023-02-06 at 9 46 52 PM" src="https://user-images.githubusercontent.com/46647968/217025399-63d00c25-45ff-4ffc-ac1a-68dc691bf9bf.png">
2. Contract address and token ID

3.ENS Name
<img width="1380" alt="Screenshot 2023-02-06 at 9 50 57 PM" src="https://user-images.githubusercontent.com/46647968/217026298-96ec1c84-17e9-4206-b5f1-86dfa95ba7a5.png">

### NFT owner will get notification when someone view their NFTs

<img width="1130" alt="Screenshot 2023-02-06 at 9 52 33 PM" src="https://user-images.githubusercontent.com/46647968/217026709-3b50407f-3de5-420f-8e32-f1b254be9cca.png">

## Channel Address

- 0x9147BDf9aaca01B5f2680633e254a9776ecB10e5

## Deployed Transaction

- https://hyperspace.filfox.info/en/tx/0x33046235c834738ee7be655bfb9629c72401d5ae7a5b12d5569067b528932d34
