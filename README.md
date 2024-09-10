On this marketplace you can make offers and listings of ERC721 Tokens on the chains supported by 0x smart contracts, namely: Ethereum, Binance Smart Chain, Polygon, Fantom, Avalanche, Celo and Optimism.

# How to Start

clone this repo

```
git clone https://github.com/trueuni/open-nft-marketplace.git
```

Install it:

```sh
yarn
```

Create an .env file with INFURA_API_KEY set with your Infura API key and then run the app

```sh
yarn dev
```

# Contributing

Check [Contributing](CONTRIBUTING.md) for a more in depth way how to contribute.

# Tech used

Started from [NEXT JS + Material UI+ Typescript + Boilerplat](https://github.com/mui/material-ui/tree/master/examples/nextjs-with-typescript)

Additionally we use trader sdk to handle nft smart contract interactions, react query to handle all http and blockchain requests, format js for internalization, web3 react to handle wallet logic. You can check our requirements [here](REQUIREMENTS.md).

# Roadmap

We will be adding any new evm network that 0x smart contracts will support.

It is also planned to extract all common hooks and state used to interact with the blockchain to a library repo.

# Premium feature?

We at the moment consider premium features as follows:

- [ ] - NFT trading history

- [ ] - Artist page

- [ ] - Cache optimizations

- [ ] - Fetch NFT and token balances via api without the need to import, using Alchemy for instance

- [ ] - Swap ERC20 <-> ERC20 tokens

- [ ] - Collection level stats like orders, max supply, floor price, number of trades

- [ ] - Improved SEO
