# NODDE

![изображение](https://github.com/nodde-web3/.github/assets/10999015/fd3ad854-e46c-4caf-9e07-f2240841047f)

Web3 platform for receiving donations and promoting paid content. 

Full project description you can find [here](https://elated-couch-eca.notion.site/Full-presentation-cc5fae9085d74dae97002608c9cc056a)

Technical assignment [here](https://elated-couch-eca.notion.site/Technical-Assignment-742e4c11738c4c7d9a05d70eb6208842)

https://community-front-henna.vercel.app

### Core Features

- Author Profiles
- Donations
  - Receive donations from subscribers;
  - Choose tokents you want to receive;
  - Uniswap V3 integration. Users can donate you using any token;
  - Get donation statistics and rewards;
- Subscriptions
  - Create paid subscriptions and link them to Telegram groups;

## Build With

- React 

  Form, Hooks, Drop Image
  
- Next.js

- Rainbowkit

  Wallet UI
  
- Current Blockchains

  BNB Chain (Testnet)  
  
- Amazon Web Services
 
  Lambdas, Dynamo DB, S3, CloudWatch
  
- Uniswap V3

  Convert tokens when donate to an author
- Chainlink  

  We use chainlink in donates statistics to display rewards in crypto -> fiat equivalent 

## High Level Architercture Diagram

![high-level-architecture-diagram](https://github.com/nodde-web3/.github/assets/10999015/c9537d68-f779-46a0-beae-d09cdc25b25d)

## Module Descriptions

### Frontent

Frontend and serverside renderer.

[https://community-front-henna.vercel.app](https://community-front-henna.vercel.app/)

#### Live Features

- Public
  - Connect wallet
  - Main page
  - Send donate 
  - Pay for subscriptions
  - Get invite link to telegram chats

- Author
  - Create auhor profile
  - Set donations
  - Create subscriptions

Frontend code can be found at the [repository](https://github.com/nodde-web3/community-front)

### Smart Contracts

Smart contracts code can be found at the [repository](https://github.com/nodde-web3/smart-contracts)

[Detail description](https://elated-couch-eca.notion.site/Smart-Contract-5063c1d752364e23ad0611c2e64f30d5)

#### Testnet

Binance Smart Chain:

- NFT Profile Contract
[0x66e8cf86ae35a96e4b67021689b4fcf47c3267c5](https://testnet.bscscan.com/address/0x66e8cf86ae35a96e4b67021689b4fcf47c3267c5#code)

- Donations Contract
[0x1F143C116A4B4E4AC650BE248BE8F4d1C935Ed3C](https://testnet.bscscan.com/address/0x1F143C116A4B4E4AC650BE248BE8F4d1C935Ed3C#code)

- Subscrioption Contract
[0xc65136CA205FbefBcB30466dD62A742a1B372327](https://testnet.bscscan.com/address/0xc65136CA205FbefBcB30466dD62A742a1B372327#code)


### Nodde Backend

Backend of the platform.

[Sequence diagrams](https://elated-couch-eca.notion.site/Backend-56e08b8188634ff0b2939ddb7cf1ec84)

[Repository link](https://github.com/nodde-web3/nodde-backend)

### Telegram Bot

Backend for interacting with Telegram.

[Sequence diagrams](https://elated-couch-eca.notion.site/Backend-56e08b8188634ff0b2939ddb7cf1ec84)

[Repository link](https://github.com/nodde-web3/community-telegram-lambdas)

