# Laminar Finance

A web app that allows users to pay and receive payments in the real world by signing a transaction via dynamically created QR codes.

Deployment Link : https://storied-elf-969a20.netlify.app/

## Description

Pay only for what you use, and get paid for the hours you work.

## :question: Problem

How do users pay only for what they use in a decentralized manner?

## :star: Our solution

- Users create an account. They deposit funds to be used.

- Users check in using a QR Code.

- Funds automatically stream to the service provider by the second.

- Users check-out using a QR Code, funds are stopped from streaming.

- User only paid for what they used.

![overview.drawio.svg](<https://github.com/Laminar-Finance/.github/blob/main/profile/diagrams/userflows/overview.drawio.svg>)

## :book: Learning

### Superfluid

<https://github.com/superfluid-finance>

### QR Codes

### Coinbase Wallet

### Web3Auth

<https://github.com/Web3Auth/Web3Auth>

<https://demo-app.web3auth.io/>

#### Installing Superfluid Monorepo

```txt
git clone https://github.com/superfluid-finance/protocol-monorepo
cd ./protocol-monorepo/example/continous-auction-hardhat
yarn install
yarn test
```

## 💰 Sponsor Prizes

1. SuperFluid
2. Polygon
3. To add more...

## :pencil: TODOs

### Pre-development

- [ ] Research more on sponsor prizes if we can submit our project for more categories (@dominicacodes)

- [x] Setup Frontend Repo
- [x] Setup Backend Repo
- [x] Setup Vercel or Netlify
- [ ] Purchase Domain
- [ ] - [ ] Work out how walletconnect works

- [ ] Superfluid Research (lewingtonpitsos)

  - [ ] Install Superfluid SDK

    - [ ] Install nvm (Node Version Manager, used for managing which node.js and npm version is in use): <https://github.com/nvm-sh/nvm#installing-and-updating>
    - [ ] Install npm using nvm (Node Package Manger, used for installing node.js packages): <https://github.com/nvm-sh/nvm#intro>
    - [ ] Install Yarn with npm: <https://classic.yarnpkg.com/lang/en/docs/install/#debian-stable>
    - [ ] Install Foundary: <https://github.com/foundry-rs/foundry> # some tools for developing with ethereum
          650 test should pass
    - [ ] Download the main superfluid repo and initialize it locally using Yarn (650 test cases should pass):

    ```txt
    git clone https://github.com/superfluid-finance/protocol-monorepo
    cd ./protocol-monorepo/examples/continous-auction-hardhat
    yarn install
    npm install @openzeppelin/contracts # louka had to do this to prevent import errors
    yarn add graphql -W # this was done to prevent an error
    yarn build
    yarn test
    ```

- [ ] Creating a new wrapped superfluid token

- [ ] Other Research
  - [ ] ERC20
  - [ ] ERC777
  - [ ] Redirecting Superfluid Streams

### Development

- [ ] Smart Contract
  - [ ] Interface for Payment Receiver
  - [ ] Payment Receiver
  - [ ] Deploy Smart Contract on Mumbai
  - [ ] Document ABI + Address of Deployment
  - [ ] Receive Superfluid Stream @Lewington-pitsos
  - [ ] Stop Superfluid Stream when checkout (@Lewington-pitsos)
- [ ] Frontend

- [ ] Backend
  - [ ] Websocket Listener to listen for check-in Event

## 🛠️ Technicals

We will use Next js for developing the mobile application

## :bulb: Initial Ideas

- ~~Time-based insurance premiums with Superfluid~~
- ~~Time-based advertisement space rental with Superfluid~~
- ~~Time & space usage based payment for decentralized file storage with Superfluid and Filecoin~~
- ~~Time-based general payment system with Superfluid~~
