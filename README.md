# simple_contract_compiler

### Documentation
https://hardhat.org/tutorial

## Installation
Follow this guide or

Install node js from official site https://nodejs.org/en/download

Run in project root
```
npm install
```

## Contract
Generate a contract using Chat GPT or create your own and input it to contracts/contract.sol file

**If you want the cheapest contracts, ask Chat GPT to create it with minimal bytecode.**

In general, less code, less bytecode

## Compile
Run in project root
```
npx hardhat compile
```

This will generate artifacts/contracts/contract.sol directory.

Abi and bytecode of your contract are located inside .json file inside that directory.
