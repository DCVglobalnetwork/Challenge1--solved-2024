# Challenge #1 - Unstoppable solved 2024

***There’s a tokenized vault with a million DVT tokens deposited. It’s offering flash loans for free, until the grace period ends.***

***To pass the challenge, make the vault stop offering flash loans.***

***You start with 10 DVT tokens in balance.***

## Two contracts

**ReceiverUnstoppable.sol** 

*implements the vault that offers flash loans. It imports the tokenized vault standard, ERC-4626, and the interface for flash borrower and lender.*

**UnstoppableVault.sol** 

*implements the borrower contract, allowing an user to initiate flash loan from UnstoppableVault.*

## The Solution

navigate to a folder *test* to a file *unstoppable.challenge.js*
```shell
it('Execution', async function () {
        /** CODE YOUR SOLUTION HERE */
        await token.connect(player).transfer(vault.address, 5);
    });
```

## Run the test

```shell
yarn unstoppable
```

![image](https://github.com/DCVglobalnetwork/Challenge1--solved-2024/assets/105791829/d026f3e3-633b-4888-9380-4dc35f94679d)







![](cover.png)

**A set of challenges to learn offensive security of smart contracts in Ethereum.**

Featuring flash loans, price oracles, governance, NFTs, lending pools, smart contract wallets, timelocks, and more!

## Play

Visit [damnvulnerabledefi.xyz](https://damnvulnerabledefi.xyz)

## Help

For Q&A and troubleshooting running Damn Vulnerable DeFi, go [here](https://github.com/tinchoabbate/damn-vulnerable-defi/discussions/categories/support-q-a-troubleshooting).

## Disclaimer

All Solidity code, practices and patterns in this repository are DAMN VULNERABLE and for educational purposes only.

DO NOT USE IN PRODUCTION.
