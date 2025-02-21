# Ampleforth

[![Build Status](https://travis-ci.com/ampleforth/uFragments.svg?token=xxNsLhLrTiyG3pc78i5v&branch=master)](https://travis-ci.com/ampleforth/uFragments)&nbsp;&nbsp;[![Coverage Status](https://coveralls.io/repos/github/frgprotocol/uFragments/badge.svg?branch=master&t=GiWi8p)](https://coveralls.io/github/frgprotocol/uFragments?branch=master)

Ampleforth (code name uFragments) is a decentralized elastic supply protocol. It maintains a stable unit price by adjusting supply directly to and from wallet holders. You can read the [whitepaper](https://www.ampleforth.org/paper/) for the motivation and a complete description of the protocol.

This repository is a collection of [smart contracts](http://ampleforth.org/docs) that implement the Ampleforth protocol on the Ethereum blockchain.

The official mainnet addresses are:

- ERC-20 Token: [0xD46bA6D942050d489DBd938a2C909A5d5039A161](https://etherscan.io/token/0xd46ba6d942050d489dbd938a2c909a5d5039a161)
- Supply Policy: [0x1B228a749077b8e307C5856cE62Ef35d96Dca2ea](https://etherscan.io/address/0x1b228a749077b8e307c5856ce62ef35d96dca2ea)
- Orchestrator: [0x6fb00a180781e75f87e2b690af0196baa77c7e7c](https://etherscan.io/address/0x6fb00a180781e75f87e2b690af0196baa77c7e7c)
- Market Oracle: [0x99c9775e076fdf99388c029550155032ba2d8914](https://etherscan.io/address/0x99c9775e076fdf99388c029550155032ba2d8914)
- CPI Oracle: [0xa759f960dd59a1ad32c995ecabe802a0c35f244f](https://etherscan.io/address/0xa759f960dd59a1ad32c995ecabe802a0c35f244f)

## Table of Contents

- [Install](#install)
- [Testing](#testing)
- [Testnets](#testnets)
- [Contribute](#contribute)
- [License](#license)

## Install

```bash
# Install project dependencies
yarn
```

## Testing

```bash
# Run all unit tests (compatible with node v12+)
yarn test
```

## Testnets

There is a testnet deployment on Rinkeby. It rebases hourly using real market data.

- ERC-20 Token: [0x027dbcA046ca156De9622cD1e2D907d375e53aa7](https://rinkeby.etherscan.io/token/0x027dbcA046ca156De9622cD1e2D907d375e53aa7)
- Supply Policy: [0x1D2771AFC894107c4edc072e3bd15Cb7F1BCC007](https://rinkeby.etherscan.io/address/0x1D2771AFC894107c4edc072e3bd15Cb7F1BCC007)
- Orchestrator: [0xF473604Be74A69a6bB4ebED33A91a291f6C5b5DE](https://rinkeby.etherscan.io/address/0xF473604Be74A69a6bB4ebED33A91a291f6C5b5DE)
- Market Oracle: [0x47fB203e1d75FB2c518Cd56f3a8094D22A46aF83](https://rinkeby.etherscan.io/address/0x47fB203e1d75FB2c518Cd56f3a8094D22A46aF83)
- CPI Oracle: [0xDB021b1B247fe2F1fa57e0A87C748Cc1E321F07F](https://rinkeby.etherscan.io/address/0xDB021b1B247fe2F1fa57e0A87C748Cc1E321F07F)


### MATIC MUMBAI TESTNET

Deployer https://explorer-mumbai.maticvigil.com/address/0x2EB8291d3a6b72cf55B000610B6485b68783D330/transactions

- ERC20 Contract: [0xDfCE65e45c3C34f6e2D83bb8a0563B149AF05d99](https://explorer-mumbai.maticvigil.com/address/0xDfCE65e45c3C34f6e2D83bb8a0563B149AF05d99/transactions)
- Supply Policy: [0x39DD9FC129Da34234EAcf673c24c7860C9588991](https://explorer-mumbai.maticvigil.com/address/0x39DD9FC129Da34234EAcf673c24c7860C9588991/transactions)
- Orchestrator: [0xAC6D411B0c1d1745c7DE079CAC646c0C528A92C9](https://explorer-mumbai.maticvigil.com/address/0xAC6D411B0c1d1745c7DE079CAC646c0C528A92C9/transactions)
- Market oracle: [0xa2c90542Cb9E2fD85d69fe658fD92168156E7F17](https://explorer-mumbai.maticvigil.com/address/0xa2c90542Cb9E2fD85d69fe658fD92168156E7F17/transactions)
- CPI oracle: [0xF592fE5A49ADcc487E84c95870716daEf5BeEe6F](https://explorer-mumbai.maticvigil.com/address/0xF592fE5A49ADcc487E84c95870716daEf5BeEe6F/transactions)

## Contribute

To report bugs within this package, create an issue in this repository.
For security issues, please contact dev-support@ampleforth.org.
When submitting code ensure that it is free of lint errors and has 100% test coverage.

```bash
# Lint code
yarn lint

# Format code
yarn format

# Run solidity coverage report (compatible with node v12)
yarn coverage

# Run solidity gas usage report
yarn profile
```

## License

[GNU General Public License v3.0 (c) 2018 Fragments, Inc.](./LICENSE)
