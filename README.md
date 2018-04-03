Smart Contracts

#### Introduction

From the official website of [Ethereum](https://ethereum.org):

> Ethereum is a decentralized platform that runs smart contracts: applications that run exactly as programmed without any possibility of downtime, censorship, fraud or third-party interference.

> These apps run on a custom built blockchain, an enormously powerful shared global infrastructure that can move value around and represent the ownership of property.

> This enables developers to create markets, store registries of debts or promises, move funds in accordance with instructions given long in the past (like a will or a futures contract) and many other things that have not been invented yet, all without a middleman or counterparty risk.

In a word, `Ethereum = blockchain + smart` contracts.

Using smart contracts, you can
- design and issue your own cryptocurrency
- kickstart a project with a trustless crowdsale
- create a democratic autonomous organization
- or build a new kind of decentralized application

#### Getting started

According to [Available Solidity Integrations](https://solidity.readthedocs.io/en/v0.4.21/#available-solidity-integrations), there are many toolkits you can use to develop smart contract. The most selective tools may be

- [Remix](https://remix.ethereum.org/): Browser-based IDE with integrated compiler and Solidity runtime environment without server-side components.
- [Truffle](http://truffleframework.com/): Truffle is the most popular development framework for Ethereum with a mission to make your life a whole lot easier.

This project uses Truffle for its fluent workflow, helpful boilerplates boxes and active community.

In this repository, there are mainly two contracts:
- ERC20 Token: [source code](contracts/TokenERC20Impl.sol), and Faxport's cryptocurrency FAS is issued via this contract, you can watch it at [https://etherscan.io/token/0xb47e9b43ee0772abac3856a1adf8f90c0e6c1067](https://etherscan.io/token/0xb47e9b43ee0772abac3856a1adf8f90c0e6c1067).
- Airdrop: [source code](contracts/Airdrop.sol). Faxport is [in sale stage now](https://faxport.io), FAS will be automatically distributed to users via this Airdrop contract.

#### Best practices

Ethereum and complex blockchain programs are new and highly experimental. Therefore, you should expect constant changes in the security landscape, as new bugs and security risks are discovered, and new best practices are developed. Thus, smart contract developers should reference [A guide to smart contract security best practices](https://github.com/ConsenSys/smart-contract-best-practices) to gain a different security mindset with these best practices.

#### Reference

- [Ethereum Project](https://ethereum.org/)
- [White Paper · ethereum/wiki Wiki](https://github.com/ethereum/wiki/wiki/White-Paper)
- [What Are Smart Contracts? A Beginner’s Guide to Smart Contracts](https://blockgeeks.com/guides/smart-contracts/)
- [Introduction to Smart Contracts — Solidity 0.4.21 documentation](https://solidity.readthedocs.io/en/v0.4.21/introduction-to-smart-contracts.html#the-ethereum-virtual-machine)
- [Create a cryptocurrency contract in Ethereum](https://www.ethereum.org/token)
- [Solidity — Solidity 0.4.21 documentation](https://solidity.readthedocs.io/en/v0.4.21/)
- [ERC20 Token Standard - The Ethereum Wiki](https://theethereum.wiki/w/index.php/ERC20_Token_Standard)
- [A guide to smart contract security best practices](https://github.com/ConsenSys/smart-contract-best-practices)
- [Remix](https://remix.ethereum.org/)
- [Truffle Suite - Your Ethereum Swiss Army Knife](http://truffleframework.com/)
- [https://etherscan.io/tokens](https://etherscan.io/tokens)
