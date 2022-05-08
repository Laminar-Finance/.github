# Laminar Finance 
Hackmoney 2022

Integration of Superfluid onto the Golem Network. Golem Network is a decentralized cloud compute service. It is currently lacking a streaming payment method such that users can accurately pay for what they use. This is where Superfluid comes in.

## :bulb: Ideas

- ~~Time-based insurance premiums with Superfluid~~
- ~~Time-based advertisement space rental with Superfluid~~
- ~~Time & space usage based payment for decentralized file storage with Superfluid and Filecoin~~
- ~~Time-based general payment system with Superfluid~~

## :book: Learning

### Superfluid

<https://github.com/superfluid-finance>

#### Installing Superfluid Monorepo

```
git clone https://github.com/superfluid-finance/protocol-monorepo
cd ./protocol-monorepo/example/continous-auction-hardhat
yarn install
yarn test
```

### Filecoin

<https://docs.filecoin.io/about-filecoin/what-is-filecoin>

## 💰 Sponsor Prizes

1. SuperFluid
2. Polygon

## TODOs

### Pre-development

- [ ] Research more on sponsor prizes if we can submit our project for more categories

- [ ] Setup Frontend Repo
- [ ] Setup Backend Repo
- [ ] Setup Vercel
- [ ] Setup Heroku (if required)
- [ ] Purchase Domain

- [ ] Superfluid Research
    - [ ] Install Superfluid SDK
        - [ ] Install nvm (Node Version Manager, used for managing which node.js and npm version is in use): https://github.com/nvm-sh/nvm#installing-and-updating
        - [ ] Install npm using nvm (Node Package Manger, used for installing node.js packages): https://github.com/nvm-sh/nvm#intro
        - [ ] Install Yarn with npm: https://classic.yarnpkg.com/lang/en/docs/install/#debian-stable
        - [ ] Download the main superfluid repo and initialize it locally using Yarn: 
        ```
        git clone https://github.com/superfluid-finance/protocol-monorepo
        cd ./protocol-monorepo/examples/continous-auction-hardhat
        yarn install
        npm install @openzeppelin/contracts # louka had to do this to prevent import errors
        yarn add graphql -W # this was done to prevent an error
        yarn test
        ```
        
        650 test should pass
    - [ ] Checkout Superfluid Examples on their monorepo (see the hardhat ones)
    - [ ] Creating a new wrapped superfluid token

- [ ] Golem Research
    - [ ] Install Golems
    - [ ] How do requestors pay?
    - [ ] How do requestors request for compute resources? (User flow)
    - [ ] How do providers provide compute resources?
    - [ ] How do providers receive payments?
    - [ ] How are compute resources pooled
    - [ ] How are compute resources extracted from the pool

- [ ] Other Research
    - [ ] ERC20
    - [ ] ERC777
    - [ ] Redirecting Superfluid Streams


### Development
