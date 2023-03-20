# IBC 2023 Final Project: Decentralized Raffle System using Verifiable Random Function
inspire by Inspired by “Build a Raffle App With Solidity and NextJS: Code Along” *[Youtube](https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=59647s)* video tutorial provided by Patrick Collins from Chainlink

![App](img/readme-app.png)


# Getting Started

## Requirements

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  - You'll know you did it right if you can run `git --version` and you see a response like `git version x.x.x`
- [Nodejs](https://nodejs.org/en/)
  - You'll know you've installed nodejs right if you can run:
    - `node --version` and get an ouput like: `vx.x.x`
- [Yarn](https://yarnpkg.com/getting-started/install) instead of `npm`
  - You'll know you've installed yarn right if you can run:
    - `yarn --version` and get an output like: `x.x.x`
    - You might need to [install it with `npm`](https://classic.yarnpkg.com/lang/en/docs/install/) or `corepack`

## Quickstart

```
git clone https://github.com/suparatsrifa/IBC2023_Group_Project
cd IBC2023_Group_Project
yarn
yarn dev
```


# Usage

1. Deploy "RaffleVRF.sol" (e.g = Remix) with valid *[Chainlinnk Subscription ID](https://vrf.chain.link/)* input

2. Get contract address

3. Replace contract address in /components/RaffleEntrance.js

3. Run this code (use different terminal calling from this repo)

```
yarn dev
```

4. Go to UI [http://localhost:3000](http://localhost:3000)




## Testing




