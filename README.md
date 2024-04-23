# Create-and-Mint-Token

## Overview
This Solidity smart contract implements the Energy Token (ET) on the Ethereum blockchain. MET is an ERC20-compliant token with a maximum total supply of 100 million.

## Contract Details
- **Solidity Version**: ^0.8.19
- **License**: MIT

## Contract Functions
1. **constructor**: Initializes the token with the name "Energy Token" and the symbol "MET", and mints 1 MET to the contract deployer.
2. **mint**: Allows the owner to mint new MET tokens and distribute them to specified addresses. Tokens are minted in multiples of 3.
3. **burn**: Allows token holders to burn their MET tokens, reducing the total supply.
4. **transfer**: Overrides the ERC20 `transfer` function to add a custom check for sufficient balance before transferring tokens.

## Custom Error Handling
The contract includes custom error handling for scenarios such as unauthorized access, exceeding maximum supply, and insufficient balance.

## Usage
1. Deploy the contract to a compatible Ethereum Virtual Machine (EVM) environment.
2. Interact with the contract using a blockchain client, wallet, or decentralized application (dApp).
3. Utilize the provided functions to mint, burn, and transfer MET tokens according to your project requirements.

## Dependencies
This contract imports the OpenZeppelin ERC20 library for implementing ERC20 standard functionalities.

## License
This project is licensed under the terms of the MIT license.

## Disclaimer
This smart contract is provided as-is, without any warranty. Use at your own risk.
- - -
